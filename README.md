<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AniStream</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #111;
      color: #fff;
    }
    header {
      background-color: #ff6600;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
    }
    nav a {
      margin: 0 10px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background-image: url('https://wallpaperaccess.com/full/2040256.jpg');
      background-size: cover;
      background-position: center;
      height: 250px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-shadow: 2px 2px 4px #000;
    }
    .hero h2 {
      font-size: 2.5em;
    }
    .anime-list {
      display: flex;
      flex-wrap: wrap;
      padding: 20px;
      gap: 20px;
      justify-content: center;
    }
    .anime-card {
      width: 150px;
      background-color: #222;
      border-radius: 8px;
      overflow: hidden;
      transition: transform 0.3s;
    }
    .anime-card:hover {
      transform: scale(1.05);
    }
    .anime-card img {
      width: 100%;
    }
    .anime-card h3 {
      font-size: 1em;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>AniStream</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Anime</a>
      <a href="#">Login</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Watch Your Favorite Anime Online</h2>
  </section>

  <section class="anime-list">
    <div class="anime-card">
      <img src="https://m.media-amazon.com/images/I/81r+LN1YxjL._AC_UF894,1000_QL80_.jpg" alt="Naruto" />
      <h3>Naruto</h3>
    </div>
    <div class="anime-card">
      <img src="https://upload.wikimedia.org/wikipedia/en/thumb/1/13/Attack_on_Titan_S4.jpg/220px-Attack_on_Titan_S4.jpg" alt="AoT" />
      <h3>Attack on Titan</h3>
    </div>
    <div class="anime-card">
      <img src="https://upload.wikimedia.org/wikipedia/en/2/26/Demon_Slayer_Kimetsu_no_Yaiba_volume_1_cover.jpg" alt="Demon Slayer" />
      <h3>Demon Slayer</h3>
    </div>
  </section>
</body>
</html>
