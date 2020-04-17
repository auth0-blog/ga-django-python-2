# ga-django-python-2

This repository contains the source code for Part 2 of Introduction to Django 3.0 - Building, Authenticating, and Deploying. Read more at: (Add Link here).

Link to Part: (Add Link here).

In this article, we'll be learning to add the authentication model to our Django app using Auth0. Next, we'll be deploying this application into production using Heroku and handle URLs and Databases.

## Requirements

1. Python3 and Git installed on your machine
2. Postgress Database
3. Auth0 Account
4. Heroku Account

## To run this:

1. Clone the repository: `git clone https://github.com/auth0-blog/ga-django-python.git`
2. Install all the packages using pip: `pip install -r "requirements.txt"`
3. Create Postgress DB with the name: `codeshare`
4. Create an Auth0 App; you can sign up here: https://auth0.com/
5. Create a `.env` file and add the API keys for authentication from Auth0 Dashboard
6. Run `python3 manage.py migrate` to make migrations locally
7. Run `python3 manage.py runserver` to start the server locally
8. Your browser should open automatically and show the application UI. If it doesn't start automatically, please open it manually and point it to http://localhost:8000
9. Create a Heroku App and add the remote (from your dashboard) and push using Git.
10. Run `heroku run python3 manage.py migrate` to make migrations in production
11. Run `heroku run python3 manage.py createsuperuser` to create superuser in production
