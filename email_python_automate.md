---
layout: page
title: Send emails using Python
permalink: /email_python_automate/
nav_order: 10
---

# Send emails to many peoples using Python :email:

Suppose that you are organizing your faculty's job fair, and you have this information to send as a CSV.

![Time Slots](/images/timeslot.png)

Suppose that there're over 100 companies participated. You have to send them relevant information to each company. Doing so manually could be daunting and risky of probable mistake (which can cost your faculty's reputation!) So, send them automatically is more safe.

Fortunately, Python comes for your rescue! But before doing that, you have to set your gmail accordingly ([follow this link](https://support.google.com/a/answer/6260879?hl=en)) for the Python code to have access to that gmail account. (Please turn off that setting when you finish doing things!)

Then, you can use this code template to send emails. Tweak this code for your need.

```python
import smtplib
from email.message import EmailMessage

EMAIL_ADDRESS = 'example@gmail.com' # Your email.
EMAIL_PASSWORD = 'password' # Your email's password.

import mimetypes

from csv import reader

if __name__ == '__main__':

    # open file in read mode
    with open('Job_Fair_Email_Info.csv', 'r', encoding='utf-8') as read_obj:
    # pass the file object to reader() to get the reader object
        csv_reader = reader(read_obj)
        header = next(csv_reader)
        # Iterate over each row in the csv using reader object
        n = 1
        
        for row in csv_reader:
            
            msg = EmailMessage()
            msg['Subject'] = 'Announcing your organization\'s Zoom meeting URL and appointment time for the faculty\'s Job Fair 2022'
            msg['From'] = EMAIL_ADDRESS 
            msg['To'] = row[1].split()
            msg.set_content("""
                
            To the HR of %s
            \n
            Regarding the faculty\'s Job Fair, Your organization\'s time slot is allocated for you as follow:
            %s January 2022, %s, at Zoom meeting room number %s
            \n
            The associated Zoom URL is provided below:
            %s
            Meeting ID: %s
            Password: %s
            Please standby in this online meeting 15 minutes prior to the appointed time. 
            \n
            For emergency case, if we cannot contact you in the Zoom meeting,
            we will contact you back through your phone, using this number: %s
            or your LINE account: %s
            \n
            We also provide you the briefing as the pdf file in this email\'s attachment.
            \n
            We are very appreciated for your participation in our  2022 Job Fair. Thank you very much!
            See you!
            \n
            If you have any question, please contact 083-XXX-XXXX or 086-XXX-XXXX.
                            
            """ % (row[0], row[4], row[5], row[6], row[7], row[8], row[9], row[2], row[3]))
            
            
            with open('Briefing.pdf', 'rb') as content_file:
                content = content_file.read()
                msg.add_attachment(content, maintype='application', subtype='pdf', filename='Briefing.pdf')
                
            with smtplib.SMTP_SSL('smtp.gmail.com', 465) as smtp:
                smtp.login(EMAIL_ADDRESS, EMAIL_PASSWORD) 
                smtp.send_message(msg)
                print("Success", n)
                n += 1
            
```

The CSV and attachment files have to be in the same directory. 

This code had been used in the real Job Fair when I organize it for my faculty in January 2022. At first, I was afriad that automated mails would end up in junk or be marked as spams. It didn't happen, though.

However, I recommend that you try to send this automated mail to your test account first!

[Link to the repository](https://github.com/nutchanonj/Email_Python_Automate).