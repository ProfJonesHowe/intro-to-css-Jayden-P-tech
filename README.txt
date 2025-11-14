[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/t2sG3BZr)
# Intro_to_CSS
Assignment #4

HTML page: 
<!DOCTYPE html>
<html lang = "en"> 
<head> 
	<link rel="stylesheet" href="styles.css">
	<title> My Advanced Webpage </title> 
</head> 
<body> 
<main> 
	<header>
		<h1> My Webpage</h1>
		<nav> 
			<a href="#about"> About</a> 
			<a href="#gallery"> Gallery</a> 
			<a href="#contact"> Contact</a> 
		</nav>	
	</header>

	<section id = "about">
		<h2> About this page </h2> 
		<p> This section explains the purpose of the site and introduces advanced HTML structure. </p>
	</section> 
		<figure> 
			<img src = "image1.jpg", alt = "HTML and CSS code example"> 
			<figcaption> Figure 1: Clean Semantic Code improves readability and accessibility </figcaption> 
		</figure>
	<section id ="gallery"> 
		<h2> "Image Gallery" </h2> 
		<p> Preview of design samples will go here later. </p> 
	</section> 
	<section id = "contact"> 
		<h2> Contact Form </h2> 
		<form action = "#" method = "post">
			<label for= "name">Name: </label>
			<input type = "text" id = "name" name="name" required>
		
			<label for="email"> Email </label> 
			<input type = "email" id = "email" name = "email" required>

			<label for="message"> Message:</label> 
			 <textarea id= "message" name = "message" rows=4 required></textarea> 

			<button type = "Submit">Send</button>
		</form>
	</section>
</main>
	<footer>
		<p> Web Technologies Essentials </p>
	</footer>
</body> 
</html> 

CSS: 
<link rel="stylesheet" href="styles.css">
body {background: #ffe9f0;}

* {box-sizing: border-box; }
html, body {margin: 0; padding: 0; }

body { 
	font-family: Arial, Helvetica, sans-serif; 
	line-height: 1.8;
	color: #2267D5; 
	max-width: 72ch;
	margin: 0 auto;
	padding: 1rem;
		}

@media (min-width: 700px) 
{
	body {padding: 2rem;
	form {max-width: 600px; }
}
