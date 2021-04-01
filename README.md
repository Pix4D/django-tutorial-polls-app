# Django Tutorial Polls App

This repository contains the complete code for the [Django](https://www.djangoproject.com/) project's [tutorial](https://docs.djangoproject.com/en/3.1/intro/tutorial01/) `polls` app. The code should mirror the code you've written at the end of [Part 7](https://docs.djangoproject.com/en/3.1/intro/tutorial07/).

The `SECRET_KEY` variable in `mysite/settings.py` must be provided as an environment variable.

----

## Quickstart

Polls is a simple Django app to conduct Web-based polls. For each question, visitors can choose between a fixed number of answers.

1. Create your virtual environment using pipenv `pipenv sync` to load all the packages.

2. Run `python manage.py migrate` to create the polls models in the database.

3. Run `python manage.py createsuperuser` to create an admin user that is able to log in the admin panel.

4. Start the development server `python manage.py runserver` and visit [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)
   to create a poll.

5. Visit [http://127.0.0.1:8000/polls/](http://127.0.0.1:8000/polls/) to participate in the poll.
