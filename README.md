This is a test website includes user management.

To get started:
    git clone ... website
    pip install -r requirements.txt
    cd website
    python manage.py makemigrations
    python manage.py migrate
    python manage.py runserver

Includes:
pip install django-users2

Added database parameters:
    User: first name, last_name, team
    Team: name, members

Features:
    Login :
        input : email, password
    Register:
        input : first name, last name, email, password, retype password
    Password reset : 
        input : email
    Change user details :
        input : first name, last name, email, password, team
  
 TODO::
    added form to handle user details change
