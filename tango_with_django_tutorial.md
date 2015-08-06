Tango With Django tutorial: http://www.tangowithdjango.com/book17/

Chapter 4: Django Basics
Create Django Project:
1. django-admin.py startproject tango_with_django_project

Project configuration directory (same name as project):
** __init__.py - a blank Python script whose presence indicates to the Python interpreter that the directory is a Python package;
** settings.py - the place to store all of your Django project’s settings;
** urls.py - a Python script to store URL patterns for your project; and
** wsgi.py - a Python script used to help run your development server and deploy your project to a production environment.

manage.py - provides you with a series of commands you can run to maintain your Django project

2. $ python manage.py runserver
Executing this command will instruct Django to initiate its lightweight development server
