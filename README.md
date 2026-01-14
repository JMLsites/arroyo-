<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ARROYO GAME FARM</title>
  <style>
    :root {
      --black: #0b0b0b;
      --gold: #d4af37;
      --white: #ffffff;
    }
    * {margin:0; padding:0; box-sizing:border-box; font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;}
    body {background-color:var(--black); color:var(--white); line-height:1.6;}
    header {background: linear-gradient(90deg, #000000, #1a1a1a); border-bottom:2px solid var(--gold); padding:20px 40px; display:flex; justify-content:space-between; align-items:center;}
    header h1 {color:var(--gold); letter-spacing:3px; font-size:28px; display:flex; align-items:center;}
    nav a {color:var(--white); text-decoration:none; margin-left:20px; font-weight:500; transition:color 0.3s ease;}
    nav a:hover {color:var(--gold);}
    .logo {display:flex; align-items:center;}
    .logo img {height:50px; margin-right:10px;}
    .hero {padding:100px 40px; text-align:center; background: radial-gradient(circle at top, #1a1a1a, #000000);}
    .hero img {max-width:100%; height:auto; border-radius:12px; margin-bottom:20px;}
    .hero h2 {font-size:48px; color:var(--gold); margin-bottom:20px;}
    .hero p {max-width:700px; margin:0 auto 30px; font-size:18px; color:#f0f0f0;}
    .hero button {background-color:var(--gold); color:#000; border:none; padding:15px 35px; font-size:16px; font-weight:bold; cursor:pointer; border-radius:30px; transition: transform 0.3s ease, box-shadow 0.3s ease;}
    .hero button:hover {transform:translateY(-3px); box-shadow:0 8px 20px rgba(212, 175, 55, 0.4);}
    section {padding:80px 40px; max-width:1200px; margin:auto;}
    section h3 {color:var(--gold); font-size:32px; margin-bottom:20px; text-align:center;}
    .cards {display:grid; grid-template-columns:repeat(auto-fit, minmax(280px, 1fr)); gap:30px; margin-top:40px;}
    .card {background-color:#111111; border:1px solid var(--gold); padding:30px; border-radius:12px; text-align:center;}
    .card h4 {color:var(--gold); margin-bottom:15px; font-size:22px;}
    .card p {color:#e5e5e5; font-size:15px;}
    footer {background-color:#000000; border-top:2px solid var(--gold); text-align:center; padding:30px 20px; margin-top:60px;}
    footer p {color:#cccccc; font-size:14px;}
    footer span {color:var(--gold); font-weight:bold;}
  </style>
</head>
<body>

  <header>
    <h1 class="logo">
      <img src="AGF_rooster_logo.png" alt="AGF" /> ARROYO GAME FARM
    </h1>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Our Chickens</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <img src="hero_chickens.png" alt="Live Game Chickens" />
    <h2>Premium Live Game Chickens</h2>
    <p>ARROYO GAME FARM is dedicated to raising healthy, strong, and high-quality live game chickens using ethical breeding and proper care.</p>
    <button>Contact Us Today</button>
  </div>

  <section id="about">
    <h3>About Our Farm</h3>
    <p style="text-align:center; max-width:800px; margin:20px auto;">We specialize in breeding and raising live game chickens with attention to bloodline quality, nutrition, and environment. Our farm follows strict standards to ensure strong, active, and well-conditioned birds.</p>
  </section>

  <section id="services">
    <h3>What We Offer</h3>
    <div class="cards">
      <div class="card">
        <h4>Live Game Chickens</h4>
        <p>Carefully bred and raised live chickens known for strength, health, and endurance.</p>
      </div>
      <div class="card">
        <h4>Quality Bloodlines</h4>
        <p>We focus on maintaining trusted bloodlines with consistent performance and physical traits.</p>
      </div>
      <div class="card">
        <h4>Farm Direct</h4>
        <p>Direct-from-farm transactions ensuring transparency, freshness, and fair pricing.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h3>Get in Touch</h3>
    <p style="text-align:center; max-width:700px; margin:20px auto;">For inquiries, availability, and pricing, please contact us directly.</p>
    <p style="text-align:center; font-size:18px;">📞 Phone: <span style="color:var(--gold);">Your Number Here</span><br />📍 Location: <span style="color:var(--gold);">Your Location Here</span></p>
  </section>

  <footer>
    <p>© 2026 <span>ARROYO GAME FARM</span>. All Rights Reserved.</p>
  </footer>

</body>
</html>
