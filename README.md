# LAB - Class 29

## Project: django-custom-user

### Author: Negin Koushkakinejad

Links and Resources:

Django: https://www.djangoproject.com/


Setup:

Initialize virtual environment - python3 -m venv .venv

Activate virtual environment - source .venv/bin/activate

Install Django - pip install django

To creat new Django project - django-admin startproject `myprojectname`

To create a new Django app where we'll define our custom user model - python manage.py startapp `app name`

To create and apply migrations - python manage.py makemigrations `app name`
python manage.py migrate

To run the server - python manage.py runserver

Tests

Run tests - python manage.py test