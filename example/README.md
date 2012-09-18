Django Leaderboard Sample Project
=================================

A sample project to try `django_leaderboard`

Dependencies
------------

Please see `requirements.txt` file for the complete dependancy list. 


Installation
------------

Dependencies are added to the `requirements.txt` file. Usage of virtualenv is highly recommended. Please use the following steps to run this sample django project. Following steps requires using a terminal.

Install virtualenv if it's not installed before

    pip install virtualenv

Use following to set up the project

    virtualenv venv --distribute
    source venv/bin/activate
    pip install -r requirements.txt 

Open `settings.py` file and do the necessary changes (i.e. db settings, youtube keys, etc). Refer to `django-leaderboard` readme file.

Now you can start using django management commands.

    cd youtube_project
    python manage.py syncdb
    python manage.py runserver

Usage
-----

Go to http://localhost:8000/ to use the project. Make sure that you create some users first.
