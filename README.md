# Learning Django

Note: Ideally, Django project name == GitHub project name

## Run Dev Server
$ python manage.py runserver

## Shell
$ python manage.py shell

## Models
### Create tables with
$ python manage.py migrate

### Update tables with
$ python manage.py makemigrations polls

### View SQL code
$ python manage.py sqlmigrate polls 0001

## Following Django Official tutorial
1. Writing your first Django app, part 1 
   - Creating a project 
   - The development server
   - Creating the Polls app
   - Write your first view
2. Writing your first Django app, part 2
   - Database setup
   - Creating models
   - Activating models
   - Playing with the API
   - Introducing the Django Admin
3. Writing your first Django app, part 3
   - Overview
   - Writing more views
   - Write views that actually do something
   - Raising a 404 error
   - Use the template system
   - Removing hardcoded URLs in templates
   - Namespacing URL names
4. Writing your first Django app, part 4
   - Write a minimal form
   - Use generic views: Less code is better
5. Writing your first Django app, part 5
   - Introducing automated testing
   - Basic testing strategies
   - Writing our first test
   - Test a view
   - When testing, more is better
   - Further testing
   - What’s next?
6. Writing your first Django app, part 6
   - Customize your app’s look and feel
   - Adding a background-image
