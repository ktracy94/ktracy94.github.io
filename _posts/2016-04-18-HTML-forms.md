---
published: true
layout: post
---

One of the first things anyone learns when beginning HTML development is how to use forms to get information from users. This is critical because it is the first way most people learn to get input from users, and by understanding this simple HTML development interactive sites can be created quickly and efficiently.

In order to create a simple HTML form, you simply need to know the basic HTML tags to use to indicate the creation of a form. 

		<h2>Registration Form</h2>
		  <form method= "POST" action="/registration">
		  	<table>
		  		<tr><td><p>Full Name</p> <input type="text" name="fname" /></td></tr>
		  		<p></p>
		  		<tr><td><p>Address</p> <input type="text" name="address" /></td></tr>
		  		<tr><td><p>School Year</p><input type="number" name="year" /></td></tr>
		  		<tr><td><p>Movie Name</p><input type="text" name="movie" /></td></tr>
		  		
		  		<p>Hosting?</p>
		  		<input type="radio" name="hosting" value="True"> <p>True</p><br>
  				<input type="radio" name="hosting" value="False"> <p>False</p><br>
				
				<p>Date:</p>
  				<input type="date" name="date">
				
		  		
		  	</table>
		  	<input type="submit" value="Submit" />
		  	
		  	
		  </form>
	
The previous code block is an example of a simple HTML form. This form was is used to get data for somebody registering for an event, and allows for the user to get an impressive amount of data in a rather simple solution. The most important thing to remember when using forms are as follows:

1. Correctly using your form tags
When using forms, always use the correct HTML tags. This will ensure that your form works as intended.

2. Make sure your input type is correct
You want to make sure that the input you receive from the form is the same thing that you think it is. If you are looking for the date, always use the "date" type so that the user feels more comfortable and understands exactly what they are supposed to enter. 

3. Use relevant names for your inputs
Making names for your inputs that are easy to remember help later down the line when you access the values in Python.

### Accessing the code in Python

The main issue from here is of course accessing the input the user gave from your backend code. By getting access to these values you can successfully input them into your SQL database, or whatever type database you are using. 

I stuck with the standard way of accessing these inputs bying using Python, and one of its libraries call Python Flask. In the next blog I will go over the basics of flask in Cloud9.
