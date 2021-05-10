# The Simplest Django REST Framework Example

[![Python Tests](https://github.com/cyface/simplest-django-rest-framework-example/actions/workflows/run_tests.yml/badge.svg)](https://github.com/cyface/simplest-django-rest-framework-example/actions/workflows/run_tests.yml)

This repository is a companion to ["The Simplest Django REST Framework Example"](https://timlwhite.medium.com/the-simplest-django-rest-framework-example-c67cecc88400) article.

This project is an example of how to implement Django REST Framework in the simplest way, using generic class-based views and routers.
## How to get this running

* `pip install -r requirements.txt`
* `python manage.py migrate`
* `python manage.py loaddata games/fixtures/initial_data.json`
* `python manage.py runserver`

Browse to: http://localhost:8000/
