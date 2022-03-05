# I N S T A C L A N 

An Independent project for Moringa Core Django module, March 3rd, 2022.

## Author  
  
[Venesa Okuna](https://github.com/VenesaOkuna) 

## Description

Instaclan is a clone of [Instagram](https://instagram.com/) 

- Sign in to the application to start using.
- Upload my pictures to the application.
- See my profile with all my pictures.
- Follow other users and see their pictures on my timeline.
- Like a picture and leave a comment on it.

## Features

- authentication system
- search functionality
- Image details
- profile 


## Site Snipets
Here is the Design
<!-- 
<p> Landing</p> -->

<!-- ![Landing](https://raw.github.com/VenesaOkuna/Galleria/master/static/images/landing.png) -->




## View Live Site here
View the complete site [here](mygalleriaapp.herokuapp.com/)


## Technologies Used
    - Python 3.8
    - Django MVC framework
    - HTML and Bootstrap
    - JavaScript
    - Postgressql
    - Heroku

## Specifications
To view the BDD check the [specs file](specs.md).

### Prerequisite
The Instaclan project requires a prerequisite understanding of the following:
- Django Framework
- Python3.8
- Postgres
- Python virtualenv

## Setup and installation

#### Clone the Repo
####  Activate virtual environment
Activate virtual environment using python3.8 as default handler
    `virtualenv -p /usr/bin/python3.8 venv && source venv/bin/activate`
####  Install dependancies
Install dependancies that will create an environment for the app to run `pip3 install -r requirements.txt`
####  Create the Database
    - psql
    - CREATE DATABASE instaclan;
####  .env file
Create .env file and paste paste the following filling where appropriate:

    SECRET_KEY = '<Secret_key>'
    DBNAME = 'instaclan'
    USER = '<Username>'
    PASSWORD = '<password>'
    DEBUG = True

#### Run initial Migration
    python3.8 manage.py makemigrations gallery
    python3.8 manage.py migrate
    
#### Run the app
    python3.8 manage.py runserver
    Open terminal on localhost:8000

## Known bugs
No known bugs so far. If found drop me an email.


## Contributors
    - Venesa Okuna

### Contact Information
vanessaatieno5@gmail.com | venesaatieno5@gmail.com
