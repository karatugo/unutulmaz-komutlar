```
pipenv install gunicorn
touch Procfile
```

Procfile dosyasına `web: gunicorn app:app` yaz.

```
heroku login
heroku create <appname>
git push heroku master
```
