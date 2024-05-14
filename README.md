# community-garden
Simple web application for use by the Berwick Community Garden

## Getting Started with Dev
1. This project has been started and tested using python version 3.12
2. requirements.txt contains the pip requirements
3. The default sqlite database is used, so no other backends need spun up
   1. `python manage.py migrate` to load all db changes into sqlite
4. A superuser for local dev can be created using `python manage.py createsuperuser`
5. To collect the static files for the admin page `python manage.py collectstatic`
6. The development server can be run using `python manage.py runserver`

### Some useful dev URLs
1. http://www.localhost:8000/admin
