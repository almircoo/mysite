## Django Login and Register Customized

Setup project environment

### Requiments

- ✨ [Mailgun API](https://www.mailgun.com) Credentials ✨
- ✨ [Python 3.11](https://www.python.org) ✨
- ✨ [Django 4.1](https://docs.djangoproject.com/) ✨
- ✨ [Postgresql@15](https://www.postgresql.org) ✨

### Getting Started
```bash
# Create virtual environment - MacOS
$ python -m venv myvenv 
$ source myvenv/bin/activate
```
```bash
# Create virtual environment - Windows
...\> py -m venv env-name 
...\> .\env_name\scripts\activate
```
```bash
# Clone the project HTTPS
$ git clone https://github.com/almirco/app.git
# Clone the project SSH
$ git clone git@github.com:almircoo/app.git
# Clone the project GitHub-CLI
$ gh repo clone JesusAlmirco/mysite
```
```bash
$ cd mysite
$ pip install -r requirements.txt
$ python manage.py migrate
$ python manage.py runserver
```