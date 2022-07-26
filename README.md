# nunamassignment
Assignment details 
Task 1: The given two data files are:
1.	5329.xls and 5308.xls
2.	Converting two given data files to .csv files
3.	5329.csv and 5308.csv
Task 2: Select required column of given sheets and make new excel file.
1.	Voltage, Current, Capacity and time columns from Detail sheet and temperature column from DetailTemp sheet.
2.	Do same process with both sheets (5329,5308).
3.	Make two new excel file.
Task 3: Import data from excel to MySQL database.
1: Create new schema/ database.
2: Import excel data to database through tables data import Wizard.
Task 4: Create the app.py Python script
1: To create web application, we import flask
           from flask import Flask
           from flask_cors import CORS, cross_origin
           app = Flask(__name__)
           CORS (app)
2: create the flask instance to use with MySQL module.
Task 5: create config.py Python file
1.	create config.py Python file to initialize MySQL database connection details to          make connection with MySQL database.
2.	Import the app script to handle MySQL database connection with Flask-MySQL   module.
Task 6: create main.py script
1.	create main.py script and import the app and config modules.
2.	Then connect to MySQL database and implement CRUD operations by defining all REST URIs.
Task 7: Install Postman
1.	Use Postman to run our Python RESTful API with (POST, GET, PUT or DELETE) methods to test it.
 Task 8: Using Plotly
1.	for visualization /graphs we use plotly in python.
2.	Import plotly.express as px
