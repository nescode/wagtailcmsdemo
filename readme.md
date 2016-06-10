# Wagtail CMS Demo

This is a demonstration project for Wagtail CMS features. You can use this project as a starting point. This project provide features demonstration of Wagtail CMS.

## Who using it?

[Nescode](https://nescode.com/)

## Wagtail CMS & Django Framework Version

```
wagtail==1.5.2
Django==1.9.7
```

## For developers, From developers

Demonstration of Wagtail features in this repositories is for developers only who know how to setup
virtual environment and Django project. In case you would like know how to setup virtualenv, browse through [Configure virtualenv and virtualenvwrapper](http://www.sunilsrikumar.com/2016/03/django-multi-site-setup/)

## Dependencies

There is no dependencies as such. You can setup Wagtail CMS using virtual environment or Vagrant. Choice is yours.

## Installation

Run the following commands:
```
git clone https://github.com/nescode/wagtailcmsdemo.git
cd wagtailcmsdemo
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
The beautiful Wagtail CMS will be now accessible at http://127.0.0.1:8000/ and the Wagtail admin interface
at http://127.0.0.1:8000/admin/ . To login into admin panel create a superuser:

```
python manage.py createsuperuser
```
Give your username, email id and password to complete the user creation process.

## Features List

Available features details are as follow:
* Dynamic homepage and standard page model to manage multiple block through admin panel.
* One, Two and Three column content
* Carousel image slider
* Blog
* Event management
* Person/team page
* Contact page
* Dynamic form through admin
* Standard page with StreamFieldPanel for multiple content type.
* Indexing
* Search across site
* Document management
* Registration/SignIn using registration redux module.
* Multi-user
* Group
* Multi-site
* Customized permission management for content management
* Google SEO Optimization for - Page title, slug, page description
* Schedule publishing of content Go live & Expiry
* Bootstrap front end framework
* Crispy form

We are adding generic usable features frequently. Keep watching this list for any update.

## This repositories as a starting point for your project

Since, secret key is public in this repositories, we recommend developer to create your own secret key in case you want to use this repositories as a starting point for your next beautiful Wagtail project.
Follow this steps to create a new secret key:

Step 1: Login into python prompt
```
$ python
```
Step2: Import necessary package and generate secret key
```
import os
os.urandom(24).encode('hex')
```
This will generate a secret key in hex code.
Now you can replace with existing secret key in settings/dev.py

## Paid development

We love Wagtail because of its flexibility and clean code. We offer paid development of [Wagtail CMS](https://wagtail.io/). Just say hello at info@nescode.com to start a discussion.

## Django development company

We are passionate technologists. We offer full stack development and consulting for organizations
with Python, Django framework, Wagtail and PostgreSQL. Drop us a line at info@nescode.com to shape your idea.
