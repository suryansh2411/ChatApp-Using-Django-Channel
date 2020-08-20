ChatApp
=========

Installation
------------
Run the app::

    docker-compose up -d

The app will now be running on: {your-docker-ip}:8000
Now, run::

    docker-compose run --rm web python manage.py migrate


Usage
-----

Make yourself a superuser account::

    python manage.py createsuperuser

Then, log into http://localhost:8000/admin/ and make a couple of Room objects.
