## Customer Relation Management Tool Web Application

# Steps to run the web app

1. Make sure you have mysql installed on your machine
2. pip3 install pipenv
3. pipenv shell
4. pipenv install django
5. pipenv install mysql-connector-python
6. django-admin startporject dcrm .
7. make changes to the mydb.py and dcrm/settings.py file to have the mysql configuration as per your system
8. python3 manage.py makemigrations
9. python3 manage.py migrate
10. python3 manage.py runserver
