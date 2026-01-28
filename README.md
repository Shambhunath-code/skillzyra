<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Skillzyra – Learn. Earn. Grow</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #0f172a;
      color: #e5e7eb;
    }
    header {
      background: linear-gradient(135deg, #2563eb, #9333ea);
      padding: 40px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 42px;
    }
    header p {
      font-size: 18px;
      margin-top: 10px;
    }
    section {
      padding: 40px 20px;
      max-width: 1100px;
      margin: auto;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: #1e293b;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.3);
    }
    .card h3 {
      margin-top: 0;
      color: #60a5fa;
    }
    .btn {
      display: inline-block;
      margin-top: 15px;
      padding: 10px 20px;
      background: #2563eb;
      color: white;
      text-decoration: none;
      border-radius: 6px;
    }
    .btn:hover {
      background: #1d4ed8;
    }
    footer {
      background: #020617;
      text-align: center;
      padding: 20px;
      font-size: 14px;
      color: #9ca3af;
    }
  </style>
</head>

<body>

<header>
  <h1>Skillzyra</h1>
  <p>Learn. Earn. Grow | CV Making, Digital Help & Skill Guides</p>
</header>

<section>
  <h2>What We Offer</h2>
  <div class="cards">

    <div class="card">
      <h3>Professional CV Making</h3>
      <p>Fresher & Experienced candidates ke liye ATS-friendly CVs.</p>
      <a class="btn" href="Sample_Fresher_CV.pdf">View Sample</a>
    </div>

    <div class="card">
      <h3>Experienced CV Samples</h3>
      <p>Industry-ready CVs jo interviews clear karne me madad kare.</p>
      <a class="btn" href="Sample_Experienced_CV.pdf">View Sample</a>
    </div>

    <div class="card">
      <h3>Digital Help & Guides</h3>
      <p>Online forms, job apply, GitHub, websites & digital skills support.</p>
      <a class="btn" href="#">Coming Soon</a>
    </div>

  </div>
</section>

<section>
  <h2>Why Skillzyra?</h2>
  <ul>
    <li>✔ Simple & professional designs</li>
    <li>✔ Beginner-friendly guidance</li>
    <li>✔ Affordable & practical solutions</li>
  </ul>
</section>

<footer>
  © 2026 Skillzyra | Built with ❤️ using GitHub Pages
</footer>

</body>
</html>
