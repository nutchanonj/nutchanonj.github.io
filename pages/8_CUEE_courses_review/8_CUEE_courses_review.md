---
layout: page
title: CUEE Courses Review
permalink: /pages/8_CUEE_courses_review/
nav_order: 8
---

# CUEE (formerly EECU) Courses Review by Nutchanon J :books:

{: .note } 
This is still under construction! :construction:

This review does not emphasize on how the professors teach each subject. The review summarize why we should learn on this topic, and how can it be applied to subsequent courses.

Also, this review will be very centered on electronics and control systems, since I pursue in my study on these two fields.

The recommended textbooks will be written with **boldface**.

## Year 2 Semester 1

![Bhumibol Bridge](bhumibol-bridge.jpg)
*Bhumibol Bridge (Photo from Yee Associates)*

### ELECT ENG MATH I

You will learn about all techniques involved in solving differential equations, solving difference equations, learning about Fourier series and Fourier transform, Laplace transform, Z-transform. Lastly, you will learn to solve partial differential equations (PDEs.)

Firstly, you will solve them (linear differential equations, linear difference equations) the hard way (characteristic equations and some very magical techniques,) and then, bam, you discover that Laplace transform and Z-transform really help you in solving those more easily.

Fourier series and Fourier transform will be appeared in many communication courses, because they are the methods by which the waves are decomposed. Fourier series is applied on periodic waves and Fourier transform is applied on aperiodic waves. Both are related and I persuade you to find that connection.

Laplace transform will be appeared in every subject related to control system theory. The word “transfer function” is heavily relied on Laplace transform. You will find this word the first time in CIR THEORY I/LAB, when you learn about the frequency response of a circuit.

Z-transform will be found in discrete-time system analysis. The digital control system and digital signal processing courses are heavily relied on Z-transform. However, you will not study those courses until the 4th year of EE.

Partial differential equations will not be found in many EE courses (in my opinion.) It’s appeared on electromagnetics and quantum mechanics. If you want to pursue those courses in the future, I recommend that you should learn PDEs thoroughly.

