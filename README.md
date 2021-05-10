# Django REST Framework Examples
Django REST Framework Examples

This repository is a companion to [my "The Simplest Django REST Framework Example" article](https://timlwhite.medium.com/the-simplest-django-rest-framework-example-c67cecc88400).

This project is an example of how to implement Django REST Framework in the simplest way, using generic class-based views and routers.
## How to get this running

* `pip install -r requirements.txt`
* `python manage.py migrate`
* `python manage.py loaddata games/fixtures/initial_data.json`
* `python manage.py runserver`

Browse to: http://localhost:8000/
