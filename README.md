# verify-sms-email

Combining simple sendgrid and verify components to a demo application

Sequence is as follows:
1. User hits the index page
2. User must enter email address, then sent to a new page to input a code
3. Only a user that is authorized will be sent an sms code
4. User recieves the sms code and enters it into the form field
5. If users code is successful then the user is redirected to the email page
6. User will send a test email 

Demo Applicatino is built on Python and Flask

Required packages include:
os
twilio.rest Client
flask
dotenv
flask mail


