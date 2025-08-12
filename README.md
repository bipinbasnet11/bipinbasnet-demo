<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Bipin Basnet — Gaming & Nepali Vibes</title>

  <!-- SEO / Social -->
  <meta name="description" content="BipinBasnet.com — where gaming meets Nepali spirit. Mountains, prayer flags and a gaming aesthetic." />
  <meta property="og:title" content="Bipin Basnet — Gaming & Nepali Vibes" />
  <meta property="og:description" content="Where gaming meets Nepali spirit — mountains, art, and community." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="assets/mountains.png" />
  <meta property="og:url" content="https://bipinbasnet.com/" />

  <!-- favicon (inline SVG) -->
  <link rel="icon" href='data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><rect fill="%230e1620" width="100" height="100"/><text x="50" y="62" font-size="46" font-family="Arial" fill="%23ff4655" text-anchor="middle">B</text></svg>' />

  <!-- web manifest -->
  <link rel="manifest" href="manifest.json" />

  <!-- Fonts -->
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500;700&family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <!-- Styles -->
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <a class="skip-link" href="#main">Skip to content</a>

  <header class="site-header" role="banner">
    <div class="container header-inner">
      <div class="brand" aria-label="Bipin Basnet homepage">
        <button id="navToggle" class="hamburger" aria-expanded="false" aria-controls="siteNav" title="Toggle menu">
          <span class="hamburger-box"><span class="hamburger-inner"></span></span>
        </button>
        <a href="/" class="logo"><span aria-hidden="true">🎮</span> Bipin Basnet</a>
      </div>

      <nav id="siteNav" class="site-nav" role="navigation" aria-label="Main navigation">
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#games">Games</a></li>
          <li><a href="#gallery">Gallery</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main id="main">
    <!-- HERO: sky + mountains + prayer flags -->
    <section id="home" class="hero" aria-label="Hero section showing mountains and prayer flags">
      <!-- Sky / clouds -->
      <div class="sky" aria-hidden="true">
        <div class="cloud cloud--1"></div>
        <div class="cloud cloud--2"></div>
      </div>

      <!-- Mountains (SVG background or image) -->
      <div class="mountains" role="img" aria-label="Himalayan mountains"></div>

      <!-- Prayer flags on rope -->
      <div class="flags" aria-hidden="true">
        <div class="rope"></div>
        <div class="flag flag--blue"></div>
        <div class="flag flag--white"></div>
        <div class="flag flag--red"></div>
        <div class="flag flag--green"></div>
        <div class="flag flag--yellow"></div>
      </div>

      <!-- Hero content -->
      <div class="hero-content">
        <h1>Welcome to <span class="accent">BipinBasnet.com</span></h1>
        <p class="lead">Where Gaming Meets Nepali Spirit — mountains, art and community.</p>

        <div class="cta">
          <a class="btn" href="#games">Explore Games</a>
          <a class="btn btn--ghost" href="#contact">Contact</a>
        </div>

        <div class="social" aria-label="Follow on social media">
          <a class="social-btn fb" href="https://www.facebook.com/share/1BeqqsWS1N/?mibextid=wwXIfr" target="_blank" rel="noopener">Facebook</a>
          <a class="social-btn ig" href="https://www.instagram.com/bipinbasnet11?igsh=anNubjh0bDdqeHVs&utm_source=qr" target="_blank" rel="noopener">Instagram</a>
          <a class="social-btn x" href="https://x.com/bipinbasnet1111?s=21" target="_blank" rel="noopener">X</a>
        </div>
      </div>
    </section>

    <!-- Example sections -->
    <section id="games" class="section container">
      <h2>Games & Streams</h2>
      <p>Coming soon — showcase your games, clips and streams here.</p>
    </section>

    <section id="gallery" class="section container">
      <h2>Gallery</h2>
      <p>Art, screenshots, and Nepali-inspired designs.</p>
    </section>

    <section id="contact" class="section container">
      <h2>Contact</h2>
      <p>If you'd like to reach out, use the form below or email: <a href="mailto:hello@bipinbasnet.com">hello@bipinbasnet.com</a></p>

      <!-- Contact form (works with Formspree when you replace ACTION) -->
      <form id="contactForm" class="contact-form" method="POST" action="">
        <!-- To activate: replace action="" with your Formspree endpoint or server endpoint -->
        <label>
          <span>Name</span>
          <input name="name" type="text" required>
        </label>
        <label>
          <span>Email</span>
          <input name="email" type="email" required>
        </label>
        <label>
          <span>Message</span>
          <textarea name="message" rows="5" required></textarea>
        </label>
        <div class="form-actions">
          <button type="submit" class="btn">Send Message</button>
        </div>
        <div id="formStatus" role="status" aria-live="polite"></div>
      </form>
    </section>
  </main>

  <footer class="site-footer" role="contentinfo">
    <div class="container">
      <p>© <span id="year"></span> Bipin Basnet — Designed with 🎮 and 🇳🇵</p>
    </div>
  </footer>

  <script src="js/main.js" defer></script>
</body>
</html>
