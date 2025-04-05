<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Careervis- Your Career, Our Mission</title>
  <style>
    * { box-sizing: border-box; }
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f5f7fa; }
    header { background: #0a3d62; color: white; padding: 20px 0; text-align: center; }
    nav a { color: white; margin: 0 10px; text-decoration: none; font-weight: bold; font-size: 1rem; }
    .hero { text-align: center; padding: 60px 20px; background: #f1f2f6; }
    .hero h1 { font-size: 2.5rem; color: #0a3d62; margin-bottom: 20px; }
    .hero p { font-size: 1.1rem; color: #333; max-width: 600px; margin: auto; }
    .sections { display: flex; flex-wrap: wrap; justify-content: center; margin: 40px 10px; }
    .card { background: white; border-radius: 10px; box-shadow: 0 2px 10px rgba(0,0,0,0.1); margin: 15px; padding: 25px; flex: 1 1 300px; max-width: 320px; text-align: center; transition: transform 0.2s ease-in-out; }
    .card:hover { transform: scale(1.03); }
    .card h3 { color: #0a3d62; margin-bottom: 15px; }
    .card p { color: #555; }
    footer { background: #0a3d62; color: white; text-align: center; padding: 20px 10px; font-size: 0.9rem; }
    @media (max-width: 600px) {
      nav a { display: block; margin: 10px 0; font-size: 1rem; }
      .hero h1 { font-size: 2rem; }
      .hero p { font-size: 1rem; padding: 0 10px; }
    }
  </style>
</head>
<body>
  <header>
    <h1>Careervis</h1>
    <nav>
      <a href="#education">Education</a>
      <a href="#jobs">Job Consultancy</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Welcome to Careervis</h1>
    <p>Your trusted partner for computer education, skill development, and job placement services. Let us help you shape your future.</p>
  </section>

  <section class="sections" id="education">
    <div class="card">
      <h3>Computer Education</h3>
      <p>Learn essential computer skills with certified courses like DCA, ADCA, Tally, and more.</p>
    </div>
    <div class="card">
      <h3>Skill Development</h3>
      <p>Get industry-ready with soft skills training, personality development, and interview preparation.</p>
    </div>
    <div class="card" id="jobs">
      <h3>Job Consultancy</h3>
      <p>Find the right job with our expert guidance and placement support for freshers and professionals.</p>
    </div>
  </section>

  <footer id="contact">
    <p>Contact us at <strong>info@Careervis.in</strong> | Follow us on Instagram & Facebook: @Careerviss.in</p>
    <p>&copy; 2025 Careervis. All rights reserved.</p>
  </footer>
</body>
</html>
