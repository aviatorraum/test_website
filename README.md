###This is a test website includes user management.

##To get started:
``` bash
    git clone ... website
    pip install -r requirements.txt
    cd website
    python manage.py makemigrations
    python manage.py migrate
    python manage.py runserver
```
##Includes:
``` bash
pip install django-users2
```
##Added database parameters:
    User: first name, last_name, team
    Team: name, members

##Features:
-   Login
``` bash
parameters: email, password
```
 -  Register:
``` bash 
parameters: first name, last name, email, password, retype password
```
-   Password reset
``` bash 
parameters: email
```
-   Change user details
``` bash 
parameters: first name, last name, email, password, team
```
  
##DEMO
https://limitless-inlet-90838.herokuapp.com/accounts/

### TODO::added form to handle user details change
