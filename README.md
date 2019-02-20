# Tutramite

# How to execute the project

First, active the virtual environment, then, install dependencies of the file requirements.txt using the following command:

- pip install -r requirements.txt

second, create migrations:

- python manage.py makemigrations entity
- python manage.py makemigrations civil_servant
- python manage.py makemigrations formality
- python manage.py makemigrations attachment

and run

- python manage.py migrate --run-syncdb

To create an user execute te comand bellow and follow the instructions
- python manage.py createsuperuser


Finally execute
- python manage.py runserver
