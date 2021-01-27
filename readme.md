<!-- ABOUT THE PROJECT -->
## Todo App with Django and React

A list of commonly used resources that I find helpful are listed in the acknowledgements.

### Built With

This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [Django]
* [DRF]
* [Sqlite]
* [Reactjs]

1. mkdir django-todo-react
2. cd django-todo-react
3. pip install pipenv
4. pipenv shell
5. pipenv install django
6. pipenv shell
7. pipenv install django
8. django-admin startproject backend
9. cd backend
10. python manage.py startapp todo
11. python manage.py migrate
12. python manage.py runserver


## After defining the model

13. python manage.py makemigrations todo
14. python manage.py migrate todo


## add model definitions to admin.py to make use of crud operations using "from django.contrib  import admin"

15. python manage.py createsuperuser

## Setting up the APIs

16. pipenv install djangorestframework django-cors-headers
17. We need to add rest_framework, corsheaders and corsheaders.middleware.CorsMiddleware to the list of installed applications, so open the backend/settings.py file and update the INSTALLED_APPS and MIDDLEWARE sections accordingly:


## Front End

18. npm install -g create-react-app