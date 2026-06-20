<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Contact - Vandhana Degree College</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:#0f172a;
    color:#fff;
}

.wrap{
    width:90%;
    max-width:1200px;
    margin:auto;
}

header{
    background:#111827;
    padding:20px 0;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:28px;
    font-weight:bold;
    color:#facc15;
}

nav ul{
    display:flex;
    list-style:none;
    gap:20px;
}

nav ul li a{
    text-decoration:none;
    color:white;
}

.hero{
    text-align:center;
    padding:60px 20px;
    background:linear-gradient(135deg,#1e3a8a,#0f766e);
}

.hero h1{
    font-size:45px;
}

.hero p{
    margin-top:10px;
    font-size:18px;
}

.contact-grid{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:30px;
    margin:50px 0;
}

.card{
    background:#1e293b;
    padding:25px;
    border-radius:12px;
}

.card h3{
    color:#facc15;
    margin-bottom:15px;
}

.card p{
    margin-bottom:10px;
}

input,
select,
textarea{
    width:100%;
    padding:12px;
    margin-top:8px;
    margin-bottom:18px;
    border:none;
    border-radius:8px;
}

button{
    width:100%;
    padding:14px;
    background:#f59e0b;
    color:white;
    border:none;
    border-radius:8px;
    font-size:16px;
    cursor:pointer;
}

button:hover{
    background:#d97706;
}

.info{
    display:flex;
    justify-content:center;
    gap:20px;
    flex-wrap:wrap;
    margin-bottom:50px;
}

.info-box{
    background:#1e293b;
    width:220px;
    text-align:center;
    padding:20px;
    border-radius:10px;
}

iframe{
    width:100%;
    height:300px;
    border:none;
}

footer{
    background:#111827;
    text-align:center;
    padding:20px;
    margin-top:40px;
}

@media(max-width:768px){

.contact-grid{
grid-template-columns:1fr;
}

.hero h1{
font-size:32px;
}

}
</style>

</head>

<body>

<header>

<div class="wrap">

<nav>

<div class="logo">Vadhana Degree College</div>

<ul>
<li><a href="#">Home</a></li>
<li><a href="#">Student Records</a></li>
<li><a href="#">About</a></li>
<li><a href="#">Contact</a></li>
</ul>

</nav>

</div>

</header>

<section class="hero">

<h1>Welcome to Vadhana Degree College</h1>

<p>Admissions, Student Support and General Enquiries</p>

</section>

<div class="wrap">

<div class="info">

<div class="info-box">
<h2>5000+</h2>
<p>Students</p>
</div>

<div class="info-box">
<h2>100+</h2>
<p>Faculty</p>
</div>

<div class="info-box">
<h2>25+</h2>
<p>Years of Excellence</p>
</div>

</div>

<div class="contact-grid">

<div class="card">

<h3>Contact Information</h3>

<p><b>Address:</b><br>
Vadhana Degree College<br>
odisha, andhra pradesh<br>
Andhra Pradesh - 533004
</p>

<p><b>Phone:</b> +91 7981677241</p>

<p><b>Email:</b> info@vadhanadegreecollege.edu.in</p>

<p><b>Office Hours:</b><br>
Monday - Saturday<br>
9:30 AM - 4:30 PM
</p>

</div>

<div class="card">

<h3>Send a Message</h3>

<form id="contactForm">

<label>Full Name</label>
<input type="text" required>

<label>Phone Number</label>
<input type="tel">

<label>Email</label>
<input type="email" required>

<label>Reason</label>

<select>
<option>Admissions</option>
<option>Attendance</option>
<option>Student Support</option>
<option>General Enquiry</option>
</select>

<label>Message</label>

<textarea rows="5"></textarea>

<button type="submit">Send Message</button>

</form>

</div>

</div>

<iframe src="https://maps.app.goo.gl/FRNYAHPPmHnSo4wR8?g_st=ac"></iframe>

</div>

<footer>

<p>©️ 2026 Vadhana Degree College</p>

<p>Designed for Student Management Demo</p>

</footer>

<script>

document.getElementById("contactForm").addEventListener("submit",function(e){

e.preventDefault();

alert("Thank you! Your message has been submitted successfully.");

this.reset();

});

</script>

</body>
</html>
