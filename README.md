Welcome to ACE Project
Aceproject is a simple note taking web application implementing some basic features of Google Keep application.
It is built with Python using the Django Web Framework.
This project has the following  apps:

* Accounts:This app is mainly a set of views that can handle user signups, login, logout and password changes. 
* Profiles: This app contains the user profile model, containing all the user details apart from authentication data.� 
* Notes: This app lets a user store private notes online.

Salient Features of  Notes app:
1. See all of our existing notes.
2. Add a new note
3. Edit and delete existing notes
4. See all of our existing tags
5. Create new tags
6. Edit and delete existing tags
7. Some basic search capability - find notes with a given tag,.
Proposed  Features of Notes app(in development):
1. More innovative design  and responsive UI.
2. Local storing  of notes.
3. Ability to store photos.
4. Ability to change background covers.
5. Many more to come.


## Installation

### Quick start
[imp]I have developed this project on linux environment.So,these instructions and this web applications is compatible on any linux systems.
But in windows it does not works at all and gives errors which are out of scope.I am unable to resolve them.But i am planing to deploy it on server so that it's accessible to all. 
To set up a development environment quickly, first install Python 3(Python 2.7 also supported) It
comes with virtualenv built-in. So create a virtual env by:

 1. `$ python3 -m venv aceproject`
 2. `$ . aceproject/bin/activate`

Install all dependencies:

*On some Linux systems like Ubuntu, Pillow will not install unless you install a C compiler and dependencies:

$ sudo apt-get install libjpeg8-dev zlib1g-dev

 pip install -r requirements.txt

Run migrations:

 python manage.py migrate
 Then:
 python manage.py runserver


Third Party Packages and Library:
1. django-environ - By default, settings has environment specific information. This package helps us define such variables in the environment which is more secure.
2. django-authtools - Custom user model and class based auth views.
3. django-crispy-forms - Provides the Sign-in and Sign-up forms.
4. django-braces - Essential set of mixins used for the included views
5. django-admin-bootstrapped - Added Bootstrap 3 theme to the admin
6. easy-thumbnails - for profile picture thumbnails.
7. Werkzeug (dev only) - Better Django error page
8. Bootstrap
9. Jquery
Special thumps up to their developers and their community.
Thank you ACE Team for this Project.
