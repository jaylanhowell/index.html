<!DOCTYPE html>
<html>
<head>
<title>Jaylan's Web Design</title>
<style>
 body {
 font-family: Arial, Helvetica, sans-serif;
 font-size: 15px;
 line-height: 1.5;
 padding: 0;
 margin: 0;
 background-color: #f4f4f4;
 }
.container {
width: 80%;
margin: auto
overflow: hidden;
}
ul {
margin: 0;
padding: 0;
}
.button_1 {
height: 38px;
background: #e8491d;
border: 0;
padding-left: 20px;
padding-right: 20px;
color: white;
}
header {
background: #35424a;
color: #ffffff;
min-height: 70px;
border-bottom: #e8491d 3px solid;
}
header a {
color: #ffffff;
text-decoration: none;
text-transform: uppercase;
font-size: 16px;
}
header li {
float: left;
display: inline;
padding: 0 20px 0 20px;
}
header #branding {
float: left;
}
header #branding h1 {
margin: 0;
}
header nav {
float: right;
margin-top: 10px;
}
header .highlight, header .current a {
color: #e8491d;
font-weight: fold;
}
header a:hover {
color: #cccccc;
font-weight: bold;
}
#showcase {
min-height: 400px;
background: url('../Pictures/showcase2.png') no-repeat 0 -400px;
text-align: center;
color: white;
}
#showcase h1 {
margin-top: 100px;
font-size: 55px;
margin-bottom: 10px;
}
#showcase p {
font-size: 20px;
}
#newsletter {
padding: 15px;
color: white;
background: #35424a;
}
#newsletter h1 {
float: left;
}
#newsletter form {
float: right;
margin-bottom: 250px;
}
#newsletter input[type="email"] {
padding: 4px;
height: 25px;
width: 250px;
}
#boxes {
margin-top: 20px;
}
footer {
padding: 20px;
margin-top: 20px;
color: white;
background-color: #e8491d;
text-align: center;
}
@media(max-width: 768px;) {
header #branding,
header nav;
header nav li {
float: none;
text-align: center;
width: 100%;
}
header {
padding-bottom: 20px;
 }
}
</style>
</head>
<body>

<header>
<div class="container">
<div id="branding">
<h1><span class="highlight">Jaylan's</span> Website Design</h1>
</div>
<nav>
<ul>
<li class="current"><a href="index.html">Home</a></li>
<li><a href="about.html">About</a></li>
<li><a href="services.html">Services</a></li>
</ul>
</nav>
</div>
</header>

<section id="showcase">
<div class="container">
<h1>Affordable Professional Web Design</h1>
    <p>Condimentum. Netus. Dictumst. Donec Netus semper id aliquam arcu ligula. Class purus nam ligula laoreet dis montes. Lobortis, hymenaeos scelerisque. Parturient sociosqu senectus placerat hendrerit massa. Elementum. Elementum. Lectus eu lorem, montes blandit per pharetra tortor proin felis. Lacinia. Fames mollis magna erat conubia mattis.
Duis tortor elit hendrerit semper tempor.
</p>
</div>
</section>

<section id="newsletter">
<div class="container">
<h2>Subscribe To Our Newsletter</h2>
<form>
<input type="email" placeholder="Enter Email...">
<button type="Submit" class="button_1">Subscribe</button>
</form>
</div>
</section>

<section id="boxes">
<div class="container">
<div class="box"
<h3>HTML5 Markup</h3>
<p>
Nulla nascetur, curae; erat nec potenti velit. Senectus sodales vestibulum sed. Gravida conubia per orci amet eleifend.</p>
</div>
<div class="box"
<h3>CSS3 Styling</h3>
<p>
Nulla nascetur, curae; erat nec potenti velit. Senectus sodales vestibulum sed. Gravida conubia per orci amet eleifend.</p>
</div>
<div class="box"
<h3>Graphic Design</h3>
<p>
Nulla nascetur, curae; erat nec potenti velit. Senectus sodales vestibulum sed. Gravida conubia per orci amet eleifend.</p>
</div>
</div>
</section>


<footer>
<p>Jaylan's Web Design, Copyright &copy; 2017</p>
</footer>
</body>
