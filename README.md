<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Golu Kumar - Professional Website Creator</title>

<!-- SEO -->
<meta name="description" content="Golu Kumar - Professional Website Creator. Modern websites and digital solutions.">
<meta name="keywords" content="Website Developer, Web Designer, Freelancer India">
<meta name="author" content="Golu Kumar">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:Arial, sans-serif;
line-height:1.6;
color:#333;
background:linear-gradient(135deg,#667eea,#764ba2);
min-height:100vh;
}

/* Container */
.container{
max-width:1200px;
margin:auto;
padding:0 20px;
}

/* Header */
header{
background:rgba(255,255,255,.95);
position:fixed;
width:100%;
top:0;
z-index:1000;
box-shadow:0 2px 15px rgba(0,0,0,.1);
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:15px 0;
}

.logo{
font-size:1.8rem;
font-weight:bold;
color:#667eea;
}

.nav-links{
display:flex;
gap:2rem;
list-style:none;
}

.nav-links a{
text-decoration:none;
color:#333;
font-weight:500;
transition:.3s;
}

.nav-links a:hover,
.nav-links a.active{
color:#667eea;
font-weight:bold;
}

/* HERO */
.hero{
height:100vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
color:white;
background:linear-gradient(135deg,#667eea,#764ba2);
background-size:400% 400%;
animation:gradientMove 10s ease infinite;
}

@keyframes gradientMove{
0%{background-position:0% 50%;}
50%{background-position:100% 50%;}
100%{background-position:0% 50%;}
}

.hero h1{
font-size:3.5rem;
margin-bottom:1rem;
}

.hero p{
font-size:1.3rem;
margin-bottom:2rem;
}

.cta-button{
background:#ff6b6b;
color:white;
padding:15px 40px;
text-decoration:none;
border-radius:50px;
font-weight:bold;
transition:.3s;
}

.cta-button:hover{
transform:translateY(-3px);
background:#ff5252;
}

/* Sections */
section{
padding:100px 0;
}

.section-title{
text-align:center;
font-size:2.5rem;
margin-bottom:3rem;
color:white;
}

/* About */
.about{
background:rgba(255,255,255,.1);
color:white;
text-align:center;
}

/* Services */
.services{
background:white;
}

.services .section-title{
color:#333;
}

.services-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:2rem;
}

.service-card{
background:#f8f9ff;
padding:2rem;
border-radius:20px;
text-align:center;
transition:.3s;
}

.service-card:hover{
transform:translateY(-10px);
box-shadow:0 15px 30px rgba(0,0,0,.1);
}

/* Contact */
.contact{
background:rgba(255,255,255,.1);
color:white;
text-align:center;
}

.contact-info{
background:rgba(255,255,255,.2);
padding:2rem;
border-radius:20px;
margin-top:2rem;
}

.phone-number{
font-size:2rem;
color:#ff6b6b;
font-weight:bold;
}

/* Footer */
footer{
background:rgba(0,0,0,.2);
color:white;
text-align:center;
padding:2rem 0;
}

/* WhatsApp Button */
.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:white;
font-size:24px;
padding:15px;
border-radius:50%;
text-decoration:none;
box-shadow:0 5px 15px rgba(0,0,0,.3);
}

/* Mobile */
@media(max-width:768px){
.nav-links{display:none;}
.hero h1{font-size:2.5rem;}
}
</style>
</head>

<body>

<header>
<nav class="container">
<div class="logo">Golu Kumar</div>

<ul class="nav-links">
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#services">Services</a></li>
<li><a href="#portfolio">Portfolio</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>
</header>

<!-- HERO -->
<section id="home" class="hero">
<div class="container">
<h1>Golu Kumar</h1>
<p>Professional Website Creator | Building Stunning Digital Experiences</p>
<a href="#contact" class="cta-button">Get Your Website Today</a>
</div>
</section>

<!-- ABOUT -->
<section id="about" class="about">
<div class="container">
<h2 class="section-title">About Me</h2>
<p>I create modern, responsive and high-performance websites for businesses and individuals.</p>
</div>
</section>

<!-- SERVICES -->
<section id="services" class="services">
<div class="container">
<h2 class="section-title">My Services</h2>

<div class="services-grid">
<div class="service-card">🎨 Custom Website Design</div>
<div class="service-card">⚡ Responsive Development</div>
<div class="service-card">🚀 E-commerce Solutions</div>
<div class="service-card">🔧 Website Maintenance</div>
<div class="service-card">📱 Mobile Apps</div>
<div class="service-card">⚙️ SEO Optimization</div>
</div>

</div>
</section>

<!-- PORTFOLIO -->
<section id="portfolio" class="services">
<div class="container">
<h2 class="section-title">My Work</h2>

<div class="services-grid">
<div class="service-card">Business Website Project</div>
<div class="service-card">E-commerce Store</div>
<div class="service-card">Portfolio Website</div>
</div>

</div>
</section>

<!-- CONTACT -->
<section id="contact" class="contact">
<div class="container">
<h2 class="section-title">Contact Me</h2>

<div class="contact-info">
<span class="phone-number">📞 +91 9263978316</span>
<p>✉️ golukumar@example.com</p>
</div>

</div>
</section>

<footer>
<p>© 2024 Golu Kumar | Professional Website Creator</p>
</footer>

<!-- WhatsApp -->
<a href="https://wa.me/9263978316" class="whatsapp" target="_blank">💬</a>

<script>

/* Smooth Scroll */
document.querySelectorAll('a[href^="#"]').forEach(anchor=>{
anchor.addEventListener("click",function(e){
e.preventDefault();
document.querySelector(this.getAttribute("href"))
.scrollIntoView({behavior:"smooth"});
});
});

/* Active Menu */
const sections=document.querySelectorAll("section");
const navLinks=document.querySelectorAll(".nav-links a");

window.addEventListener("scroll",()=>{
let current="";

sections.forEach(section=>{
const top=section.offsetTop-150;
if(scrollY>=top){
current=section.getAttribute("id");
}
});

navLinks.forEach(a=>{
a.classList.remove("active");
if(a.getAttribute("href")==="#"+current){
a.classList.add("active");
}
});
});

</script>

</body>
</html>
