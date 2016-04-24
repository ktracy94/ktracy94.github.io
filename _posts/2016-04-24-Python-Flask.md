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

[Capture1.PNG]({{site.baseurl}}/_posts/Capture1.PNG)
