
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>DETECTOR PRO | Professional Metal Detectors</title>

<meta name="description"
content="Professional metal detectors and ground detection technology. Explore our latest detection systems.">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:Arial, Helvetica, sans-serif;
    background:#080a0d;
    color:#fff;
    line-height:1.6;
}

/* HEADER */

header{
    position:fixed;
    top:0;
    left:0;
    width:100%;
    z-index:1000;
    background:rgba(8,10,13,.94);
    border-bottom:1px solid rgba(212,175,55,.25);
    backdrop-filter:blur(10px);
}

.navbar{
    max-width:1200px;
    margin:auto;
    height:75px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:0 20px;
}

.logo{
    color:#d4af37;
    font-size:25px;
    font-weight:bold;
    letter-spacing:2px;
}

.logo span{
    color:white;
}

nav{
    display:flex;
    gap:28px;
}

nav a{
    color:#ddd;
    text-decoration:none;
    font-size:15px;
    transition:.3s;
}

nav a:hover{
    color:#d4af37;
}

.menu{
    display:none;
    font-size:28px;
    cursor:pointer;
}

/* HERO */

.hero{
    min-height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    padding:120px 20px 70px;
    background:
    radial-gradient(circle at center,rgba(212,175,55,.16),transparent 45%),
    linear-gradient(135deg,#080a0d,#11151a);
}

.hero-content{
    max-width:850px;
}

.hero h1{
    font-size:clamp(42px,7vw,78px);
    line-height:1.05;
    margin-bottom:25px;
}

.gold{
    color:#d4af37;
}

.hero p{
    color:#bbb;
    font-size:19px;
    max-width:700px;
    margin:auto auto 35px;
}

.buttons{
    display:flex;
    justify-content:center;
    gap:15px;
    flex-wrap:wrap;
}

.btn{
    display:inline-block;
    padding:14px 28px;
    border-radius:5px;
    text-decoration:none;
    font-weight:bold;
    transition:.3s;
}

.btn-primary{
    background:#d4af37;
    color:#080a0d;
}

.btn-primary:hover{
    background:#f0cc57;
    transform:translateY(-2px);
}

.btn-outline{
    border:1px solid #d4af37;
    color:#d4af37;
}

.btn-outline:hover{
    background:#d4af37;
    color:#080a0d;
}

/* SECTIONS */

section{
    padding:90px 20px;
}

.container{
    max-width:1200px;
    margin:auto;
}

.section-title{
    text-align:center;
    margin-bottom:50px;
}

.section-title h2{
    font-size:40px;
    margin-bottom:10px;
}

.section-title p{
    color:#999;
}

/* PRODUCTS */

.products{
    background:#0d1014;
}

.product-grid{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:25px;
}

.product{
    background:#15191f;
    border:1px solid #252a31;
    border-radius:10px;
    overflow:hidden;
    transition:.35s;
}

.product:hover{
    transform:translateY(-8px);
    border-color:#d4af37;
}

.product-image{
    height:250px;
    background:
    linear-gradient(135deg,#1b2027,#090b0e);
    display:flex;
    align-items:center;
    justify-content:center;
    color:#777;
    font-size:18px;
}

.product-image img{
    width:100%;
    height:100%;
    object-fit:cover;
}

.product-info{
    padding:25px;
}

.product-info h3{
    color:#d4af37;
    font-size:23px;
    margin-bottom:10px;
}

.product-info p{
    color:#aaa;
    margin-bottom:20px;
}

/* FEATURES */

.features{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:25px;
}

.feature{
    padding:30px;
    background:#11151a;
    border:1px solid #252a31;
    border-radius:10px;
    text-align:center;
}

.feature-icon{
    font-size:42px;
    margin-bottom:15px;
}

.feature h3{
    margin-bottom:10px;
    color:#d4af37;
}

.feature p{
    color:#999;
}

/* ABOUT */

.about{
    background:#080a0d;
}

.about-grid{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:50px;
    align-items:center;
}

.about-text h2{
    font-size:42px;
    margin-bottom:20px;
}

.about-text p{
    color:#aaa;
    margin-bottom:18px;
}

.about-box{
    min-height:350px;
    border:1px solid #d4af37;
    border-radius:10px;
    display:flex;
    align-items:center;
    justify-content:center;
    background:
    radial-gradient(circle,rgba(212,175,55,.15),transparent 60%);
}

.about-box strong{
    font-size:35px;
    color:#d4af37;
}

/* CONTACT */

.contact{
    background:#0d1014;
}

.contact-grid{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:30px;
}

.contact-card{
    background:#15191f;
    padding:35px;
    border-radius:10px;
    border:1px solid #252a31;
}

.contact-card h3{
    color:#d4af37;
    margin-bottom:20px;
}

.contact-card p{
    color:#aaa;
    margin:12px 0;
}

.contact-card a{
    color:#fff;
    text-decoration:none;
}

.contact-card a:hover{
    color:#d4af37;
}

/* FOOTER */

footer{
    background:#050608;
    padding:40px 20px;
    text-align:center;
    border-top:1px solid #20242a;
}

footer .logo{
    margin-bottom:15px;
}

footer p{
    color:#777;
    font-size:14px;
}

.social{
    margin:20px 0;
}

.social a{
    color:#aaa;
    margin:0 10px;
    text-decoration:none;
}

.social a:hover{
    color:#d4af37;
}

/* WHATSAPP */

.whatsapp{
    position:fixed;
    right:20px;
    bottom:20px;
    width:58px;
    height:58px;
    border-radius:50%;
    background:#25d366;
    color:white;
    display:flex;
    align-items:center;
    justify-content:center;
    text-decoration:none;
    font-size:27px;
    z-index:999;
    box-shadow:0 5px 20px rgba(0,0,0,.4);
}

/* MOBILE */

@media(max-width:800px){

    nav{
        display:none;
        position:absolute;
        top:75px;
        left:0;
        width:100%;
        background:#080a0d;
        flex-direction:column;
        padding:25px;
        gap:20px;
        border-bottom:1px solid #333;
    }

    nav.active{
        display:flex;
    }

    .menu{
        display:block;
    }

    .product-grid,
    .features,
    .about-grid,
    .contact-grid{
        grid-template-columns:1fr;
    }

    section{
        padding:70px 18px;
    }

    .hero p{
        font-size:16px;
    }
}
</style>
</head>

<body>

<header>
<div class="navbar">

<div class="logo">
DETECTOR <span>PRO</span>
</div>

<div class="menu" onclick="toggleMenu()">☰</div>

<nav id="nav">
<a href="#home">Home</a>
<a href="#products">Products</a>
<a href="#technology">Technology</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>

</div>
</header>


<!-- HERO -->

<section class="hero" id="home">

<div class="hero-content">

<h1>
Discover What Lies <span class="gold">Beneath</span>
</h1>

<p>
Professional metal detection technology designed for treasure hunters,
prospectors and serious exploration.
</p>

<div class="buttons">

<a href="#products" class="btn btn-primary">
Explore Products
</a>

<a href="#contact" class="btn btn-outline">
Contact Us
</a>

</div>

</div>

</section>


<!-- PRODUCTS -->

<section class="products" id="products">

<div class="container">

<div class="section-title">

<h2>Our <span class="gold">Products</span></h2>

<p>
Advanced detection systems for professional exploration.
</p>

</div>


<div class="product-grid">


<div class="product">

<div class="product-image">
Product Image
</div>

<div class="product-info">

<h3>Professional Detector</h3>

<p>
Advanced metal detection system with high sensitivity and professional performance.
</p>

<a href="#contact" class="btn btn-outline">
Learn More
</a>

</div>

</div>


<div class="product">

<div class="product-image">
Product Image
</div>

<div class="product-info">

<h3>3D Ground Scanner</h3>

<p>
Explore underground structures and targets using advanced 3D scanning technology.
</p>

<a href="#contact" class="btn btn-outline">
Learn More
</a>

</div>

</div>


<div class="product">

<div class="product-image">
Product Image
</div>

<div class="product-info">

<h3>Deep Detection System</h3>

<p>
Professional equipment designed for deep underground exploration.
</p>

<a href="#contact" class="btn btn-outline">
Learn More
</a>

</div>

</div>


</div>
</div>

</section>


<!-- TECHNOLOGY -->

<section id="technology">

<div class="container">

<div class="section-title">

<h2>Advanced <span class="gold">Technology</span></h2>

<p>
Designed for precision, reliability and professional exploration.
</p>

</div>


<div class="features">

<div class="feature">

<div class="feature-icon">◉</div>

<h3>High Sensitivity</h3>

<p>
Advanced sensor technology helps detect small and deep targets.
</p>

</div>


<div class="feature">

<div class="feature-icon">⌁</div>

<h3>3D Visualization</h3>

<p>
Visualize underground signals using modern scanning technology.
</p>

</div>


<div class="feature">

<div class="feature-icon">◆</div>

<h3>Professional Design</h3>

<p>
Reliable equipment designed for demanding field conditions.
</p>

</div>

</div>

</div>

</section>


<!-- ABOUT -->

<section class="about" id="about">

<div class="container">

<div class="about-grid">

<div class="about-text">

<h2>
About <span class="gold">Us</span>
</h2>

<p>
We provide modern metal detection and underground exploration solutions
for users looking for reliable and professional equipment.
</p>

<p>
Our goal is to combine advanced technology with simple and practical
operation in the field.
</p>

<a href="#contact" class="btn btn-primary">
Contact Us
</a>

</div>


<div class="about-box">

<strong>DETECTOR PRO</strong>

</div>

</div>

</div>

</section>


<!-- CONTACT -->

<section class="contact" id="contact">

<div class="container">

<div class="section-title">

<h2>Contact <span class="gold">Us</span></h2>

<p>
We are ready to answer your questions.
</p>

</div>


<div class="contact-grid">

<div class="contact-card">

<h3>Get In Touch</h3>

<p>📧 Email:
<a href="mailto:info@example.com">
info@example.com
</a>
</p>

<p>📱 WhatsApp:
<a href="#">
+216 XX XXX XXX
</a>
</p>

<p>📍 Tunisia</p>

</div>


<div class="contact-card">

<h3>Professional Equipment</h3>

<p>
Interested in one of our detection systems?
Contact us for more information about products, specifications and availability.
</p>

<a href="mailto:info@example.com" class="btn btn-primary">
Send Email
</a>

</div>

</div>

</div>

</section>


<!-- FOOTER -->

<footer>

<div class="logo">
DETECTOR <span>PRO</span>
</div>

<div class="social">

<a href="#">Facebook</a>
<a href="#">Instagram</a>
<a href="#">YouTube</a>

</div>

<p>
© 2026 DETECTOR PRO. All Rights Reserved.
</p>

</footer>


<!-- WHATSAPP -->

<a class="whatsapp"
href="https://wa.me/216XXXXXXXX"
target="_blank">
✆
</a>


<script>

function toggleMenu(){

const nav = document.getElementById("nav");

nav.classList.toggle("active");

}

document.querySelectorAll("nav a").forEach(link => {

link.addEventListener("click", () => {

document.getElementById("nav").classList.remove("active");

});

});

</script>

</body>
</html>
