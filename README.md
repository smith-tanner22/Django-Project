# Overview

For this project I am taking a dive into Django web application and setting up certain databases to store input. For this project I created a polls application that asks "Would you Rather" questions to the user and keeps track of what gets voted. I also created an Admin page where I can see the questions and answers and what was being voted on. I can also add more questions and options and post when I put those in to keep better track of the polls.

To start a test server you must first download django onto your computer and make sure that it is working with terminal. Then you run the "django-admin startproject mysite" command in the terminal and this will create a project for you in your directory. CD into the directory and run the command "python manage.py runserver" This will create a server for you to use and give you a link to where it can be located on the browser. After that its just a matter of typing in the right thing into the browser to see different types of the page. For example if you wanted to go to the admin of your page it would be, "http://localhost:8000/admin/" or in my case if I wanted to get to my polls it would be, "http://localhost:8060/polls/" (I changed the Internal IP number to show that it can be different numbers.)

A walkthrough of the code and webpages can be found below 👇

[Django Project - Would you rather](https://youtu.be/6M3vtjfVC7o)

# Web Pages

The most important webpage i needed to create was the admin page. This allowed me to login with my own secure credentials and be able to edit the site and content of the page, as well as keep track of answers to the questions that I created. The only other pages were the poll questions all grouped together and then the poll itself where it would go in one question at a time and as you answer them it tells you what other people voted for thanks to the database within Django.

# Development Environment
For this project I used Visual Studio Code to create the application, and within it I used Django, Python, HTML, and CSS to help create and style the webpages. I also used Django built in database system: SQLite. There was a lot of libraries involved including django.http, django.urls, django.contrib, django.db, django.utils, django.shortcuts, polls.models, and datetime.

# Useful Websites
Helpful Websites:

* [djangoproject.com (Help in installing Django)](https://docs.djangoproject.com/en/3.2/intro/install/)
* [djangoproject.com (Help in terminology and Error codes)](https://docs.djangoproject.com/en/3.2/ref/django-admin/)
* [developer.mozilla.org (What is Django)](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Introduction)

# Future Work

* Create a more accessible database using MySQL instead of the built in SQLite
* Have the pages more naturally flow into each other.
* Better CSS for the webpages.