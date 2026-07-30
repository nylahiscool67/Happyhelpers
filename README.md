# Happyhelpers
# Happyhelper
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Helper | Babysitting & Errands</title>

<link rel="stylesheet" href="style.css">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap" rel="stylesheet">

</head>

<body>

<header>

<div class="logo">
Happy Helper
</div>

<nav>

<a href="#services">Services</a>
<a href="#about">About</a>
<a href="#share">Share</a>
<a href="#contact">Contact</a>

</nav>

<a href="#contact" class="hire-btn">Hire Me</a>

</header>

<section class="hero">

<div class="badge">
Based in E10 Leyton, London
</div>

<h1>

Welcome to
<span>Happy Helper</span>

</h1>

<p>

I offer babysitting and local errands —
all with genuine care and a big smile.

</p>

<div class="buttons">

<a href="#services" class="primary">
See My Services
</a>

<a href="#contact" class="secondary">
Get in Touch
</a>

</div>

<div class="tags">

<span>Reliable</span>
<span>Caring</span>
<span>Creative</span>
<span>Trustworthy</span>
<span>Local</span>

</div>

</section>

<section id="services">

<h2>What I Do</h2>

<p class="subtitle">
Done with care, every time
</p>

<div class="cards">

<div class="card blue">

<h3>🛍️ Errands</h3>

<p>

Need a hand with everyday tasks?
I can help with:

</p>

<ul>

<li>Trips to the shop</li>
<li>Collecting parcels</li>
<li>Posting letters</li>
<li>Other local errands</li>

</ul>

</div>

<div class="card peach">

<h3>🧸 Babysitting</h3>

<p>

Available for children aged
3–11.

Fun, safe and engaging childcare.

</p>

<ul>

<li>Phonics help</li>
<li>Reading practice</li>
<li>Storytelling</li>
<li>Craft club</li>
<li>Baking</li>
<li>Arts & Crafts</li>
<li>Homework help</li>
<li>Evenings & Weekends</li>

</ul>

</div>

</div>

</section>

<section class="prices">

<h2>Babysitting Rates</h2>

<div class="price-grid">

<div class="price-card">

<h3>£8</h3>

<p>per hour</p>

<strong>1 CHILD</strong>

</div>

<div class="price-card">

<h3>£14</h3>

<p>per hour</p>

<strong>2 CHILDREN</strong>

</div>

<div class="price-card green">

<h3>Get in Touch</h3>

<p>per hour</p>

<strong>3+ CHILDREN</strong>

</div>

</div>

</section>

<section class="discount">

🎉 <strong>10% off your first booking!</strong>

<p>

Mention it when you email me.

</p>

</section>

<section id="contact">

<h2>Hire Me</h2>

<p>

Interested in one of my services?

I'd love to hear from you!

</p>

<a class="email"

href="mailto:bookhappyhelper@yahoo.com">

📧 bookhappyhelper@yahoo.com

</a>

<p class="small">

Click the email above to send me a message.

</p>

</section>

<footer>

<p>

Happy Helper — E10 Leyton, London

</p>

</footer>

<script src="script.js"></script>

</body>
</html>
*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
}

body{
font-family:'Poppins',sans-serif;
background:#fff9f4;
color:#333;
line-height:1.6;
}

header{
position:sticky;
top:0;
background:white;
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 8%;
box-shadow:0 5px 20px rgba(0,0,0,.08);
z-index:1000;
}

.logo{
font-size:28px;
font-weight:700;
color:#ff7a00;
}

nav{
display:flex;
gap:25px;
}

nav a{
text-decoration:none;
color:#444;
font-weight:600;
transition:.3s;
}

nav a:hover{
color:#ff7a00;
}

.hire-btn{
background:#ff7a00;
color:white;
padding:12px 22px;
border-radius:50px;
text-decoration:none;
font-weight:600;
transition:.3s;
}

.hire-btn:hover{
background:#e86800;
transform:translateY(-2px);
}

