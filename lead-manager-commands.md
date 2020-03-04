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

4. Create Django app:

```
python manage.py startapp leads
```


5. Add `leads` and `rest_framework` to `INSTALLED_APPS`.

6. Create `Lead` model & makemigrations & migrate.

7. Create leads/serializers.py and `LeadSerializer` class in it.

8. Create leads/api.py and `LeadViewSet` class in it.

9. Create leads/urls.py and import `router` from `rest_framework`.

10. Install postman. 

11. `python manage.py runserver` and start testing the api with postman. 


