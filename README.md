# mon-site-basket
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Passion Basket</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f7f7f7;
      color: #333;
    }

    header {
      background-color: #D32F2F;
      color: white;
      padding: 20px;
      text-align: center;
    }

    main {
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
    }

    h2 {
      color: #D32F2F;
    }

    .players {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }

    .player-card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      width: 250px;
      overflow: hidden;
      text-align: center;
    }

    .player-card img {
      width: 100%;
      height: 300px;
      object-fit: cover;
    }

    .player-card h3 {
      margin: 10px 0;
    }

    footer {
      text-align: center;
      background-color: #eee;
      padding: 10px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Ma passion : le Basket</h1>
    <p>Découvrez mes joueurs préférés !</p>
  </header>

  <main>
    <h2>Les Légendes du Basket</h2>
    <div class="players">
      <div class="player-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/5/5d/LeBron_James_Lakers.jpg" alt="LeBron James">
        <h3>LeBron James</h3>
        <p>Star des Lakers, multiple champion NBA et MVP.</p>
      </div>

      <div class="player-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/7/7c/Michael_Jordan_in_2014.jpg" alt="Michael Jordan">
        <h3>Michael Jordan</h3>
        <p>Légende des Bulls, considéré comme le meilleur joueur de tous les temps.</p>
      </div>

      <div class="player-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/8/89/Stephen_Curry_2022.jpg" alt="Stephen Curry">
        <h3>Stephen Curry</h3>
        <p>Maître du tir à 3 points, star des Golden State Warriors.</p>
      </div>
    </div>
  </main>

  <footer>
    © 2025 - Adam Glab, fan de basket
  </footer>

</body>
</html>
