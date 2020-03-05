```
python3 -m pipenv shell
pipenv install django==2.2 djangorestframework
django-admin startproject fuzzyfiesta
cd fuzzyfiesta/
python manage.py migrate
python manage.py createsuperuser
python manage.py startapp languages
```

Add leads and rest_framework to INSTALLED_APPS.
Create `languages/urls.py`.
