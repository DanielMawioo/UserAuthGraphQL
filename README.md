# Django and GraphQl all auth users-mgt backend-app

## Description

The  App uses django backend and GraphQL to create the rest endpoints for user accounts management

- Query any Quizzes available in the database using a single endpoint

Created on, April 8th 2021

## Technologies used

- Django
- Django_graphene ##GraphQl
- Django_graphene_jwt
- Django_graphene_allauth
- Git

## Development and Setup.

### prerequisites

- Python 3.8+ should be installed
- django 3.0 +
- install django graphene && graphene-jwt && graphene-allauth

### Installation.

- Ensure python3.8+ is installed.
- Clone the repository git clone <repo url>
- create a virtual environment virtualenv <envname> and activate source <envname>/bin/activate
- Install the required packages pip3 install -r requirements.txt
- set up your database.
- Once the database is set up, make migrations. This creates database schemas for the application python manage.py -makemigrations
- Then create the actual database tables by python manage.py migrate
- Start the application by python manage.py runserver and open http://127.0.0.1:8000 in the browser.

## Test Driven Development

Testing was done using python inbuild test tool called unittest to test database and form models.

## Functionalities
- 1. Login
- 2. Logout
- 3. Authentication
- 4. Signup with emai confirmation
- 5. Change password
- 6. Forgotten password via email confirmation
- 7. Delete account
- 8. Update account details

## Further help

To get Further help you can visit the official python ,django, django_graphene, django-graphene-allauth documentation.

## Licence

MIT (c) 2021 Daniel Mawioo
