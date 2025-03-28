<iframe height="167" frameborder="0" src="https://itch.io/embed/3363299" width="552"><a href="https://mightyandpowerfulgames.itch.io/mapgrid">MAPGrid - 3D Tilemap/World Builder for Unity by MightyAndPowerfulGames</a></iframe>

<iframe src="https://itch.io/embed/3394651" width="552" height="167" frameborder="0"><a href="https://mightyandpowerfulgames.itch.io/steampunk-pirates-extremely-early-access">Steampunk Pirates - Mechanics Prototype by MightyAndPowerfulGames</a></iframe>

<iframe width="552" height="167" frameborder="0" src="https://itch.io/embed/3375375"><a href="https://mightyandpowerfulgames.itch.io/assortment-of-pixel-characters-with-animations">Assortment of Pixel Characters with Animations by MightyAndPowerfulGames</a></iframe>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Might And Powerful Games</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&family=Roboto&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Roboto', sans-serif;
      background: #0e0e0e;
      color: #f5f5f5;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(to right, #111, #1f1f1f);
      padding: 2rem;
      text-align: center;
      border-bottom: 2px solid #444;
    }

    header h1 {
      font-family: 'Orbitron', sans-serif;
      font-size: 2.5rem;
      color: #ff3c00;
      letter-spacing: 2px;
    }

    nav {
      margin-top: 1rem;
    }

    nav a {
      color: #aaa;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #ff3c00;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1600195077078-4c3d0c2e6e8b') no-repeat center center/cover;
      height: 90vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      padding: 2rem;
    }

    .hero h2 {
      font-size: 3rem;
      background: rgba(0, 0, 0, 0.6);
      padding: 1rem 2rem;
      border-radius: 10px;
    }

    section {
      padding: 4rem 2rem;
      max-width: 1100px;
      margin: auto;
    }

    .about, .games {
      margin-bottom: 4rem;
    }

    .about h3, .games h3 {
      font-size: 2rem;
      margin-bottom: 1rem;
      color: #ff3c00;
    }

    .about p {
      font-size: 1.1rem;
      color: #ccc;
    }

    .games-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }

    .game-card {
      background: #1c1c1c;
      border: 1px solid #333;
      border-radius: 10px;
      overflow: hidden;
      transition: transform 0.3s ease;
    }

    .game-card:hover {
      transform: scale(1.05);
    }

    .game-card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .game-card h4 {
      padding: 1rem;
      font-size: 1.2rem;
      color: #fff;
    }

    footer {
      background: #111;
      color: #888;
      padding: 2rem;
      text-align: center;
      border-top: 2px solid #444;
    }

    footer a {
      color: #ff3c00;
      text-decoration: none;
    }

    @media (max-width: 600px) {
      .hero h2 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Might And Powerful Games</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#games">Games</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <h2>Creating Worlds. Forging Legends.</h2>
  </div>

  <section id="about" class="about">
    <h3>About Us</h3>
    <p>
      We are a passionate indie game studio focused on delivering immersive, story-driven, and visually stunning experiences. 
      At Might And Powerful Games, we believe in the magic of interactive storytelling and the power of gameplay to inspire and challenge.
    </p>
  </section>

  <section id="games" class="games">
    <h3>Our Games</h3>
    <div class="games-grid">
      <div class="game-card">
        <img src="https://images.unsplash.com/photo-1605902711622-cfb43c4437d4" alt="Game 1" />
        <h4>Chrono Blades</h4>
      </div>
      <div class="game-card">
        <img src="https://images.unsplash.com/photo-1558981403-c5f9891a4a59" alt="Game 2" />
        <h4>Shadow Realms</h4>
      </div>
      <div class="game-card">
        <img src="https://images.unsplash.com/photo-1568605114967-8130f3a36994" alt="Game 3" />
        <h4>Skyforge: Awakening</h4>
      </div>
    </div>
  </section>

  <footer id="contact">
    <p>Contact us: <a href="mailto:contact@mightandpowerfulgames.com">contact@mightandpowerfulgames.com</a></p>
    <p>&copy; 2025 Might And Powerful Games. All rights reserved.</p>
  </footer>

</body>
</html>
