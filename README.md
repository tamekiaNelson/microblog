# microblog

Part One: Intro to Flask
*** Should have been completed prior to this session ***

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

Now that we have a basic Flask application up and running, we are going to investigate how the Jinja2 Templating Engine works in Flask.  We'll explore template inheritance as well.

Read the material for part 2 of the Flask Tutorial (Links to an external site.)Links to an external site., and implement the code changes in your microblog repo.  When you are done, commit and tag your changes, using the tag 'v0.2'.  Then push your changes to your github repo, and submit the URL to the tagged commit.

------------------------------------------------------------------------------------
Part 3: Web Forms
*** Current session that is being built on ***

Here we will explore how to get user input into Flask by way of web forms.  We'll also install the Flask-WTF extension to make this integration easier.  Great name for an extension, BTW.

We'll look at how to implement configuration for Flask:  Where are all the various tokens, settings, and environment variables kept?  What is best practice for managing these?  There will be some form validation, and exploration of decoupling: how to not bog down your code with literal references to API routes.

-------------------------------------------------------------------------------------