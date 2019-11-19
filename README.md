# Writers Blog


This repository contains the source code of Writers Blog, a social media app built using Django where users can create profiles and write blogs, and also leave comments on post.
This enables users to visit the application and perform basic CRUD and also upload pictures.
The customers will have a level of authorization before they can perform some of the operations. 

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
- Install pip if it is not installed yet in your system

- To install virtual environment, run in your terminal:

`pip install virtualenv`
- To create a virtual environment, in the root folder of the cloned app, run:
`virtualenv -p python3 venv`
- To activate the virtualenv:
`source venv/bin/activate`
- Run the command below to install all the project dependencies:
`pip install -r requirements.txt`
- To deactivate the virtualenv, run the command below:
`deactivate`
### Installing
- Clone this repository
https://github.com/Celoka/writers-Blog.git

- Cd into the cloned app, create a virtualenv and activate(see instruction above for steps to create a virtualenv)

- Create a .env file, copy the variables in the .env_sample in the root directory of the project and set up the configurations according to your system.

- Ensure to makemigrations then migrate by running the following commands sequencially:

`python manage.py makemigrations`

`python manage.py migrate`

- To start the application, in the root directory of the project, run:
python manage.py runserver

## Features of the Project
- User Registration
- User Login
- User Upload Passport Photo
- Admin/User athentication
- User create blog post
- User edit blog post
- User list all/individual blog post
- User delet blog post

## Built With
- Python 3
- Sqlite
- Django (MVC style framework)

## Authors
- Eloka Chima