I recommend that you learn the course from **[Ajarn Supatana](https://ee.eng.chula.ac.th/supatana-auethavekiat/)’s lecture notes**, and also her scrap papers during her teaching, since her techniques on solving this math are really wonderful. Some techniques are not even presented on modern textbooks anymore.

The class skips these topics: Series solutions of linear equations (you will miss some special functions like Bessel’s or Legendre’s,) Systems of linear and nonlinear equations ( you will see those in LIN CON SYS I anyway, but you will miss something like phase portraits,) Numerical methods (of which, in the past, is separated to another advanced course, but now that course is abolished. Maybe because now, it is a computer who took the job!?)

For those who want to rely on textbook, I recommend **Differential Equations with Boundary Value Problems by Dennis G. Zill**. If you have time and dedication, I think you should read that book entirely. For Z-Transform, you will need other textbooks. I recommend **Discrete-Time Signal Processing by Oppenheim** or **Digital Control System Analysis and Design by Charles L. Phillips**.

For the exams, I do not recommend that you rely on textbooks, since the exams will be much harder than the problems in textbooks. Instead, rely on [Ajarn Supatana](https://ee.eng.chula.ac.th/supatana-auethavekiat/)’s lecture notes and her collected former exams.

---

### PROB STAT ELEC ENG

You will learn all of the basics in statistics required in EE. The course is very easy in my opinion.

For the main textbook accompanied with the teaching, please refer to prof. However, these are my recommendation for those who are really into it.

**Introduction to Probability by Joe Blitzstein and Jessica Hwang**: This is my FAVORITE book so far! I recommend that if you really want to understand and to have a very strong foundation on statistics, this book is a must. The book covers all of topics before midterm. For the topics after that, you need another textbook, that is:

**Mathematical Statistics with Applications by Dennis Wackerly**: This book is better than other textbooks because of its very strong mathematical handling. I recommend that if you really want to understand statistics to its mathematical core, this book is also a must. The book covers all of topics after midterm, and additionally covers many interesting topics, such as linear modeling, ANOVA, categorical data, nonparametric statistics, and Bayesian inference. I myself finished this book after the course because the topics provided are so interesting.

**Introductory Statistics by Neil A. Weiss**: For those who have time, I found this book to be more practical, not heavily theoretical, so that you can see more easily how statistics can be applied to the real world problems. I think it is suitable for someone who do not want to learn stats by seeing many, many math theorems.

---

### CIR THEORY I/LAB

This is essential for every EE student, period.

The textbook used by prof for many years is **Engineering Circuit Analysis by William H. Hayt**. However, I found some error(s) in that book that I do personally not recommend it. The book that I recommend is **Fundamentals of Electric Circuits by Charles K. Alexander, Matthew N.O. Sadiku**.

The book (6th edition) covers all of the topics that you require to learn in this course. The prof will skip Chapter 6, 7, and 8 because those first- and second-order circuits can be solved more easily by Laplace transform, not direct ODE. Furthermore, I strongly recommend that you understand the Bode plot to comprehend the frequency response of a circuit more easily. (Also, it may help you on the exam!) Laplace and Fourier transform will be skipped in this course (because you will learn them in ELECT ENG MATH I.) The two-port networks will be taught in CIR THEORY II/LAB. The op-amp will be taught in ETRON CIRCUIT/LAB (2nd semester of the 3rd year.)

P.S. This course has lab exams. I recommend that you go and practice when there is an allocated time provided by prof before the lab exam. (Even though this is not the obligation, it will help you.)

---

### ENG MECHANICS I

The only subject from Mechanical Engineering. Both **Engineering Mechanics by R. Hibbeler** or by **J.L. Meriam & L.G. Kraige** will do your favor. Do homework by yourself since one of the problems will be appear on the exam. End of the review. Good luck.

---

### CALCULUS III

This is an essence. Do not believe someone who say this course is useless. Electromagnetics requires this course. If you want to learn something like optimization techniques, understanding from this course is a must.

I recommend that you do exercises provided by prof by yourself, just like what you have done in CALCULUS I and CALCULUS II. The exam will be as hard as that. Prof’s handouts are enough. But if not, any international calculus textbooks will do you favors. I personally recommend **Calculus: Early Transcendentals by Howard Anton, Irl Bivens, and Stephen Davis**. Read the entire book, trust me, you are going to use all of those topics in many subsequent courses.

---

## Year 2 Semester 2

![Philadelphia, PA, United States](philadelphia.jpg)
*Philadelphia, PA, United States (Photo by Trev Adams)*

### ELECT ENG MATH II

This is my only course that I got a B+, so far.

I, personally, find that **[Ajarn Jitkomut](http://jitkomut.eng.chula.ac.th/)’s slides on Linear Algebra**, and **[Ajarn Suchin](https://ee.eng.chula.ac.th/suchin-arunsawatwong/)’s slides on Complex Analysis** should be enough for you to get through this course. However, if you want to rely on textbooks, my recommendations are these textbooks:

**Linear Algebra and Its Applications by David Lay, Steven Lay and Judi McDonald**: The first five chapters in the book (5th edition) will be all taught before the midterm. Chapter 6 (orthogonality, least square, Gram-Schmitt) and Chapter 7 (Symmetric matrices and Quadratic form) will not be taught. However, I recommend that you read those anyway since they are going to reappear in many subsequent courses (PRINC COMM, LIN CONT SYS II, RANDOM PROC EE, etc.)

I want to emphasize that Linear Algebra is very important in every field of engineering. You should take this course very seriously.

**Complex Variables and Applications by Brown and Churchill**: The holy grail of the complex analysis in my opinion. The first seven chapters in the book (9th edition) will be taught after the midterm. I found these topics have no direct application in electrical engineering yet, but it will help explaining many topics that found in control systems (e.g., Nyquist stability criterions.) If you don’t want to blindly accept those topics, learn the materials. The bonuses of this course are

- You will finally know how to evaluate some improper integrals which can be solved much easier by the residue theorem.
- You will finally know how to evaluate inverse Laplace transform without finding partial fraction of a function (but you will not do it that way anyway.)

---

### CIR THEORY II

In my opinion, this course material is not updated at all. The book of which professors are still using is **Network Analysis and Synthesis by Franklin F. Kuo**. Seriously, this book is published in *1966*, the year my father was born. I would not recommend this book to any new EE students since the way this book handles electrical circuits is obviously outdated. Anyway, I do recommend, still, for those who want to understand how circuits are analysed before the time when computers are very rampant. Nowadays, it is more common to use state-space to analyse any linear models (e.g., linear circuits.) In the book mentioned, the author used full matrix representation to analyse the voltages of all nodes, or the currents of all paths to analyse the circuit. Obviously, this is very computationally-heavy! The practices for the problems which are going to be on the exam are also virtually none since this technique is already outdated. However, there are problems from [Ajarn Manop](https://ee.eng.chula.ac.th/manop-wongsaisuwan/) which can be done by hands and can be checked by Simscape Electrical. I also had done it almost entirely and they should be in the EE resources’ Google Drive.

Before the midterm, you will learn the topic mentioned above. After the midterm, more modern techniques such as state-space model and two-port networks will be taught. You can go back to use **Fundamentals of Electric Circuits by Charles K. Alexander, Matthew N.O. Sadiku** to follow those topics again. I want to emphasize that this course is very connected to Linear Algebra in ELECT ENG MATH II. I also want to emphasize that this course will make you more appreciate LIN CONT SYS I, since the way of analyzing electrical circuits will be directly applied to general linear models (mechanical, thermal, etc.) in that course.

---

### ENG EMAG

Follow **[Ajarn Supatana](https://ee.eng.chula.ac.th/supatana-auethavekiat/)’s lecture notes and her former exams** and you will be fine. End of the review. (Sorry, just kidding.)

This course is very important for those who want to study in the field of communication. (Telecommunication, Microwave, Optics, Antennas, etc.)

My book recommendations are:

**Introduction to Electrodynamics by David J. Griffiths**: Honestly, this is the holy grail. You may think that you already understand electromagnetics from your first-year courses; *no*, you’re not, until you read this book.

First 9 chapters in the book (4th edition) will be taught in the course. If you cannot self-study from this book, please attend the class and use this book as a reference. Ajarn Supatana has so many techniques to approach EM problems, that they will not be found on textbooks. However, the book will strengthen your understanding in electromagnetics in a very significant way. I still recommend that you read this book!

**Field and Wave Electromagnetics by Cheng**: This book is actually a book used by the course’s professors. I do not read the book myself, by my friend [Taran](https://www.facebook.com/nineza.taran) recommends this book so often that I decide it should be on the recommended list. This book is very connected to the future courses in communication (transmission line, waveguide, antenna.) So, I do recommend that if you don’t want the feeling of too much physics-oriented explaining in the previous mentioned book, this book is more EE-oriented and recommended to those who want to pursue further in communication.

**Electromagnetism: Problems with Solutions by Pramanik**: How the authors can compile these many problems in EM is astonishing. I recommend that if you really have time and get bored of former exams, go for this book.

---

### ELEC MACH I

This is the first course that is, in my opinion, practical-oriented.

**Electric Machinery Fundamentals by Chapman** is the book used by professor, and I recommend you to read the entire book, since every topic is relevant to electrical machinery in these days. I also recommend that, for those who find this book not theoretical enough, you go for **Fitzgerald & Kingsley's Electric Machinery by Umans**. I personally had no time to read the latter book, though.

---

## Year 3 Semester 1

![Saint Petersburg, Russia](saint-petersburg.jpg)
*Saint Petersburg, Russia (Photo by Serj Sakharovskiy)*

### ELEC POWER SYS I

To be honest, this is the course that I did not give my attention that much. (How I can get an A from this course is still astonishing to me!?) 

The prof's slides, materials and former exams should be enough for the course. If you are energetic for this course, please refer to **Power System Analysis and Design by J. Duncan Glover**. I heard that this book can be used further in ELEC POWER SYS II as well.

### SEMICON DEV I

This is where many EE students find themselve whether they really want to pursue further in electronics or not.

This course is taught entirely by [Ajarn Songpol](https://ee.eng.chula.ac.th/songphol-kanjanachuchai/) in my year, and he's very good at it. You will learn all of the essential topics related to semiconductor. *Essential* is not an exaggerated word: these topics will be useful when you take ETRON CIRCUIT/LAB next semester. 

The textbook that Ajarn Songpol uses for many years is **Solid State Electronic Devices by Ben Streetman**. I find that book good if you want to learn fast. If you want to learn these topics in a more physics-oriented way, I recommend you to read **Semiconductor Physics and Devices by Donald A. Neamen** for more in-depth understanding. (Again, if you have time.)

### PRINC COMM/LAB

This course give you many basic topics about communication in general. Some say it is useful, and some say it cannot provide any pictorial understanding about communication at all. I am in the former group; I find it useful enough for me who don't want to study further in communication field.

The textbook that I relied on, parallelly with the prof's slides and materials, is **Modern Digital and Analog Communication Systems by B. P. Lathi**. I found it readable for any beginner. [Ajarn Nisachon](https://ee.eng.chula.ac.th/nisachon-tangsangiumvisai/) says that the course relies on **Digital and Analog Communication Systems by Leon Couch**, but I found it very hard to read for the beginners. Some people recommend the book **Communication Systems by Michael Moher and Simon Haykin**, but I haven't read that book yet.

### FUND DIGIT CIRC

{: .note } 
I want to say this for a long time: You don't have to love SEMICON DEV I and ETRON CIRCUIT/LAB to decide whether you want to pursue further in electronics or not. Field of electronics is huge that you don't have to be good at everything.

{: .warning } 
I heard that for subsequent years, profs would want you to use Xilinx Vivado software suite. You should have your own computer with AT LEAST 200 GB OF FREE SPACE to install that. If not, you need to have some generous friends whom you can rely their computers.

This course is the first course in electronics (along with SEMICON DEV I.) This is the first step in digital design.

All of the basics will be taught in this course. The pair of books which I used simultaneously are:

**Digital Fundamentals by Thomas L. Floyd**: This book is made for beginner that I find it very easy to read. Furthermore, it includes topics in common digital ICs used in discrete electronics (74 series.) It also includes many common electronics knowledges that I personnally find those very helpful. All in all, I recommend that anyone who wants to go further in digital electronics to read this book entirely. Nevertheless, this book does not cover all of the topics in FUND DIGIT CIRC. (It lacks the topic about state machine.) The next book that covers all topics in this subject is

**Fundamentals of Logic Design by Charles H. Roth**: This book is very in-depth. In the book (7th edition,) Unit 1 through Unit 13 will be thought in this course (seriously.) Some topics will be skipped (e.g. Quine-McCluskey method, hazards in digital circuits, etc.) The rest of the topics are also very interesting if you want to work in digital design in the future. Follow this book along with the course will give you the best understanding.

This course uses VHDL for synthesizing digital logics (even though Verilog is more popular.) For VHDL, The book from Charles H. Roth mentioned above have some units dedicated to VHDL, but I found them not enough for me. I personnally find **Free Range VHDL by Bryan Mealy and Fabrizio Tappero** to be very helpful for beginner who wants to start fast. (This book is FREE, you can search it for yourself in Google.) Anyway, this book does not include the topic on testbench (and many advanced topics about VHDL.) For more in-depth topics, you should follow **The Designer’s Guide to VHDL by Peter J. Ashenden**.

For anyone interest in Verilog, I recommend **Quick Start Guide To Verilog by Brock J. LaMeres**.

### LIN CONT SYS I/LAB

The first course in control system theory. Since I'm in the field of electronics, this course is very important (trust me.)

I personally found that [Ajarn Manop](https://ee.eng.chula.ac.th/manop-wongsaisuwan/)'s slide for this course is very easy to read, but not enough for in-depth understanding. You should rely on additional examples and explanation in textbooks to achieve real understanding in this course. (If you want to.) The recommended books are:

**Modern Control Engineering by Katsuhiko Ogata**: This is the book that is recommended by [Ajarn Suchin](https://ee.eng.chula.ac.th/suchin-arunsawatwong/), and I will also recommend this book to you. This book is very easy to read, and my friend [Taran](https://www.facebook.com/nineza.taran) also agree with me. Chapter 1 through Chapter 7 in the book (5th edition) will be taught in this course. (You can safely skip Chapter 4.) Chapter 8, the PID, can be read for further understanding. Chapter 9 and 10 will be covered in LIN CONT SYS II.

For other books, there are **Modern Control Systems by Richard C. Dorf**, but I find it hard to read for beginners, and **Control Systems Engineering by Norman S. Nise**, but I have not read it yet.

{: .note } 
For those who find this course very hard: I personally read all of the topics in this course FOR 3 TIMES to make an A out of it.

---

## Year 3 Semester 2

![Jiufen, Taiwan](jiufen-taiwan.jpg)
*Jiufen, Taiwan (Photo by We Fun Taiwan)*

{: .note } 
This is where the fun begin.

### PROP ELEC ENG MAT

I personally hate this course, lol. (Don't mind me.)

You can rely on prof's slides entirely and you should be fine. The textbook used by prof is **Principles of Electronic Materials and Devices by S. O. Kasap**, but I have no time to read that book. Good luck.

### ELEC MEAS/INSTRU

This course teaches you about the basics on electrical instrumentations and measurements. I personally find this course useful. The course has no companion textbook. Some of the topics are out-of-date in my opinion. Relying on prof's slides only and you should be fine. End of the review.

### ETRON CIRCUIT/LAB

I personally not recommand you to rely prof's slides to fully understand this course! [They will never be enough!](https://www.youtube.com/watch?v=6jZVsr7q-tE)

Finally, one of the courses that I found the instructors not so very helpful (only [Ajarn Boonchuay](https://ee.eng.chula.ac.th/boonchuay-supmonchai/) and [Ajarn Napong](https://ee.eng.chula.ac.th/napong-panitantum/) are good, the other are :unamused:.) If you want to pursue further in analog design, PLEASE use the textbooks. THIS COURSE IS HARD AS IT SUPPOSED TO BE! I recommend that for someone who go for analog or microelectronics in general, please refer to:

**Microelectronic Circuits - Sedra & Smith**: This book is the best in my opinion. Only warning is that the arrangement of the topics in this book is not the same as in the course, so that you need to learn fast enough if you want to rely on this book along with the course. I recommend this book first because I love how this book arranges its content.

If you want to use this book (7th edition) along with the course, this is my advice:
- Firstly, you should review the basic about semiconductor from Chapter 3.
- Then, you need to learn about device physics (BJT and MOS) from Chapter 5 and 6.
- The BJT amplifier will be taught first, you read it from Chapter 7. I recommend that you should understand how the resistance-reflection rule works.
- Also, you need to learn more about the frequency response of a BJT amplifier. You read that from Chapter 10 for those relevant topics. The prof is generous if you are lucky, so only the frequency response of the common-emitter configuration will be asked in the exam.
- Secondly, the MOS amplifier will be taught. You go back to Chapter 7 again. MOS is easier than BJT since there is no gate (base) current.
- Some of the MOS amp configurations will be new for you (e.g. cascoding, current mirror, etc.) You should read Chapter 8.
- Also, you need to learn more about the frequency response of a MOS amplifier, so you go back to Chapter 10 to read about that. If the prof is generous, again, only the frequency response of the common-source configuration will be asked in the exam.
- For the op amp, you read from Chapter 2. This is the most easy topic that you will learn from this course.
- For the basic of current mirror, differential amp, analog filter and some oscillator, you read those from Chapter 8, 9, 17 and 18. The oscillator circuit is analysed more easily if you know things from feedback in Chapter 11.

Chapter 11 and 13 will be taught further in PRIN ANALOG CIR. Chapter 14 to 16 is very helpful if you want to study DIG IC in the future.

If you want to read the textbook that arrange its content in the same way as of the course, you can refer to **Microelectronics Circuit Analysis and Design by Donald A. Neamen**. I cannot comment on that book since I have not read it yet. (I just skim on it.) Other recommended textbooks are **Fundamentals of Microelectronics by Behzad Razavi** and **Microelectronic Circuit Design by Richard C. Jaeger**, those I haven't read yet, too.

{: .note } 
The terminology used in this course is not the same as in any standard textbook. It is also not mentioned by the prof AT ALL. (Why? :expressionless:) So, I note it here: 
- A(vin) = voltage gain with no load and no source resistance
- A(vn) = voltage gain with no load but with source resistance
- A(vi) = voltage gain with load but no source resistance
- A(v) = voltage gain with load and source resistance

### LIN CONT SYS II (compulsory elective; control system theory)

### INTRO EMBED SYS (compulsory elective; electronics)

### AI ENG (free elective; a course from computer engineering)

---

## Year 4 Semester 1

### RANDOM PROC EE (compulsory elective; control system theory)

### MMEDIA COMPR TECH (elective; communication)

### DIG CONT SYS (compulsory elective; control system theory)

### PRIN ANALOG CIR (compulsory elective; electronics)

### INTRO OPT TECH (elective; control system theory)

### DIG IC (elective; electronics)
