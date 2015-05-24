django-skel
===========
A Django (1.8) project skeleton.

Install
=======

django-skel currently supports Django 1.8. To create a new django-skel base
project, run the following command (this assumes you have Django 1.8 installed
already):

    $ django-admin.py startproject --template=https://github.com/hipwerk/django-skel/zipball/master woot


Where ``woot`` is the name of the project you'd like to create.

This is possible because Django 1.6's ``startproject`` command allows
you to fetch a project template over HTTP (which is what we're doing
here).
