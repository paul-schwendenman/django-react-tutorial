Django REST with React Tutorial
===================================

This project is my work through of this tutorial:
https://www.valentinog.com/blog/tutorial-api-django-rest-react/

To use project::

    pipenv install
    npm install
    pipenv shell

Migrate the DB::

    python manage.py migrate

Run webpack with::

    npm run dev

Running the app::

    python manage.py runserver

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


Running E2E tests
------------------

After starting the app in a separate terminal::

    python manage.py runserver

Start the tests::

    npm run e2e
