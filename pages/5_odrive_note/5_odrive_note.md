---
layout: page
title: Note on Odrive 3.6
permalink: /pages/5_odrive_note/
nav_order: 5
---

# Note on Odrive 3.6 :ferris_wheel:

P.S. Now there is a new version of Odrive. My note refers to Odrive 3.6. This note is intended as an archived reference for future members in [EIC Chula](https://web.facebook.com/eicchulalongkorn). However, this is public.

In [RoboCup 2022 @Home Open Platform League](https://athome.robocup.org/2022-qualified-teams/), our robot *Walkie* ([his/her own Instagram](https://www.instagram.com/walkie_eic/)) used [hoverboard motors](https://www.amazon.com/HULKWHEELS-Electric-Brushless-Toothless-Skateboard/dp/B08BFPTWCZ) for his/her base movement. The controller is Odrive 3.6.

{: .warning } 
Always cautious because there is always a risk of breaking your board (and it's expensive!)

To begin the setup, please refer to [here](https://docs.odriverobotics.com/v/0.5.5/getting-started.html). I recommend that you use [Anaconda](https://www.anaconda.com/) if you want to test the board and the motor with your laptop for the first time. Usually, the Windows user will find a problem(s) with firmware, so please install it (*Zadig*) from [here](https://docs.odriverobotics.com/v/0.5.5/odrivetool.html#troubleshooting). 

{: .note } 
In Raspberry Pi (Linux), if you are a Linux newbie like me, you may not know how to access a USB. My friend told me to run `chmod a+rw /dev/ttyACM0` and `chmod a+rw /dev/ttyAMA0` to make USB terminals work for Odrive.

For the hoverboard setup, you can refer to [here](https://docs.odriverobotics.com/v/0.5.5/hoverboard.html). Usually, the Hall sensor's wire colors of a motor (maybe it is from China or somewhere) do not match the documentation (their signal orders are reversed, for example). I recommend that you use an oscilloscope to track the signal from the Hall sensor's wire first. (Before doing that, please plug those wires into the Odrive's A, B, and Z first because Hall sensors' signals require a pull-up resistor to make the signal strong enough to drive things. Maybe you connect those on a breadboard and then plug in other external wires to probe the signals using an oscillator. If you don't have an oscillator that has three or more inputs, you can use Arduino to track the signals by using a high baud rate and send a serial message when the signals change their values from 0 to 1.)

Then, follow the documentation carefully. This is the Python code to set up all of those steps in one instance. (You can run it on Spyder if you have Anaconda on your laptop.)

```python
import odrive
from odrive.enums import *

odrv0 = odrive.find_any()
print(odrv0)
odrv0.axis1.motor.config.current_lim = 6
odrv0.axis1.controller.config.vel_limit = 2
odrv0.axis1.motor.config.calibration_current = 1
odrv0.axis1.motor.config.pole_pairs = 15
odrv0.axis1.motor.config.torque_constant = 0.27566667
odrv0.axis1.motor.config.motor_type=MOTOR_TYPE_HIGH_CURRENT

odrv0.axis1.encoder.config.mode = ENCODER_MODE_HALL
odrv0.axis1.encoder.config.cpr = 90
odrv0.axis1.encoder.config.calib_scan_distance = 150
odrv0.axis1.encoder.config.bandwidth = 100
odrv0.axis1.controller.config.pos_gain = 1
odrv0.axis1.controller.config.vel_gain = 0.02 * odrv0.axis1.motor.config.torque_constant * odrv0.axis1.encoder.config.cpr
odrv0.axis1.controller.config.vel_integrator_gain = 0.1 * odrv0.axis1.motor.config.torque_constant * odrv0.axis1.encoder.config.cpr
odrv0.axis1.controller.config.vel_limit = 10
odrv0.axis1.requested_state = AXIS_STATE_FULL_CALIBRATION_SEQUENCE
odrv0.axis1.controller.config.control_mode = CONTROL_MODE_VELOCITY_CONTROL
```

Please modify `odrv0.axis1.motor.config.calibration_current` to a suitable value. (Don't change it too quickly, so you will not break the board!) If the calibration procedure is not successful. If it is too little, the motor will not have enough force to finish the pole counts properly. Also, please limit the motor velocity `odrv0.axis1.controller.config.vel_limit` in the first test. Its unit is round per second. You don't want to mess around with some motor jerks for sure.

{: .note } 
If you run both the terminal and any Python IDE at the same time, they will fight for access to the USB. So, please run only one at a time. I recommend that, for the first time, running on the terminal is the best way. When everything works, gather all the steps into one Python code.

After you finish calibration, there should be no error. 

You can see [here](https://drive.google.com/file/d/1Dos8hIA3wKShhRdPNJD6h-djf7STYQrp/view?usp=sharing) that the accuracy of speed is very good, even though the Hall sensor's CPR is only 90. (In the video, the motor is being driven with a velocity of 2 rounds per second, so the measurement reads and displays 120 rounds per minute.)

You can use this code to see how the variation of speed changes over time. This is helpful when you want to tune the PID variables.

```python
import odrive
from odrive.enums import *
from odrive.utils import start_liveplotter
import time

import matplotlib.pyplot as plt
import numpy as np

odrv0 = odrive.find_any()
print(odrv0)

vel = 0.5
P = 6.5
I = 2.5

seconds = 10

odrv0.axis0.controller.config.vel_gain = P
odrv0.axis1.controller.config.vel_gain = P

odrv0.axis0.controller.config.vel_integrator_gain = I
odrv0.axis1.controller.config.vel_integrator_gain = I

odrv0.axis0.requested_state = AXIS_STATE_CLOSED_LOOP_CONTROL
odrv0.axis0.controller.input_vel=-vel
odrv0.axis1.requested_state = AXIS_STATE_CLOSED_LOOP_CONTROL
odrv0.axis1.controller.input_vel=vel

vel_data = [];

for i in range(seconds*4):
    vel_data.append(-odrv0.axis0.encoder.vel_estimate)
    time.sleep(0.25)

odrv0.axis0.controller.input_vel=0
odrv0.axis0.requested_state = AXIS_STATE_IDLE
odrv0.axis1.controller.input_vel=0
odrv0.axis1.requested_state = AXIS_STATE_IDLE

xpoints = np.array(range(seconds*4))
ypoints = np.array(vel_data)

plt.plot(xpoints, ypoints)
plt.show()
```
