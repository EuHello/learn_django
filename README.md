# Django app
Learn to create with Django framework (Python). 

## Overview
Basic polling app that lets people view polls and vote in polls.
1. Model. DB engine: sqlite3
2. View
3. Template
4. URL dispatcher
5. Tests

## Run Dev Server
`python manage.py runserver`  

## Django shell
`python manage.py shell`  

## Django commands
### Creates DB tables based on settings.py
`python manage.py migrate`  

### Store model changes with makemigrations
`python manage.py makemigrations polls`  

### Returns SQL code
`python manage.py sqlmigrate polls 0001`  
