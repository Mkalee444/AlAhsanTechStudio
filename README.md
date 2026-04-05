<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Al-Ahsan Tech Studio</title>  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f5f7fa;
      color: #333;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 40px;
      background: #0f172a;
      color: white;
      position: sticky;
      top: 0;
    }

    header img {
      height: 40px;
      border-radius: 32px
    }

    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: #38bdf8;
    }

    .hero {
      text-align: center;
      padding: 100px 20px;
      background: linear-gradient(to right, #1e3a8a, #2563eb);
      color: white;
    }

    .hero h1 {
      font-size: 40px;
      margin-bottom: 10px;
    }

    .hero button {
      margin-top: 20px;
      padding: 12px 25px;
      border: none;
      background: white;
      color: #1e3a8a;
      border-radius: 6px;
      cursor: pointer;
    }

    section {
      padding: 60px 20px;
      text-align: center;
    }

    .branches, .fields {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .contact {
      background: #1e3a8a;
      color: white;
    }

    footer {
      background: #020617;
      color: white;
      text-align: center;
      padding: 15px;
    }

  </style></head>
<body>  <!-- HEADER -->  <header>
    <div>
      <img src="C:\Users\hp\Pictures\AhsanTechLogo.jpg" alt="Logo">
    </div>
    <nav>
      <a href="#">Home</a>
      <a href="#about">About</a>
      <a href="#branches">Branches</a>
      <a href="#fields">Fields</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>  <!-- HERO -->  <div class="hero">
    <h1>AL-AHSAN TECH STUDIO</h1>
    <p>Highlighting Tech Sectors & Training Future Innovators</p>
    <button onclick="showMessage()">Get Started</button>
  </div>  <!-- ABOUT -->  <section id="about">
    <h2>About Us</h2>
    <p>We are a tech media and training studio showcasing Cybersecurity, AI, Software Engineering and more.</p>
  </section>  <!-- BRANCHES -->  <section id="branches">
    <h2>Our Branches</h2>
    <div class="branches">
      <div class="card">
        <h3>Media & Awareness</h3>
        <p>We create banners and educational content for tech awareness.</p>
      </div>
      <div class="card">
        <h3>Training & Development</h3>
        <p>We train students in coding and modern technologies.</p>
      </div>
    </div>
  </section>  <!-- FIELDS -->  <section id="fields">
    <h2>Tech Fields</h2>
    <div class="fields">
      <div class="card">Cyber Security</div>
      <div class="card">Software Engineering</div>
      <div class="card">Information Technology</div>
      <div class="card">Computer Science</div>
      <div class="card">Artificial Intelligence</div>
    </div>
  </section>  <!-- CONTACT -->  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>Email: lawalumarkalee@gmail.com </p>
    <p>Phone: +234 9018294373 </p>
  </section>  <!-- FOOTER -->  <footer>
    <p>© 2026 Al-Ahsan Tech Studio</p>
  </footer>  <!-- JAVASCRIPT -->  <script>
    function showMessage() {
      alert("Welcome to Al-Ahsan Tech Studio ");
    }
  </script></body>
</html>






