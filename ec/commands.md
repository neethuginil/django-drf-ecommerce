# packages

Django==5.0.7
djangorestframework==3.15.2
python-dotenv==1.0.1
pytest==8.3.2




# commands

django-admin startproject ecommerce .

python3 manage.py runserver

from django.core.management.utlis import get_random_secret_key

print(get_random_secret_key())

pip freeze > requirements.txt

pip insall --upgrade pip

pip install python-dotenv

pip install pytest-django

# pytest 

pytest -h # prints options _and_ config file settings
