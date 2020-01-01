# Poll-Applications
Basic poll applications from the django tutorial

git clone https://github.com/fedorkovolodymyr/Poll-Applications.git
cd Poll-Applications/
python3 -m venv env
python3 -m pip install Django
django-admin startproject mysite
python3 mysite/manage.py runserver
cd mysite/
python3 manage.py startapp polls
