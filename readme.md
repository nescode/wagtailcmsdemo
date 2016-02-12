### Wagtail CMS Demo

This is a demonstration project for Wagtail CMS features. We do not recommend using
this project to start your own site. This project provide features demonstration
of Wagtail CMS.

###### For developers, From developers

Demonstration of Wagtail features in this repositories is for developers only who know how to setup
virtual environment and setup Django project.

###### Dependencies

There is not dependencies as such. You can setup using virtual environment or Vagrant. Choice is yours.

### Installation

Run the following commands:
'''
git clone https://github.com/nescode/wagtailcmsdemo.git
cd wagtailcmsdemo
pip install -r requirement.txt
python manage.py migrate
python manage.py runserver
'''
The beautiful Wagtail CMS will be now accessible at http://127.0.0.1:8000/ and the Wagtail admin interface
at http://127.0.0.1:8000/admin/ . To login into admin panel create a superuser:

'''
python manage.py createsuperuser
'''
Give your username, email id and password to complete the user creation process.

###### This repositories as a starting point for your project

Since, secret key is public in this repositories, we do not recommend using this repositories
as a starting point. However, you can create your own secret key in case you want to use this
repositories as a starting point for your next beautiful Wagtail project.
Follow this steps to create a new secret key:

'''
Step 1: Login into python prompt
$ python

Step2: Import necessary package and generate secret key
>> import os
>> os.urandom(24).encode('hex')

This will generate a secret key in hex code.
'''

and replace with existing secret key in settings/dev.py

###### Django development company

We are passionate technologists. We offer full stack development and consulting for organizations
with Python, Django framework and PostgreSQL. Drop us a line at info@nescode.com to shape your idea.
