<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Srinivasan | AWS Cloud & DevOps Engineer</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#050816;
overflow:hidden;
color:white;
}

/* Animated Gradient */

body::before{

content:"";

position:fixed;

width:100%;
height:100%;

background:linear-gradient(
135deg,
#050816,
#0f172a,
#1e3a8a,
#7c3aed,
#06b6d4,
#0f172a
);

background-size:500% 500%;

animation:gradientMove 20s ease infinite;

z-index:-5;

}

@keyframes gradientMove{

0%{background-position:0% 50%;}

50%{background-position:100% 50%;}

100%{background-position:0% 50%;}

}

/* Floating Particles */

.particles{

position:fixed;

top:0;
left:0;

width:100%;
height:100%;

overflow:hidden;

z-index:-2;

}

.particles span{

position:absolute;

display:block;

width:6px;

height:6px;

border-radius:50%;

background:#00f7ff;

box-shadow:
0 0 10px #00f7ff,
0 0 20px #00f7ff,
0 0 30px #00f7ff;

animation:float linear infinite;

opacity:.8;

}

@keyframes float{

0%{

transform:translateY(100vh) scale(0);

opacity:0;

}

20%{

opacity:1;

}

100%{

transform:translateY(-120vh) scale(1.5);

opacity:0;

}

}

/* Hero */

.hero{

height:100vh;

display:flex;

justify-content:center;

align-items:center;

text-align:center;

padding:20px;

}

.glass{

width:900px;

padding:60px;

border-radius:25px;

background:rgba(255,255,255,.08);

backdrop-filter:blur(25px);

border:1px solid rgba(255,255,255,.15);

box-shadow:0 0 40px rgba(0,255,255,.25);

}

h1{

font-size:70px;

font-weight:800;

margin-bottom:10px;

}

h2{

color:#00f7ff;

margin-bottom:20px;

}

p{

font-size:18px;

line-height:1.8;

margin-bottom:30px;

}

.tech{

display:flex;

justify-content:center;

flex-wrap:wrap;

gap:15px;

}

.tech span{

padding:12px 22px;

background:rgba(255,255,255,.1);

border-radius:40px;

transition:.3s;

}

.tech span:hover{

background:#00f7ff;

color:black;

transform:translateY(-6px);

}

</style>

</head>

<body>

<div class="particles"></div>

<section class="hero">

<div class="glass">

<h1>Srinivasan</h1>

<h2>AWS Cloud & DevOps Engineer</h2>

<p>

Building Secure • Scalable • Automated Cloud Infrastructure

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

</div>

</section>

<script>

const particles=document.querySelector(".particles");

for(let i=0;i<150;i++){

let particle=document.createElement("span");

let size=Math.random()*6+2;

particle.style.width=size+"px";
particle.style.height=size+"px";

particle.style.left=Math.random()*100+"vw";

particle.style.animationDuration=(8+Math.random()*12)+"s";

particle.style.animationDelay=Math.random()*10+"s";

particle.style.background=["#00f7ff","#38bdf8","#7c3aed","#ffffff"][Math.floor(Math.random()*4)];

particles.appendChild(particle);

}

</script>

</body>
</html>