.hero{
padding:90px 10%;
text-align:center;
background:linear-gradient(135deg,#fff5ea,#ffe2bf);
}

.badge{
display:inline-block;
background:white;
padding:10px 18px;
border-radius:40px;
font-size:14px;
box-shadow:0 5px 20px rgba(0,0,0,.08);
margin-bottom:25px;
}

.hero h1{
font-size:58px;
margin-bottom:20px;
}

.hero h1 span{
color:#ff7a00;
}

.hero p{
font-size:20px;
max-width:700px;
margin:auto;
}

.buttons{
margin-top:35px;
display:flex;
justify-content:center;
gap:18px;
flex-wrap:wrap;
}

.primary,
.secondary{
padding:14px 28px;
border-radius:50px;
text-decoration:none;
font-weight:600;
transition:.3s;
}

.primary{
background:#ff7a00;
color:white;
}

.secondary{
background:white;
color:#ff7a00;
border:2px solid #ff7a00;
}

.primary:hover,
.secondary:hover{
transform:translateY(-3px);
}

.tags{
display:flex;
justify-content:center;
gap:12px;
margin-top:35px;
flex-wrap:wrap;
}

.tags span{
background:white;
padding:10px 18px;
border-radius:30px;
box-shadow:0 5px 15px rgba(0,0,0,.08);
}

section{
padding:80px 10%;
}

h2{
text-align:center;
font-size:40px;
margin-bottom:10px;
}

.subtitle{
text-align:center;
margin-bottom:40px;
color:#777;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:30px;
}

.card{
background:white;
padding:35px;
border-radius:25px;
box-shadow:0 10px 25px rgba(0,0,0,.08);
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
}

.blue{
border-top:6px solid #4aa8ff;
}

.peach{
border-top:6px solid #ffb167;
}

.card h3{
margin-bottom:18px;
font-size:28px;
}

.card ul{
margin-top:15px;
padding-left:20px;
}

.card li{
margin:8px 0;
}

.prices{
background:#fff;
}

.price-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:25px;
margin-top:40px;
}

.price-card{
background:#fff9f4;
padding:35px;
text-align:center;
border-radius:25px;
box-shadow:0 10px 20px rgba(0,0,0,.08);
}

.price-card h3{
font-size:42px;
color:#ff7a00;
}

.green h3{
color:#2fa84f;
}

.discount{
background:#ffedd9;
text-align:center;
border-radius:25px;
margin:40px 10%;
padding:40px;
font-size:22px;
}

#contact{
text-align:center;
background:white;
}

.email{
display:inline-block;
margin-top:30px;
background:#ff7a00;
color:white;
text-decoration:none;
padding:18px 30px;
border-radius:50px;
font-size:22px;
font-weight:700;
transition:.3s;
}

.email:hover{
background:#e86b00;
transform:scale(1.05);
}

.small{
margin-top:20px;
color:#666;
}

footer{
background:#222;
color:white;
text-align:center;
padding:30px;
margin-top:50px;
}

@media(max-width:768px){

header{
flex-direction:column;
gap:15px;
}

nav{
flex-wrap:wrap;
justify-content:center;
}

.hero h1{
font-size:40px;
}

.buttons{
flex-direction:column;
align-items:center;
}

h2{
font-size:32px;
}

.email{
font-size:18px;
padding:15px 22px;
}

}
// Smooth fade-in animation

const observer = new IntersectionObserver((entries) => {
  entries.forEach((entry) => {
    if (entry.isIntersecting) {
      entry.target.classList.add("show");
    }
  });
});

document.querySelectorAll("section").forEach((section) => {
  section.classList.add("hidden");
  observer.observe(section);
});

// Button hover effect

document.querySelectorAll("a").forEach((button) => {
  button.addEventListener("mouseenter", () => {
    button.style.transition = "0.3s";
  });
});

// Current year in footer (optional)

const footer = document.querySelector("footer p");

if (footer) {
  footer.innerHTML =
    `© ${new Date().getFullYear()} Happy Helper • E10 Leyton, London`;
}

// Welcome message

window.addEventListener("load", () => {
  console.log("Happy Helper website loaded!");
});
