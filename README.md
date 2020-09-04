## TECH STACK USED
Django Stack: Django, python and SQLite3 as Database

# INSTALLATION
Install python for respective OS: Click here

Install pip for respective OS: Click here

Install Django for respective OS: Click here

# DO CHANGES IN CODE
Navigate to project folder where settings.py present and do following changes in code (present at the end of settings.py file)

Enter your email and password of gmail account from which mail has to be send
```
EMAIL_HOST_USER = 'your_email@gmail.com'
EMAIL_HOST_PASSWORD = 'your_password'
```

Note :

a.) Allow EMAIL_HOST_USER to allow less secure apps to send mail(gmail account), since this website is on localhost now. You won't have to allow less secure apps to access EMAIL_HOST_USER once we have SSL certificate enabled for this website.

b.) Since we're running website on local server therefore we haven't enabled SSL certificate for this website yet.

Reciever's email(gmail accounts) list we've set in the code itself. We can make an interface to enter reciever's email. We'll implement in future as per the requirements and suggestions.

## STARTING LOCAL DEVELOPMENT SERVER
Open command prompt

Navigate to project folder where manage.py present

Run following command

 python manage.py runserver  

## RUN THE WEBSITE AS FOLLOWS
Open a browser.

Search for: 127.0.0.1:8000/enterphone

You now have website running on your browser
