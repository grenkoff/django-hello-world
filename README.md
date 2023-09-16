# django-hello-world

My first Django project

Commands I used from this project:
* `mkdir django-hello-world`
* `cd django-hello-world`
* `python3 -m venv django-hello-world`
* `source django-hello-world/bin/activate`
* `pip install django`
* `django-admin startproject helloworld`
* `cd helloworld`
* `./manage.py runserver`
* `./manage.py migrate`
* `./manage.py startapp helloapp`
* Add our application `helloapp` to the variable `INSTALLED_APPS` in the file `settings.py`
* Create folder `templates` inside our project `mkdir templates`
* Inside the folder `templates` create the file `index.html`: `cd templates` `touch index.html`
* Register the folder `templates` in variable `TEMPLATES` using the key `DIRS` in the file `settings.py`
* Write view-function in file `views.py`
* Link our view-function and URL in file `urls.py`
* `./manage.py runserver`