# lead-manager app commands

1. Install dependencies:

```
python3 -m pipenv shell
pipenv install django==2.2 djangorestframework django-rest-knox
```

2. Start Django project:

```
django-admin startproject leadmanager
cd leadmanager
```

3. Select Python Interpreter as the one in pipenv.

4. Create Django app

```
python manage.py startapp leads
```


5. Add 'leads' and 'rest_framework' to `INSTALLED_APPS`
