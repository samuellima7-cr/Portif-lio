[portfolio_site_ready.html](https://github.com/user-attachments/files/22125951/portfolio_site_ready.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Samuel Alencar — Web Designer & Developer</title>
  <meta name="description" content="Modern, responsive and high-converting websites for small businesses and startups. Landing pages, business sites, and e-commerce.">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    /* Estilo resumido para o portfólio */
    body{margin:0;font-family:Inter,sans-serif;background:#0b0e14;color:#e6edf6;line-height:1.6}
    a{color:inherit;text-decoration:none}
    .container{max-width:1200px;margin:0 auto;padding:24px}
    header,section,footer{padding:24px 0}
    .btn{display:inline-block;padding:12px 18px;border-radius:999px;background:#6ee7b7;color:#071417;font-weight:600}
    .btn:hover{opacity:.85}
  </style>
</head>
<body>
  <header class="container">
    <h1>Samuel Alencar — Web Dev</h1>
    <p><a class="btn" href="https://www.fiverr.com/samuelalencar" target="_blank">Hire me on Fiverr</a></p>
  </header>

  <section class="container" id="portfolio">
    <h2>Portfolio</h2>
    <p>Confira alguns projetos recentes:</p>
    <ul>
      <li>Restaurant Website — Next.js, NYC</li>
      <li>E-commerce Fashion Store — Shopify, London</li>
      <li>Consulting Landing Page — WordPress, Toronto</li>
    </ul>
    <p><a class="btn" href="#contact">Contact Me</a></p>
  </section>

  <section class="container" id="contact">
    <h2>Contact</h2>
    <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
      <input type="text" name="name" placeholder="Your Name" required><br><br>
      <input type="email" name="email" placeholder="Your Email" required><br><br>
      <textarea name="message" placeholder="Your project details" required></textarea><br><br>
      <button class="btn" type="submit">Send Message</button>
    </form>
  </section>

  <footer class="container">
    <p>© 2025 Samuel Alencar. All rights reserved.</p>
  </footer>
</body>
</html>
