# LittleLemon - FullStack Project

## How to run?

`$ pipenv shell`

`$ pipenv install`

----------------------------------------------------------------------------
## Install MySQL and create a database and user for the project

`$ brew install mysql`

login to mysql

`$ mysql -u root -p`

`$ create database reservations`

`$ CREATE USER 'admindjango'@'localhost' IDENTIFIED BY 'employee@123!';`

`$ GRANT ALL PRIVILEGES ON reservations.* TO 'admindjango'@'localhost';`

exit mysql

----------------------------------------------------------------------------
## Running the project

`$ python manage.py makemigrations`

`$ python manage.py migrate`

`$ python manage.py runserver`

Navigate your browser to http://127.0.0.1:8000/. Success!

