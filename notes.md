# setting environment

sudo apt-get install python-virtualenv
virtualenv --python=python3.5 myvenv
source myvenv/bin/activate
pip install --upgrade pip
pip install django~=1.10.0

# create project
django-admin startproject mysite .

# create DB
python manage.py migrate

# starting web server
python manage.py runserver

# Creating an application
python manage.py startapp blog

# Create tables for models in your database
python manage.py makemigrations blog

# Django prepared a migration file for us that we now have to apply to our database
python manage.py migrate blog

# admin create user
python manage.py createsuperuser
admin:carolina3#

# deploy
https://www.pythonanywhere.com/

# tutorial
https://tutorial.djangogirls.org/en/deploy/
