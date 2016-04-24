---
published: true
"layout :": post
layout: post
---
## Python Flask

The first step to ensure that Python Flask is installed on your server. As we discussed last post, I am currently using Flask to retrieve data from the user who is attempting to register for something. The first thing that I did in my code was to ensure that I have correct inclusions. The top of my Server.py code is:

	import os
	import psycopg2
	import psycopg2.extras
	from flask import Flask, render_template, request
    
I created a "registration" function after this which then allows the python code to access what has been entered into the fields, as shown below in a screenshot of the form.

![](https://raw.githubusercontent.com/ktracy94/ktracy94.github.io/master/_posts/Capture1.PNG)

Once the user hits the "Submit" button, it will send the rest of the data to the python code in what is called a dictionary. This dictionary contains key-value pairs which allow the programmer to easily access the data that they require. To access this code, I first had to use the "request" function in order to grab it from the HTML side. 

	    peopleDict.append({'fname': request.form['fname']
        ,'address': request.form['address']
        ,'year': request.form['year']
        ,'movie': request.form['movie']
        ,'hosting': request.form['hosting']
        ,'date': request.form['date']})