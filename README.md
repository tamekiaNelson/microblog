# microblog

This program is to have a simple Flask web application running on your computer. The steps include intro to flask, building templates, web forms, the database and user login creation. 

Below are the steps to each part of the build up.


Part One: Intro to Flask
*** Should have been completed prior to this session ***

In the intro to Flask module the basics are setting up flask and installing the required programs will be the main focus. In the end being able to displace "Hello World" is the objective to completing this intro to flask. 

<<<< instruction based on the module assignment >>>>

For our introduction to Flask, we'll be using the Flask Mega Tutorial (Links to an external site.)Links to an external site. series, a course designed by Miguel Grinberg.  Each chapter of this series will serve as both a reading, and assignment. Your instructors will guide you through any difficulties throughout the course.

To complete this first assignment, do the following:

Read the material for part 1 (Links to an external site.)Links to an external site..

Create your own `microblog` repository in your github. Follow best repo practices -- see the Rubric below... (Note: be sure to replace the placeholder text)

Your directory structure should look like this:

.
├── .gitignore
├── Pipfile
├── Pipfile.lock
├── README.md
├── app
│   ├── __init__.py
│   └── routes.py
└── microblog.py

To submit your work, first create a github repository, and push a TAGGED part 1 to it.  

Congratulations, you have completed Flask part 1 "Hello World".  To submit your work, copy and paste the tagged github URL into Canvas.  

------------------------------------------------------------------------------------	
Part 2: Templates 
*** Should have been completed prior to this session ***

In flask templates help with seperation and can be stored in seperate areas or files within the application. Once you have completed the first step of setting up flask this section will help in setting up templates. Below are more details on how this section will flow. 

<<<< instruction based on the module assignment >>>>

Now that we have a basic Flask application up and running, we are going to investigate how the Jinja2 Templating Engine works in Flask.  We'll explore template inheritance as well.

Read the material for part 2 of the Flask Tutorial (Links to an external site.)Links to an external site., and implement the code changes in your microblog repo.  When you are done, commit and tag your changes, using the tag 'v0.2'.  Then push your changes to your github repo, and submit the URL to the tagged commit.

------------------------------------------------------------------------------------
Part 3: Web Forms
*** Should have been completed prior to this session ***

Section 3 of the Flask assignment is going to get more into completing the web forms and installing additional program extension to ensure that everything runs and integrates easier. 

<<<< instruction based on the module assignment >>>>

Here we will explore how to get user input into Flask by way of web forms.  We'll also install the Flask-WTF extension to make this integration easier.  Great name for an extension, BTW.

We'll look at how to implement configuration for Flask:  Where are all the various tokens, settings, and environment variables kept?  What is best practice for managing these?  There will be some form validation, and exploration of decoupling: how to not bog down your code with literal references to API routes.

-------------------------------------------------------------------------------------
Part 4: The Database
*** Should have been completed prior to this session ***

Now that web forms are setup this section goes step by step on setting up a way to maintain the data that is being added. Databases in Flask are customizeable and in this section you have the freedom to intergrate a database that feeds your needs. 

<<<< instruction based on the module assignment >>>>

Topics
Setup of the database as a persistent store  
Object Relational Mappers (ORMs) and why they are so powerful
Migrations: Changing database schemas, doing up- and down-migrations
Database models & relationships
DB queries via SQLAlchemy
Flask shell commands
 
Additional Libraries to install:
Flask-SQLAlchemy (Links to an external site.)Links to an external site.
Flask-Migrate (Links to an external site.)Links to an external site.
To Do:
Read and understand section 4, and implement the code changes in your codebase as you are reading. Be sure to run through the REPL examples of the manual database queries.

-------------------------------------------------------------------------------------
Part 5: User Logins
*** Current session that is being built on ***

The final part of the flask section is seting up login and logout functionality. Flask has a extension that assist in this area where it can "remember" details for login. In this session you will be able to implement those extentions and build on what you have created in the previous steps. 

<<<< instruction based on the module assignment >>>>

Topics
Password hashing
Adapting the User model with a `mixin` class
Logging users in and out
Protecting routes with @login
Registering new users
Libraries to install
Flask-login (Links to an external site.)Links to an external site.
To Do
This section examines html-rendered (template) login functionality.  Application-based logins (e.g. JWT authentication) will come later in the series.  Read and understand section 5, and implement the code changes in your codebase as you are reading. 