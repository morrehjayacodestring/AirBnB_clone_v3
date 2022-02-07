
0x05. AirBnB clone - RESTful API
 By Guillaume, CTO at Holberton School
 Weight: 2
 Project to be done in teams of 2 people (your team: Samuel Ogoigbe, MORRIS MUTISYA SAMMY
 Ongoing project - started 02-03-2022, must end by 02-08-2022 (in about 13 hours) - you're done with 0% of tasks.
 Checker was released at 02-04-2022 06:00 PM
 QA review fully automated.
Concepts
For this project, students are expected to look at these concepts:

REST API
AirBnB clone
Resources
Read or watch:

REST API concept page
Learn REST: A RESTful Tutorial
Designing a RESTful API with Python and Flask
HTTP access control (CORS)
Flask cheatsheet
What are Flask Blueprints, exactly?
Flask
Modular Applications with Blueprints
Flask tests
Flask-CORS
AirBnB clone - RESTful API
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
What REST means
What API means
What CORS means
What is an API
What is a REST API
What are other type of APIs
Which is the HTTP method to retrieve resource(s)
Which is the HTTP method to create a resource
Which is the HTTP method to update resource
Which is the HTTP method to delete resource
How to request REST API
Requirements
Python Scripts
Allowed editors: vi, vim, emacs
All your files will be interpreted/compiled on Ubuntu 14.04 LTS using python3 (version 3.4.3)
All your files should end with a new line
The first line of all your files should be exactly #!/usr/bin/python3
A README.md file, at the root of the folder of the project, is mandatory
Your code should use the PEP 8 style (version 1.7)
All your files must be executable
The length of your files will be tested using wc
All your modules should have documentation (python3 -c 'print(__import__("my_module").__doc__)')
All your classes should have documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
All your functions (inside and outside a class) should have documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')
A documentation is not a simple word, s a real sentence explaining s the purpose of the module, class or method (the length of it will be verified)
Python Unit Tests
Allowed editors: vi, vim, emacs
All your files should end with a new line
All your test files should be inside a folder tests
You have to use the unittest module
All your test files should be python files (extension: .py)
All your test files and folders should start by test_
Your file organization in the tests folder should be the same as your project: ex: for models/base_model.py, unit tests must be in: tests/test_models/test_base_model.py
All your tests should be executed by using this command: python3 -m unittest discover tests
You can also test file by file by using this command: python3 -m unittest tests/test_models/test_base_model.py
We strongly encourage you to work together on test cases, so that you t miss any edge cases
GitHub
There should be one project repository per group. If you clone/fork/whatever a project repository with the same name before the second deadline, you risk a 0% score.

More Info



Install Flask
$ pip3 install Flask
Tasks
0. Restart from scratch!
mandatory
No no no! We are already too far in the project to restart everything.

But once again, s work on a new codebase.

For this project you will fork this codebase:

Update the repository name to AirBnB_clone_v3
Update the README.md:
Add yourself as an author of the project
Add new information about your new contribution
Make it better!
If re the owner of this codebase, create a new repository called AirBnB_clone_v3 and copy over all files from AirBnB_clone_v2
Repo:

GitHub repository: AirBnB_clone_v3
  
1. Never fail!
mandatory


Since the beginning ve been using the unittest module, but do you know why unittests are so important? Because when you add a new feature, you refactor a piece of code, 
At Holberton, we have a lot of tests, and they all pass! Just for the Intranet itself, there are:

5,213 assertions (as of 08/20/2018)
13,061 assertions (as of 01/25/2021)
The following requirements must be met for your project:

all current tests must pass (t delete themdonetcweyouletdonwhatit# AirBnB_clone_v3
