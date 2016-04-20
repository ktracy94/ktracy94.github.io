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
		  		<!--<tr><td>Hosting? <input type="boolean" name="hosting" /></td></tr>-->
		  		
		  		<p>Hosting?</p>
		  		<input type="radio" name="hosting" value="True"> <p>True</p><br>
  				<input type="radio" name="hosting" value="False"> <p>False</p><br>
				
				 <p>Date:</p>
  				<input type="date" name="date">
				
		  		
		  	</table>
		  	<input type="submit" value="Submit" />
		  	
		  	
		  </form>
	
The previous code block is an example of a simple HTML form. This form was is used to get data for somebody registering for an event.
	
 
