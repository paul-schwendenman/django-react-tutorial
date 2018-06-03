Django REST with React Tutorial
===================================

This project is my work through of this tutorial:
https://www.valentinog.com/blog/tutorial-api-django-rest-react/

To use project::

    pipenv install
    pipenv shell

Migrate the DB::

    python manage.py migrate

Code coverage
--------------

::

    coverage run --source='.' manage.py test


Generate HTML report::

    coverage html
    open htmlcov/index.html

Commandline report::

    coverage report

Seeding DB
-----------

Installing fixtures::

    python manage.py loaddata leads
