# Conspiverse-Blog
<img src="https://github.com/adi2381/conspiverse-blog/blob/master/django.png" height="100" width="200">
The aim of this project was to get better hang of django and get more into it.

It's safe to say that after this project, there's no doubt I love Django for tons of reasons, i'll just tell my few favorites.

* Ridiculously easy-to-understand documentation
* Ability to Quickly preview all the changes made through it's own local server
* Everything from user authentication to literally anything is just an import away

#### Why the fancy name, Conspiverse? 
There's no dedicated platform for conspiracy theorists to discuss and just talk in general.
So, this project is just a skeleton or base for that containing functionalities such as user authentication, creating groups, posting etc.

## Getting Started

### Version
Following versions of python and django were used in this project, refrain from using other versions due to incompatilibity issues.
Specifically use Django 1.11.17 as Django 1.11 contains a bug which prevents from running django's local server.
Bootstrap3 was specifically used as Bootstrap4 was having rendering problems.
* Python 3
* Django 1.11.17
* Bootstrap 3

### Running the Project

* Clone Directory

When you clone the directly and unzip the files, put everything in a new folder and then open it up in visual code or atom.
The directory is divided into:

posts

groups

accounts

main project files

static files (containing css)

templates (containing html)

* Create a virtual env using conda or python

``` conda create -n yourenvname ``` Or ``` py -m venv yourenvname ```

* Activate Virtual Environment

``` conda activate yourenvname``` Or ``` source activate yourenvname ```

* Install Django 1.11.17

``` pip install django==1.11.17 ```

* Install Bootstrap3

``` pip install django-bootstrap3 ```

* Install Misaka (provides markdown parsing when commenting or creating posts, so "strong" "em" tags would render immediately)

``` pip install misaka ```

* Install django-braces 1.13.0 - Provides mixins to add easy functionality to Django class-based views, forms, and models.
Mixins is a special type of multiple-inheritance in python. A Mixin class contains methods from other classes which can be further
shared by other classes by inheriting them.

``` pip install django-braces ```

* Run server

``` python manage.py runserver ```

* In the browser, Input <strong>127.0.0.1: 8000</strong>

## Shoutout

* Python Django Framework Full Course - Learning with the Docs - <strong> FreeCodeCamp </strong>

This tutorial from freecodecamp was extremely helpful in understanding the documentation - [Tutorial Link](https://www.youtube.com/watch?v=cI3FOYIMSYE)

* Django - Create a Blog - <strong> Shaun a.k.a @thenetninja </strong>

This amazing tutorial by Shaun was taken as a reference when creating the conspiverse blog - [Tutorial Link](https://www.youtube.com/watch?v=jAE94gzgQvI&list=PL4cUxeGkcC9ib4HsrXEYpQnTOTZE1x0uc&index=2)



