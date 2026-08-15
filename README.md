<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tillu Hackathon Portfolio</title>
  <style>
    *{margin:0;padding:0;box-sizing:border-box;font-family:Arial,sans-serif;}
    body{background:#0f172a;color:white;line-height:1.6;}
    header{background:#1e293b;padding:20px;text-align:center;}
    nav a{color:white;margin:0 15px;text-decoration:none;font-weight:bold;}
    section{padding:40px 20px;max-width:900px;margin:auto;}
    .hero{text-align:center;padding:60px 20px;}
    .card{background:#1e293b;padding:20px;margin:20px 0;border-radius:12px;}
    .btn{display:inline-block;background:#2563eb;color:white;padding:10px 20px;border-radius:8px;text-decoration:none;margin-top:10px;}
    footer{background:#1e293b;text-align:center;padding:20px;margin-top:40px;}
  </style>
</head>
<body>

<header>
  <h1>Tillu Hackathon Portfolio</h1>
  <nav>
    <a href="#home">Home</a>
    <a href="#certificates">Certificates</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="home" class="hero">
  <h2>Welcome to My Certification Portfolio</h2>
  <p>I am a CSE student interested in Web Development, JavaScript, Node-RED, and IoT Projects.</p>
  <a class="btn" href="#certificates">View Certificates</a>
</section>

<section id="certificates">
  <h2>My Certifications</h2>

  <div class="card">
    <h3>HTML Certificate</h3>
    <a class="btn" href="007-html.pdf" target="_blank">View Certificate</a>
  </div>

  <div class="card">
    <h3>IoT Certificate</h3>
    <a class="btn" href="007-iot.pdf" target="_blank">View Certificate</a>
  </div>

  <div class="card">
    <h3>JavaScript Certificate</h3>
    <a class="btn" href="007-javascript.pdf" target="_blank">View Certificate</a>
  </div>

  <div class="card">
    <h3>Node-RED Certificate</h3>
    <a class="btn" href="007-node red.pdf" target="_blank">View Certificate</a>
  </div>

  <div class="card">
    <h3>Project Certificate</h3>
    <a class="btn" href="007-project.pdf" target="_blank">View Certificate</a>
  </div>
</section>

<section id="about">
  <h2>About Me</h2>
  <p>I am passionate about hackathons, IoT, and web development.</p>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Email: tillu@example.com</p>
  <p>GitHub: github.com/tillu</p>
</section>

<footer>
  <p>© 2026 Tillu | Hackathon Portfolio</p>
</footer>

</body>
</html>
