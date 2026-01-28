<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Skillzyra – Learn. Earn. Grow</title>

<style>
body{
  margin:0;
  font-family:Arial, Helvetica, sans-serif;
  background:#0f172a;
  color:#e5e7eb;
}
header{
  background:linear-gradient(135deg,#2563eb,#9333ea);
  padding:50px 20px;
  text-align:center;
}
header h1{margin:0;font-size:44px;}
header p{font-size:18px;margin-top:10px;}

section{
  padding:40px 20px;
  max-width:1100px;
  margin:auto;
}

.cards{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:20px;
}

.card{
  background:#1e293b;
  padding:25px;
  border-radius:14px;
  box-shadow:0 10px 25px rgba(0,0,0,.4);
}

.card h3{margin-top:0;color:#60a5fa;}

.btn{
  display:inline-block;
  margin-top:15px;
  padding:10px 22px;
  background:#2563eb;
  color:white;
  text-decoration:none;
  border-radius:6px;
  font-weight:bold;
}
.btn:hover{background:#1d4ed8;}

.price{
  font-size:22px;
  color:#34d399;
  margin-top:10px;
}

footer{
  background:#020617;
  text-align:center;
  padding:20px;
  font-size:14px;
  color:#9ca3af;
}

/* WhatsApp Button */
.whatsapp{
  position:fixed;
  bottom:20px;
  right:20px;
  background:#25D366;
  color:white;
  padding:14px 18px;
  border-radius:50px;
  font-weight:bold;
  text-decoration:none;
  box-shadow:0 5px 20px rgba(0,0,0,.4);
}
</style>
</head>

<body>

<header>
  <h1>Skillzyra</h1>
  <p>Learn. Earn. Grow | CV Making, Digital Help & Skill Guides</p>
</header>

<section>
<h2>Our Services</h2>
<div class="cards">

<div class="card">
<h3>Resume / CV Making</h3>
<p>ATS-friendly professional CVs for Freshers & Experienced.</p>
<p class="price">₹30 – ₹50 only</p>
<a class="btn" href="Sample_Fresher_CV.pdf">View Sample</a>
</div>

<div class="card">
<h3>Photo Editing & Instagram Help</h3>
<p>Profile photo enhancement, basic edits & social help.</p>
<a class="btn" href="#">Coming Soon</a>
</div>

<div class="card">
<h3>Online Form & Digital Help</h3>
<p>Job forms, admissions, accounts & digital support.</p>
<a class="btn" href="#">Coming Soon</a>
</div>

<div class="card">
<h3>Skill + Job Guides</h3>
<p>Beginner-friendly guides to learn skills & earn online.</p>
<a class="btn" href="#">Coming Soon</a>
</div>

</div>
</section>

<section>
<h2>Why Skillzyra?</h2>
<ul>
<li>✔ Affordable services</li>
<li>✔ Simple & clean designs</li>
<li>✔ Beginner-friendly guidance</li>
<li>✔ Fast WhatsApp support</li>
</ul>
</section>

<footer>
© 2026 Skillzyra | Built with ❤️ using GitHub Pages
</footer>

<!-- WhatsApp -->
<a class="whatsapp" 
href="https://wa.me/917008956984" 
target="_blank">
💬 WhatsApp
</a>

</body>
</html>
