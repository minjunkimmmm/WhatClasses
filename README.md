# WhatClasses
Web app to see what classes you have in common with other students!

# Features
> Log classes and see what classes you have with other students in the database
> Working email server to send emails to verify email addresses

# Setup
- In all HTML files, verify_email_server.py and main.py change the url_base and origin (for main.py) to the base of wherever you are hosting the fastapi server
- When you run the program, it will automatically create a database, and if the dump_courses() function is run, it will input the classes in the dump_courses function into the database. The format for adding tuples is (Course Category (Math), Course Name (Algebra II), Teacher Name (Jim Harris), Course ID (ap_spanlang))
- In verify_email_server.py, change the password and sender email and password to your email and password of your email that will be sending verification requests.

# Photos
![image](https://github.com/user-attachments/assets/45247e43-003d-4c59-bd81-b871253f0395)
> Example Login

![image](https://github.com/user-attachments/assets/fe75e130-e3a8-4a7c-998e-5b174c3743c8)
> Class logging example

![image](https://github.com/user-attachments/assets/e65f3ca5-ae61-4726-b01a-83380cc88f96)
> Example OTP email

# Credits
Co-developed with Jake Rothstein
