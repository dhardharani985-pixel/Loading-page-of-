Landing page 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dharani.A | JEYA MURUGAN E-SEVA</title>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; }
    header, footer { background: #333; color: #fff; text-align: center; padding: 1rem; }
    .hero { text-align: center; padding: 3rem 1rem; background: #6a11cb; color: #fff; }
    .hero button { padding: 0.7rem 1.2rem; border: none; border-radius: 5px; margin-top: 1rem; cursor: pointer; }
    .features { display: flex; justify-content: center; gap: 1rem; padding: 2rem; background: #f9f9f9; flex-wrap: wrap; }
    .feature { background: #fff; padding: 1rem; border-radius: 5px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    .contact { padding: 2rem; text-align: center; background: #eef2f3; }
    .contact h2 { margin-bottom: 1rem; }
    .contact p { margin: 0.5rem 0; }
    .contact a { color: #6a11cb; font-weight: bold; text-decoration: none; }
    .contact a:hover { text-decoration: underline; }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <h2>Dharani.A</h2>
    <p>JEYA MURUGAN E-SEVA</p>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Browsing Centre</h1>
    <p>Loading page<br>
    "I am a small business owner. I operate a small home-based browsing center, providing services such as online certificates and cards. Customers notice my service board and reach out to me."</p>
    <button onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'});">Contact Us</button>
  </section>

  <!-- Features -->
  <section class="features">
    <div class="feature">✅ Proactive Approach</div>
    <div class="feature">⚡ Decisive Action</div>
    <div class="feature">🎯 Focused and Productive</div>
  </section>

  <!-- Contact Section -->
  <section class="contact" id="contact">
    <h2>Contact Details</h2>
    <p><strong>Owner:</strong> Dharani.A</p>
    <p><strong>Business:</strong> JEYA MURUGAN E-SEVA</p>
    <p><strong>Phone:</strong> <a href="tel:+919876543210">+91 8056432026</a></p>
    <p><strong>Email:</strong> <a href="mailto: dhardharani985@gmail.com">dhardharani985@gmail.com</a></p>
    <p><strong>Address:</strong> 80C, Middle street, Dindigul, Tamil Nadu</p>
  </section>

  <!-- Footer -->
  <footer>&copy; 2025 JEYA MURUGAN</footer>
</body>
</html>
