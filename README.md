<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NOVA Architecture Studio</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<!-- NAV -->
<header class="header">
  <div class="container nav">
    <h1 class="logo">NOVA<span>.</span></h1>
    <nav>
      <ul class="nav-links">
        <li><a href="#home">Accueil</a></li>
        <li><a href="#about">Studio</a></li>
        <li><a href="#work">Projets</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </div>
</header>

<!-- HERO -->
<section id="home" class="hero">
  <div class="hero-content reveal">
    <h1>Architecture contemporaine</h1>
    <p>Nous concevons des espaces iconiques et intemporels.</p>
    <a href="#work" class="btn">Découvrir</a>
  </div>
</section>

<!-- ABOUT -->
<section id="about" class="section reveal">
  <h2>Studio</h2>
  <p>
    NOVA Architecture est un studio international spécialisé dans la conception
    de bâtiments modernes, minimalistes et durables.
  </p>
</section>

<!-- WORK -->
<section id="work" class="section">
  <h2 class="reveal">Projets</h2>

  <div class="grid">
    <div class="card reveal">
      <img src="https://picsum.photos/600/400?1">
      <div class="overlay">Villa Horizon</div>
    </div>

    <div class="card reveal">
      <img src="https://picsum.photos/600/400?2">
      <div class="overlay">Sky Tower</div>
    </div>

    <div class="card reveal">
      <img src="https://picsum.photos/600/400?3">
      <div class="overlay">Museum Light</div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact" class="section reveal">
  <h2>Contact</h2>

  <form id="form">
    <input type="text" placeholder="Nom" required>
    <input type="email" placeholder="Email" required>
    <textarea placeholder="Message"></textarea>
    <button type="submit">Envoyer</button>
  </form>
</section>

<footer>
  <p>© 2026 NOVA Architecture Studio</p>
</footer>

<script src="script.js"></script>
</body>
</html># Architecte-