<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta http-equiv="X-UA-Compatible" content="ie=edge" />
  <title>PY Healthcare LLP</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <img src="logo.png" alt="PY Healthcare LLP Logo" class="logo" />
    <h1>PY Healthcare LLP</h1>
    <p>Your Trusted Medical Equipment & Regulatory Partner</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>Medical Equipment Supplier: CT, MRI, PET-CT, Gamma Camera</li>
      <li>Radiological Equipments</li>
      <li>Nuclear Medicine Equipments</li>
      <li>Regulatory Consultation Services</li>
      <ul>
        <li>AERB - Atomic Energy Regulatory Board Licensing</li>
        <li>ET Machine Licensing</li>
        <li>QA of CF, PET-CE Machines</li>
      </ul>
      <li>National & International Client Services</li>
    </ul>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>PY Healthcare LLP is a professional medical equipment supplier and regulatory service provider. We work with both national and international clients in the healthcare and nuclear medicine industries.</p>
    <h3>Our Key Management:</h3>
    <ul>
      <li>Gourav Thakur</li>
      <li>Gajendra Singh</li>
      <li>Amit Kumar Gupta</li>
    </ul>
    <p><strong>Address:</strong><br>
      Shop No 12, Omaxe City, Palwal, Faridabad, Haryana, India, 121102<br>
      Region: Faridabad
    </p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:PYhealthcarellp@gmail.com">PYhealthcarellp@gmail.com</a></p>
    <form onsubmit="return validateForm()">
      <label for="name">Your Name:</label><br />
      <input type="text" id="name" name="name" required /><br />
      <label for="email">Your Email:</label><br />
      <input type="email" id="email" name="email" required /><br />
      <label for="message">Message:</label><br />
      <textarea id="message" name="message" required></textarea><br />
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 PY Healthcare LLP. All rights reserved.</p>
  </footer>

  <script>
    function validateForm() {
      const name = document.getElementById("name").value.trim();
      const email = document.getElementById("email").value.trim();
      const message = document.getElementById("message").value.trim();
      if (!name || !email || !message) {
        alert("Please fill out all fields.");
        return false;
      }
      return true;
    }
  </script>
</body>
</html># PY-Helthcare-LLP
