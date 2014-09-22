Setup for a django app using Vagrant & Ansible

Inspiration: https://danielgroves.net/notebook/2014/05/development-environments/

Run with:
vagrant up
vagrant ssh
cd /var/www/django-app
source bin/activate
python vagranttest/manage.py runserver 0.0.0.0:8080