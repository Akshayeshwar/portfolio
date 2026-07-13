# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Portfolio</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:#f4f4f4;
    color:#333;
}

header{
    background:#0d6efd;
    color:white;
    text-align:center;
    padding:25px;
}

nav{
    background:#222;
    text-align:center;
    padding:15px;
}

nav a{
    color:white;
    text-decoration:none;
    margin:15px;
    font-size:18px;
}

nav a:hover{
    color:yellow;
}

section{
    padding:40px;
}

.hero{
    text-align:center;
}

.hero img{
    width:180px;
    height:180px;
    border-radius:50%;
    border:5px solid #0d6efd;
}

.hero h1{
    margin-top:15px;
    font-size:40px;
}

.hero h3{
    color:#555;
    margin-top:10px;
}

.btn{
    display:inline-block;
    margin-top:20px;
    background:#0d6efd;
    color:white;
    padding:12px 25px;
    text-decoration:none;
    border-radius:5px;
}

.btn:hover{
    background:#084298;
}

.about{
    background:white;
}

.skills{
    background:#e9ecef;
}

.skill{
    margin-bottom:20px;
}

.progress{
    width:100%;
    background:#ccc;
    border-radius:20px;
}

.bar{
    height:20px;
    background:#0d6efd;
    border-radius:20px;
}

.projects{
    background:white;
}

.card{
    width:300px;
    display:inline-block;
    margin:20px;
    background:white;
    border-radius:10px;
    box-shadow:0 0 10px gray;
    overflow:hidden;
    vertical-align:top;
}

.card img{
    width:100%;
}

.card h3{
    padding:10px;
}

.card p{
    padding:10px;
}

.card a{
    display:block;
    text-align:center;
    padding:10px;
    background:#0d6efd;
    color:white;
    text-decoration:none;
}

.contact{
    background:#e9ecef;
}

input,textarea{
    width:100%;
    padding:10px;
    margin:10px 0;
}

button{
    background:#0d6efd;
    color:white;
    border:none;
    padding:12px 25px;
    cursor:pointer;
}

button:hover{
    background:#084298;
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
}
</style>

</head>

<body>

<header>
<h1>My Portfolio</h1>
<p>Full Stack Web Developer</p>
</header>

<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</nav>

<section id="home" class="hero">

<img src="profile.jpg" alt="Profile Picture">

<h1>Your Name</h1>

<h3>Full Stack Developer</h3>

<p>
I build responsive websites and web applications using modern technologies.
</p>

<a href="#" class="btn">Download Resume</a>

</section>

<section id="about" class="about">

<h2>About Me</h2>

<br>

<p>
Hello! I'm a passionate web developer with experience in HTML, CSS,
JavaScript, React, Node.js and MongoDB.
I enjoy building modern, responsive, and user-friendly websites.
</p>

</section>

<section id="skills" class="skills">

<h2>Skills</h2>

<br>

<div class="skill">
HTML
<div class="progress">
<div class="bar" style="width:95%"></div>
</div>
</div>

<div class="skill">
CSS
<div class="progress">
<div class="bar" style="width:90%"></div>
</div>
</div>

<div class="skill">
JavaScript
<div class="progress">
<div class="bar" style="width:85%"></div>
</div>
</div>

<div class="skill">
React
<div class="progress">
<div class="bar" style="width:80%"></div>
</div>
</div>

<div class="skill">
Node.js
<div class="progress">
<div class="bar" style="width:75%"></div>
</div>
</div>

</section>

<section id="projects" class="projects">

<h2>Projects</h2>

<div class="card">

<img src="project1.jpg" alt="Project">

<h3>Portfolio Website</h3>

<p>
A responsive portfolio website using HTML, CSS and JavaScript.
</p>

<a href="#">View Project</a>

</div>

<div class="card">

<img src="project2.jpg" alt="Project">

<h3>Weather App</h3>

<p>
Weather application using OpenWeather API.
</p>

<a href="#">View Project</a>

</div>

<div class="card">

<img src="project3.jpg" alt="Project">

<h3>Calculator</h3>

<p>
Simple calculator using JavaScript.
</p>

<a href="#">View Project</a>

</div>

</section>

<section id="contact" class="contact">

<h2>Contact Me</h2>

<form>

<input type="text" placeholder="Your Name" required>

<input type="email" placeholder="Your Email" required>

<input type="text" placeholder="Subject">

<textarea rows="5" placeholder="Message"></textarea>

<button type="submit">Send Message</button>

</form>

</section>

<footer>

<h3>© 2026 Your Name | All Rights Reserved</h3>

</footer>

</body>
</html>
