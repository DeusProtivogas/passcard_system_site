# Bank security console

Service to monitor the bank's vault entrances and entrance timings.


### Environment variables
- Database information
  - DB_ENGINE
  - DB_HOST
  - DB_PORT
  - DB_NAME
  - DB_USER
  - DB_PASSWORD
- SECRET_KEY

1. Put `.env` file near `manage.py`.
2. `.env` contains text data without quotes.


### How to install


Python3 should be already installed. 
Then use `pip` (or `pip3`, if there is a conflict with Python2) to install dependencies:
```
pip install -r requirements.txt
```

### How to run

Standard command to launch a Django application with manage.py, for example:
```
python manage.py runserver 0.0.0.0:8000
```

### Project Goals

The code is written for educational purposes on online-course for web-developers [dvmn.org](https://dvmn.org/).