<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Srinivasan | AWS DevOps Engineer</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700;800&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins,sans-serif;
}

html{
scroll-behavior:smooth;
}

body{

background:#030712;
overflow-x:hidden;
color:white;

}

/* Animated Background */

body::before{

content:"";

position:fixed;

width:100%;
height:100%;

background:
linear-gradient(135deg,#1e3a8a,#7c3aed,#06b6d4,#14b8a6,#2563eb);

background-size:500% 500%;

animation:gradient 15s ease infinite;

z-index:-3;

}

@keyframes gradient{

0%{background-position:0% 50%;}
50%{background-position:100% 50%;}
100%{background-position:0% 50%;}

}

/* Floating Blobs */

.blob{

position:fixed;

border-radius:50%;

filter:blur(80px);

opacity:.4;

animation:float 15s infinite alternate;

z-index:-2;

}

.b1{

width:300px;
height:300px;

background:#00e5ff;

top:5%;
left:10%;

}

.b2{

width:400px;
height:400px;

background:#7c3aed;

bottom:0;
right:5%;

}

@keyframes float{

from{

transform:translateY(-40px);

}

to{

transform:translateY(40px);

}

}

nav{

display:flex;

justify-content:space-between;

padding:25px 10%;

backdrop-filter:blur(20px);

background:rgba(255,255,255,.05);

position:fixed;

width:100%;

z-index:999;

}

nav h2{

color:#00f7ff;

}

nav ul{

display:flex;

list-style:none;

gap:35px;

}

nav a{

color:white;

text-decoration:none;

font-weight:500;

transition:.3s;

}

nav a:hover{

color:#00f7ff;

}

.hero{

height:100vh;

display:flex;

justify-content:center;

align-items:center;

padding:30px;

}

.card{

width:850px;

padding:60px;

text-align:center;

border-radius:30px;

background:rgba(255,255,255,.08);

backdrop-filter:blur(25px);

border:1px solid rgba(255,255,255,.15);

box-shadow:0 0 50px rgba(0,255,255,.2);

}

.profile{

width:170px;

height:170px;

border-radius:50%;

border:5px solid cyan;

margin-bottom:20px;

box-shadow:0 0 30px cyan;

}

h1{

font-size:60px;

font-weight:800;

margin-bottom:15px;

}

.title{

font-size:26px;

color:#00f7ff;

margin-bottom:20px;

}

.desc{

font-size:18px;

line-height:1.8;

opacity:.9;

margin-bottom:35px;

}

.tech{

display:flex;

justify-content:center;

flex-wrap:wrap;

gap:15px;

margin-bottom:40px;

}

.tech span{

padding:12px 22px;

border-radius:40px;

background:rgba(255,255,255,.1);

transition:.3s;

cursor:pointer;

}

.tech span:hover{

background:#00f7ff;

color:black;

transform:translateY(-6px);

}

.btn{

padding:15px 35px;

border-radius:40px;

text-decoration:none;

font-weight:bold;

margin:10px;

display:inline-block;

transition:.4s;

}

.primary{

background:#00f7ff;

color:black;

}

.secondary{

border:2px solid cyan;

color:white;

}

.primary:hover{

transform:scale(1.08);

box-shadow:0 0 25px cyan;

}

.secondary:hover{

background:cyan;

color:black;

}

.stats{

display:grid;

grid-template-columns:repeat(4,1fr);

margin-top:50px;

gap:20px;

}

.box{

padding:25px;

border-radius:20px;

background:rgba(255,255,255,.06);

transition:.4s;

}

.box:hover{

transform:translateY(-8px);

box-shadow:0 0 20px cyan;

}

.box h3{

font-size:35px;

color:#00f7ff;

}

.box p{

margin-top:8px;

}

@media(max-width:768px){

h1{

font-size:40px;

}

.stats{

grid-template-columns:repeat(2,1fr);

}

nav ul{

display:none;

}

}

</style>

</head>

<body>

<div class="blob b1"></div>
<div class="blob b2"></div>

<nav>

<h2>☁ DevOps Portfolio</h2>

<ul>

<li><a href="#">Home</a></li>

<li><a href="#">About</a></li>

<li><a href="#">Projects</a></li>

<li><a href="#">Skills</a></li>

<li><a href="#">Contact</a></li>

</ul>

</nav>

<section class="hero">

<div class="card">

<img src="profile.jpg" class="profile">

<h1>Srinivasan</h1>

<div class="title">
AWS Cloud & DevOps Engineer
</div>

<p class="desc">

Building Secure • Scalable • Automated Cloud Infrastructure using AWS, Terraform, Docker, Jenkins and GitHub Actions.

</p>

<div class="tech">

<span>☁ AWS</span>

<span>🏗 Terraform</span>

<span>🐳 Docker</span>

<span>⚙ Jenkins</span>

<span>🚀 GitHub Actions</span>

<span>🐧 Linux</span>

<span>📊 Grafana</span>

<span>🔥 Prometheus</span>

</div>

<a href="#" class="btn primary">
🚀 View Projects
</a>

<a href="#" class="btn secondary">
📄 Download Resume
</a>

<div class="stats">

<div class="box">

<h3>4+</h3>

<p>Years Experience</p>

</div>

<div class="box">

<h3>15+</h3>

<p>Projects</p>

</div>

<div class="box">

<h3>10+</h3>

<p>DevOps Tools</p>

</div>

<div class="box">

<h3>24x7</h3>

<p>Automation</p>

</div>

</div>

</div>

</section>

</body>

</html>
