Install pip3 & pipenv
=====================

```bash
sudo apt install python3-pip
pip3 install pipenv
```

Now, they are installed. You are able to run:

```
python3 -m pipenv install
python3 -m pipenv shell
```


Install flask etc.
==================

```bash
pipenv --python 3.6 install flask
pipenv --python 3.6 install django==2.2
```

```
python3 -m pipenv
pipenv install flask flask-sqlalchemy
pipenv install python-dotenv
```
