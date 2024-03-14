# ImagePost_python_django
### These are my first steps in python and django
#### The app itself is a simple python + django app for uploading images and text, with a smaller thumbnail and a larger detailview. Images are simply stored in a media folder, this will of course be developed later. The frontend is still rudimentary, with minor bootstrap elements.

## Installation
To install, you need an older version of django and sorl-thumbnail \
Django==3.1.4 \
sorl-thumbnail==12.7.0 \
This may require pipenv or another virtual env

## And the following commands:
```
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver 0.0.0.0:8000
```
### In this case, localhost://8000 will run the server and you can manage the data on the /admin page with the specified superuser.
