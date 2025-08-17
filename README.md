# Cosm-tique-site-
beauté, soins et cosmétiques, style et éclat.
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cosmétiques Douceur</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #fce4ec;
      color: #333;
      overflow-x: hidden;
    }
    header {
      background: linear-gradient(135deg, #f8bbd0, #f48fb1);
      padding: 20px;
      text-align: center;
      font-size: 28px;
      font-weight: bold;
      color: white;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      animation: fadeInDown 1s ease;
    }
    nav {
      background: #f48fb1;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px;
      position: sticky;
      top: 0;
      z-index: 10;
      animation: fadeIn 2s ease;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #333;
    }
    .hero {
      text-align: center;
      padding: 80px 20px;
      background: url('https://via.placeholder.com/1200x400/ffe4ec/333?text=Beaut%C3%A9+Naturelle') center/cover;
      color: white;
      animation: fadeIn 2s ease;
    }
    .hero h1 {
      font-size: 48px;
      margin-bottom: 15px;
      text-shadow: 1px 1px 4px rgba(0,0,0,0.3);
    }
    .section {
      padding: 60px 20px;
      text-align: center;
      animation: fadeInUp 1.5s ease;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 25px;
      padding: 20px;
    }
    .product {
      background: white;
      padding: 20px;
      border-radius: 15px;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s, box-shadow 0.3s;
      opacity: 0;
      transform: translateY(20px);
      animation: fadeInUp 1s ease forwards;
    }
    .product:nth-child(1) { animation-delay: 0.3s; }
    .product:nth-child(2) { animation-delay: 0.6s; }
    .product:nth-child(3) { animation-delay: 0.9s; }
    .product:nth-child(4) { animation-delay: 1.2s; }
    .product:nth-child(5) { animation-delay: 1.5s; }
    .product img {
      max-width: 100%;
      border-radius: 12px;
      margin-bottom: 10px;
    }
    .about, .contact, .testimonials {
      background: #fff;
      margin: 20px auto;
      border-radius: 12px;
      max-width: 900px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      padding: 30px;
      animation: fadeInUp 1.5s ease;
    }
    .testimonials blockquote {
      font-style: italic;
      margin: 20px 0;
      padding: 15px;
      border-left: 4px solid #f48fb1;
      background: #fce4ec;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 500px;
      margin: auto;
    }
    form input, form textarea, form button {
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 16px;
    }
    form button {
      background: #f48fb1;
      color: white;
      font-weight: bold;
      cursor: pointer;
      border: none;
      transition: background 0.3s;
    }
    form button:hover {
      background: #ec407a;
    }
    footer {
      background: linear-gradient(135deg, #f8bbd0, #f48fb1);
      text-align: center;
      padding: 20px;
      margin-top: 30px;
      color: white;
      animation: fadeIn 2s ease;
    }

    /* Animations */
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-30px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <header>Cosmétiques Douceur</header>
  <nav>
    <a href="#accueil">Accueil</a>
    <a href="#produits">Produits</a>
    <a href="#apropos">À propos</a>
    <a href="#temoignages">Témoignages</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="accueil" class="hero">
    <h1>Éclat & Beauté Naturelle</h1>
    <p>Des cosmétiques pensés pour sublimer votre peau et vos cheveux.</p>
  </section>

  <section id="produits" class="section">
    <h2>Nos Produits</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/200x200?text=Crème+Hydratante" alt="Crème Hydratante">
        <h3>Crème Hydratante</h3>
        <p>Hydrate et adoucit la peau.</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x200?text=Rouge+à+lèvres" alt="Rouge à lèvres">
        <h3>Rouge à lèvres</h3>
        <p>Couleur intense et tenue parfaite.</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x200?text=Sérum+Visage" alt="Sérum Visage">
        <h3>Sérum Visage</h3>
        <p>Revitalise et illumine la peau.</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x200?text=Palette+Maquillage" alt="Palette Maquillage">
        <h3>Palette Maquillage</h3>
        <p>Des couleurs élégantes pour toutes occasions.</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x200?text=Shampooing+Bio" alt="Shampooing Bio">
        <h3>Shampooing Bio</h3>
        <p>Nettoie et nourrit vos cheveux naturellement.</p>
      </div>
    </div>
  </section>

  <section id="apropos" class="about">
    <h2>À propos de nous</h2>
    <p>Cosmétiques Douceur est une marque passionnée par la beauté naturelle. Nous sélectionnons avec soin les meilleurs ingrédients pour vous offrir des produits respectueux de votre peau et de l'environnement. Notre mission est de mettre en valeur l'éclat unique de chaque personne.</p>
  </section>

  <section id="temoignages" class="testimonials">
    <h2>Témoignages</h2>
    <blockquote>"La crème hydratante a transformé ma peau en seulement une semaine !" – Marie</blockquote>
    <blockquote>"Un rouge à lèvres qui tient toute la journée, j'adore !" – Claire</blockquote>
    <blockquote>"Le shampooing bio a redonné vie à mes cheveux secs." – Julie</blockquote>
  </section>

  <section id="contact" class="contact">
    <h2>Contactez-nous</h2>
    <form>
      <input type="text" placeholder="Votre nom" required>
      <input type="email" placeholder="Votre email" required>
      <textarea rows="5" placeholder="Votre message" required></textarea>
      <button type="submit">Envoyer</button>
    </form>
  </section>

  <footer>
    &copy; 2025 Cosmétiques Douceur - Tous droits réservés | contact@cosmetiquesdouceur.com
  </footer>
</body>
</html>
