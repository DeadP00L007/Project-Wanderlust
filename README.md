<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pokhara - The Wonderful City</title>
  <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f0f8ff;
    }
    header, footer {
      background: #2c3e50;
      color: white;
      padding: 1em;
      text-align: center;
    }
    .hero {
      background: url('https://upload.wikimedia.org/wikipedia/commons/1/1a/Phewa_Lake_Pokhara_Nepal.jpg') center/cover no-repeat;
      height: 300px;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 2em;
      text-shadow: 1px 1px 4px #000;
    }
    section {
      padding: 2em;
    }
    h2 {
      color: #2980b9;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1em;
    }
    .gallery img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>

  <header>
    <h1>Pokhara – The Wonderful City</h1>
  </header>

  <div class="hero">
    Welcome to Pokhara
  </div>

  <section>
    <h2>Top Attractions</h2>
    <ul>
      <li>Phewa Lake</li>
      <li>World Peace Pagoda</li>
      <li>Davis Falls</li>
      <li>Sarangkot Sunrise</li>
      <li>Gupteshwor Mahadev Cave</li>
    </ul>
  </section>

  <section>
    <h2>Nature & Wildlife</h2>
    <div class="gallery">
      <img src="https://upload.wikimedia.org/wikipedia/commons/1/1a/Phewa_Lake_Pokhara_Nepal.jpg" alt="Phewa Lake" data-aos="fade-up" />
      <img src="https://upload.wikimedia.org/wikipedia/commons/e/e2/Machapuchare.jpg" alt="Machhapuchhre Mountain" data-aos="fade-up" />
      <img src="https://upload.wikimedia.org/wikipedia/commons/1/12/World_Peace_Pagoda%2C_Pokhara.jpg" alt="Peace Pagoda" data-aos="fade-up" />
      <img src="https://upload.wikimedia.org/wikipedia/commons/1/13/Bird_Pokhara.jpg" alt="Bird in Pokhara" data-aos="fade-up" />
      <img src="https://upload.wikimedia.org/wikipedia/commons/7/79/Sarangkot_sunrise.jpg" alt="Sunset from Sarangkot" data-aos="fade-up" />
      <img src="https://upload.wikimedia.org/wikipedia/commons/5/5a/Wildlife_Pokhara_Nepal.jpg" alt="Wildlife in Pokhara" data-aos="fade-up" />
    </div>
  </section>

  <footer>
    &copy; 2025 Pokhara Tourism | Made with ❤️
  </footer>

  <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
  <script>
    AOS.init();
  </script>

</body>
</html>
