# google-oauth2-calender
I find various tutorials talking about django social oauth but I want the full connectivity from google login button to viewing google calender events.

## Prerequisite
- Firtly visit the https://console.developers.google.com
- create new project and then setup 
- You will get the credentials pass those credentials in your environment variables as mentioned below.


### Environment variable setup
- SOCIAL_AUTH_GOOGLE_OAUTH2_KEY
- SOCIAL_AUTH_GOOGLE_OAUTH2_SECRET

## Enabling APIs
- When your are trying to access any of the google apis then you need to enable that api
- visit the https://console.developers.google.com
- On **Dashboard** click button **Enable APIS and SERVICES** 
- Select those apis that you want to explore, in my case its google calender

## Django setup
- python manage.py makemigrations
- python manage.py migrate
- python manage.py runserver

# Features
- Profile migration from social sites to django db 
- Profile Photo social sites to django db
- Login/ Logout functionality 
- Django login logout alongwith social login
- Login Based upon username/email
- Password Reset/ Password Confirmation /Email confirmation
- Update Profile details
- Google Calender events of logged in user through social sites

## TODO
- For extending the features you can add more apis and services available at gooogle apis portal
- Handling the meeting invite automatically
- Hangout chat automatic replies
