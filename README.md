Beautiful Problems 
====================

Introduction
------------

Beautiful Problems is a web application to rate competitive programming problems.

Live Demo: https://beautiful-problem.herokuapp.com/

Installation
--------------
Clone the repository in your working directory.

Change directory to project root:

 `cd beautiful-problems`

Create and activate python virtual env:

    python3.6 -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip

Install requirements with:
    
`pip install -r requirements.txt`

How to run
---------------
Configure database with:

    flask db init
    flask db migrate
    flask db upgrade

Run with:

`flask run`