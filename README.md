### Beginning
- Create a new project: `django-admin startproject blog`
- Create app in project: `python manage.py startapp entries`
- Apply migrations: `python manage.py migrate`

### To create a python virtual environment

- python3 -m venv django_venv
- source django_venv/bin/activate

### To begin running the server

- python manage.py runserver

### After creating models, migrations can be run
- python3 manage.py makemigrations (create migrations for changes)
- python3 manage.py migrate (applies migrations to db)