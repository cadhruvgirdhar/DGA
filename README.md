<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dhruv Girdhar & Associates | Tax & Accounting Services in Hisar</title>
<meta name="description" content="Dhruv Girdhar & Associates provides GST Return, TDS Return and Income Tax Return services in Hisar, Haryana.">
<meta name="keywords" content="Dhruv Girdhar Associates, GST Consultant Hisar, TDS Consultant Hisar, Income Tax Consultant Hisar">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{font-family:Inter,sans-serif;color:#172033;background:#f8fafc;line-height:1.6}
a{text-decoration:none;color:inherit}
.container{width:min(1120px,92%);margin:auto}
header{position:sticky;top:0;z-index:1000;background:rgba(255,255,255,.96);backdrop-filter:blur(12px);border-bottom:1px solid #e5e7eb}
.navbar{min-height:76px;display:flex;align-items:center;justify-content:space-between;gap:25px}
.brand{display:flex;align-items:center;gap:12px}
.brand-logo{width:46px;height:46px;border-radius:10px;object-fit:contain;display:block}
.brand-text strong{display:block;font-size:17px;color:#123c69}
.brand-text span{font-size:11px;color:#64748b;letter-spacing:1px;text-transform:uppercase}
nav{display:flex;gap:28px;align-items:center}
nav a{font-size:14px;font-weight:600;color:#334155}
nav a:hover{color:#123c69}
.nav-btn{padding:11px 18px;border-radius:8px;background:#123c69;color:#fff!important}

.hero{background:linear-gradient(120deg,#0d2f50 0%,#164f80 100%);color:#fff;padding:95px 0 85px;position:relative;overflow:hidden}
.hero-grid{display:grid;grid-template-columns:1.25fr .75fr;gap:60px;align-items:center;position:relative;z-index:1}
.badge{display:inline-flex;padding:7px 13px;border-radius:30px;background:rgba(255,255,255,.12);border:1px solid rgba(255,255,255,.2);font-size:13px;margin-bottom:20px}
.hero h1{font-family:"Playfair Display",serif;font-size:clamp(42px,5vw,68px);line-height:1.05;margin-bottom:22px}
.hero h1 span{color:#d8eaff}
.hero p{max-width:650px;color:#dce9f5;font-size:17px;margin-bottom:30px}
.hero-buttons{display:flex;gap:14px;flex-wrap:wrap}
.btn{padding:13px 21px;border-radius:8px;font-weight:700;display:inline-flex;align-items:center;justify-content:center}
.btn-primary{background:#fff;color:#123c69}.btn-outline{border:1px solid rgba(255,255,255,.5);color:#fff}

.rating-card{background:#fff;color:#172033;border-radius:18px;padding:32px;box-shadow:0 25px 60px rgba(0,0,0,.18)}
.rating-number{font-size:52px;font-weight:800;color:#123c69;line-height:1}
.stars{color:#f59e0b;font-size:24px;letter-spacing:2px;margin:10px 0}
.rating-card p{color:#64748b;margin:0;font-size:14px}
.rating-divider{height:1px;background:#e5e7eb;margin:24px 0}
.experience{display:flex;justify-content:space-between;gap:20px}
.experience strong{display:block;font-size:28px;color:#123c69}.experience span{font-size:13px;color:#64748b}

section{padding:85px 0}
.section-heading{text-align:center;max-width:700px;margin:0 auto 50px}
.eyebrow{text-transform:uppercase;letter-spacing:2px;color:#2563eb;font-size:12px;font-weight:800;margin-bottom:10px}
.section-heading h2,.about-text h2{font-family:"Playfair Display",serif;color:#102a43}
.section-heading h2{font-size:clamp(32px,4vw,45px);margin-bottom:12px}
.section-heading p,.about-text p{color:#64748b}

.about-grid{display:grid;grid-template-columns:1fr 1fr;gap:60px;align-items:center}
.about-text h2{font-size:42px;margin-bottom:20px}.about-text p{margin-bottom:18px}
.info-box{display:flex;gap:15px;padding:18px;background:#fff;border:1px solid #e5e7eb;border-radius:12px;margin-top:20px}
.info-icon{width:42px;height:42px;border-radius:9px;background:#e8f1fb;color:#123c69;display:grid;place-items:center;font-size:14px;font-weight:800;flex-shrink:0}
.info-box strong{display:block;color:#172033;margin-bottom:3px}.info-box span{font-size:14px;color:#64748b}

.services,.reviews{background:#fff}
.service-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:22px}
.service-card{padding:30px;background:#f8fafc;border:1px solid #e5e7eb;border-radius:15px;transition:.25s}
.service-card:hover{transform:translateY(-5px);box-shadow:0 15px 35px rgba(15,23,42,.08)}
.service-icon{width:50px;height:50px;display:grid;place-items:center;border-radius:11px;background:#123c69;color:#fff;font-weight:800;margin-bottom:20px}
.service-card h3{font-size:19px;margin-bottom:9px}.service-card p{color:#64748b;font-size:14px}

.why-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:18px}
.why-card{background:#fff;padding:27px 22px;border-radius:14px;border:1px solid #e5e7eb;text-align:center}
.why-card strong{display:block;margin-bottom:8px;color:#123c69}.why-card p{color:#64748b;font-size:13px}

.reviews{background:#f1f5f9}
.review-card{max-width:700px;margin:auto;background:#fff;padding:35px;border-radius:17px;text-align:center;border:1px solid #e5e7eb}
.review-card h3{color:#123c69;margin-bottom:10px}.review-card p{color:#64748b;font-size:15px}
.review-note{font-size:12px!important;margin-top:20px}

.contact-grid{display:grid;grid-template-columns:.9fr 1.1fr;gap:30px}
.contact-card{background:#123c69;color:#fff;padding:40px;border-radius:17px}
.contact-card h2{font-family:"Playfair Display",serif;font-size:36px;margin-bottom:20px}
.contact-item{margin:23px 0}.contact-item small{display:block;color:#a9c8e3;text-transform:uppercase;letter-spacing:1px;margin-bottom:5px}.contact-item p{color:#fff}
.map{min-height:400px;border-radius:17px;overflow:hidden;background:#dbeafe}
.map iframe{width:100%;height:100%;min-height:400px;border:0}
.map-link{display:block;width:100%;height:100%;cursor:pointer}
.maps-btn{display:inline-flex;align-items:center;justify-content:center;margin-top:8px;padding:12px 18px;border-radius:9px;background:#fff;color:#123c69;font-weight:700;font-size:14px;border:1px solid rgba(255,255,255,.25);transition:.25s}
.maps-btn:hover{transform:translateY(-2px);background:#f8fafc}

footer{background:#0b1f33;color:#cbd5e1;padding:35px 0}
.footer-content{display:flex;justify-content:space-between;gap:20px;align-items:center}
.footer-content strong{color:#fff}.footer-content p{font-size:13px}

@media(max-width:850px){
nav{display:none}.hero{padding:70px 0}.hero-grid,.about-grid,.contact-grid{grid-template-columns:1fr}
.hero h1{font-size:44px}.service-grid{grid-template-columns:1fr 1fr}.why-grid{grid-template-columns:1fr 1fr}
}
@media(max-width:560px){
section{padding:65px 0}.brand-text strong{font-size:14px}.brand-text span{font-size:9px}
.brand-logo{width:40px;height:40px;object-fit:contain}.hero h1{font-size:38px}.hero p{font-size:15px}
.hero-buttons{flex-direction:column}.btn{width:100%}.service-grid,.why-grid{grid-template-columns:1fr}
.about-text h2{font-size:34px}.contact-card{padding:28px}.footer-content{flex-direction:column;text-align:center}
}
</style>
</head>

<body>
<header>
<div class="container navbar">
<a href="#" class="brand">
<img src="logo.jpeg" alt="Dhruv Girdhar &amp; Associates Logo" class="brand-logo">
<div class="brand-text"><strong>Dhruv Girdhar &amp; Associates</strong><span>Tax &amp; Accounting Professionals</span></div>
</a>
<nav>
<a href="#about">About</a><a href="#services">Services</a><a href="#reviews">Reviews</a><a href="#contact">Contact</a>
<a class="nav-btn" href="#contact">Get in Touch</a>
</nav>
</div>
</header>

<section class="hero">
<div class="container hero-grid">
<div>
<div class="badge">★ 5.0 Rated on Justdial</div>
<h1>Dhruv Girdhar <span>&amp; Associates</span></h1>
<p>Professional tax, GST and accounting support for individuals and businesses in Hisar, Haryana.</p>
<div class="hero-buttons">
<a href="#contact" class="btn btn-primary">Contact Us</a>
<a href="#services" class="btn btn-outline">Explore Services</a>
</div>
</div>
<div class="rating-card">
<div class="rating-number">5.0</div>
<div class="stars">★★★★★</div>
<p>Customer Rating on Justdial</p>
<div class="rating-divider"></div>
<div class="experience">
<div><strong>38+</strong><span>Years in Business</span></div>
<div><strong>3</strong><span>Justdial Reviews</span></div>
</div>
</div>
</div>
</section>

<section id="about">
<div class="container about-grid">
<div class="about-text">
<div class="eyebrow">About Us</div>
<h2>Trusted Professional Support for Your Financial Needs</h2>
<p>Dhruv Girdhar &amp; Associates is a professional tax and accounting service provider based in Hisar, Haryana.</p>
<p>The firm is listed on Justdial with a 5.0 rating and provides services including GST Returns, TDS Returns and Income Tax Returns.</p>
<div class="info-box"><div class="info-icon">✓</div><div><strong>Established Professional Presence</strong><span>38 years in business as listed on Justdial.</span></div></div>
</div>
<div>
<div class="info-box"><div class="info-icon">GST</div><div><strong>GST Return Services</strong><span>Assistance with GST return related compliance and filing.</span></div></div>
<div class="info-box"><div class="info-icon">TDS</div><div><strong>TDS Return Services</strong><span>Professional assistance with TDS return compliance.</span></div></div>
<div class="info-box"><div class="info-icon">IT</div><div><strong>Income Tax Return Services</strong><span>Assistance with income tax return related requirements.</span></div></div>
</div>
</div>
</section>

<section id="services" class="services">
<div class="container">
<div class="section-heading"><div class="eyebrow">Our Services</div><h2>Professional Tax &amp; Compliance Services</h2><p>Services listed for Dhruv Girdhar &amp; Associates on Justdial.</p></div>
<div class="service-grid">
<div class="service-card"><div class="service-icon">GST</div><h3>GST Returns</h3><p>Professional assistance with GST return preparation and compliance requirements.</p></div>
<div class="service-card"><div class="service-icon">TDS</div><h3>TDS Returns</h3><p>Support for TDS return related filing and compliance requirements.</p></div>
<div class="service-card"><div class="service-icon">IT</div><h3>Income Tax Returns</h3><p>Assistance with income tax return preparation and filing requirements.</p></div>
</div>
</div>
</section>

<section>
<div class="container">
<div class="section-heading"><div class="eyebrow">Why Choose Us</div><h2>Built on Experience &amp; Professional Service</h2></div>
<div class="why-grid">
<div class="why-card"><strong>38+ Years</strong><p>Long-standing professional presence, as listed on Justdial.</p></div>
<div class="why-card"><strong>5.0 Rating</strong><p>A 5.0 customer rating is displayed on the Justdial listing.</p></div>
<div class="why-card"><strong>Tax Expertise</strong><p>Services include GST, TDS and Income Tax Returns.</p></div>
<div class="why-card"><strong>Local Presence</strong><p>Conveniently located at Old Court Complex, Lajpat Nagar, Hisar.</p></div>
</div>
</div>
</section>

<section id="reviews" class="reviews">
<div class="container">
<div class="section-heading"><div class="eyebrow">Client Reviews</div><h2>Rated 5.0 on Justdial</h2><p>Customer rating information displayed on the firm's Justdial listing.</p></div>
<div class="review-card">
<div class="stars">★★★★★</div><h3>5.0 / 5.0</h3>
<p>Dhruv Girdhar &amp; Associates has a 5.0 rating based on 3 reviews on Justdial.</p>
<p class="review-note">Individual review text has not been reproduced here because the complete review content was not available from the accessible listing data.</p>
</div>
</div>
</section>

<section id="contact">
<div class="container contact-grid">
<div class="contact-card">
<div class="eyebrow">Visit Us</div>
<h2>Let's Discuss Your Requirements</h2>
<div class="contact-item"><small>Address</small><p>SCO 135, Old Court Complex,<br>Lajpat Nagar,<br>Hisar – 125001, Haryana</p></div>
<div class="contact-item"><small>Landmark</small><p>Near Laziz Hotel</p></div>
<div class="contact-item"><small>Location</small><p>Hisar, Haryana</p></div>
<a href="https://www.google.com/maps/place/Dhruv+Girdhar+%26+Associates/@29.1469786,75.7166257,17z/data=!3m1!4b1!4m6!3m5!1s0x391233541819760b:0x193d49df331aa8ea!8m2!3d29.146974!4d75.7214966!16s%2Fg%2F11fnw9qjpr?hl=en-IN&entry=ttu&g_ep=EgoyMDI2MDkwMS4wIKXMDSoASAFQAw%3D%3D" target="_blank" rel="noopener noreferrer" class="maps-btn">📍 View on Google Maps</a>
</div>
<div class="map">
<a href="https://www.google.com/maps/place/Dhruv+Girdhar+%26+Associates/@29.1469786,75.7166257,17z/data=!3m1!4b1!4m6!3m5!1s0x391233541819760b:0x193d49df331aa8ea!8m2!3d29.146974!4d75.7214966!16s%2Fg%2F11fnw9qjpr?hl=en-IN&entry=ttu&g_ep=EgoyMDI2MDkwMS4wIKXMDSoASAFQAw%3D%3D" target="_blank" rel="noopener noreferrer" class="map-link" aria-label="Open Dhruv Girdhar & Associates on Google Maps">
<iframe src="https://www.google.com/maps?q=Dhruv%20Girdhar%20%26%20Associates%2C%20Hisar%2C%20Haryana&output=embed" loading="lazy" allowfullscreen></iframe>
</a>
</div>
</div>
</section>

<footer>
<div class="container footer-content">
<p>© 2026 <strong>Dhruv Girdhar &amp; Associates</strong>. All Rights Reserved.</p>
<p>Hisar, Haryana</p>
</div>
</footer>
</body>
</html>
