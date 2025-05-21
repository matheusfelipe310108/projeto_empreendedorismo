<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Level Up Lanches</title>
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: linear-gradient(to right, #1e272e, #2d3436);
      font-family: 'Poppins', sans-serif;
      color: #fff;
    }

    header {
      background: #ff4757;
      padding: 30px 20px;
      text-align: center;
      font-family: 'Press Start 2P', cursive;
      font-size: 1.5rem;
      color: #fff;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 40px;
      background: #2f3542;
      padding: 15px;
    }

    nav a {
      text-decoration: none;
      color: #fffa65;
      font-weight: 600;
      transition: 0.3s;
    }

    nav a:hover {
      color: #70a1ff;
    }

    .container {
      max-width: 1200px;
      margin: 40px auto;
      padding: 20px;
    }

    .titulo {
      text-align: center;
      font-size: 2rem;
      margin-bottom: 30px;
      color: #fffa65;
    }

    .cardapio {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }

    .item {
      background: #57606f;
      border-radius: 15px;
      padding: 20px;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
      transition: 0.3s;
    }

    .item:hover {
      transform: scale(1.05);
    }

    .item img {
      width: 120px;
      height: 120px;
      object-fit: contain;
      margin-bottom: 15px;
    }

    .item h3 {
      margin-bottom: 10px;
      font-size: 1.2rem;
      color: #fffa65;
    }

    .item p {
      font-size: 0.95rem;
      margin-bottom: 15px;
    }

    .item button {
      background: #ff4757;
      color: white;
      border: none;
      padding: 10px 25px;
      border-radius: 30px;
      font-weight: bold;
      cursor: pointer;
      transition: background 0.3s;
    }

    .item button:hover {
      background: #ff6b81;
    }

    .recompensas {
      background: #2ed573;
      color: #2f3542;
      padding: 30px;
      border-radius: 20px;
      text-align: center;
      margin-top: 50px;
    }

    .recompensas h2 {
      font-family: 'Press Start 2P', cursive;
      margin-bottom: 15px;
      color: #fff;
    }

    .recompensas p {
      font-size: 1rem;
    }

    .moedas {
      font-size: 2rem;
      margin-top: 15px;
    }
  </style>
</head>
<body>

  <header>
    🍔 LEVEL UP LANCHES 🎮
  </header>

  <nav>
    <a href="#">Início</a>
    <a href="#">Cardápio</a>
    <a href="#">Recompensas</a>
    <a href="#">Contato</a>
  </nav>

  <div class="container">
    <h2 class="titulo">🌟 Monte seu Combo Geek!</h2>
    <div class="cardapio">
      <div class="item">
        <img src="https://cdn-icons-png.flaticon.com/512/1046/1046784.png" alt="">
        <h3>PokéBurger</h3>
        <p>Burger temático do Pikachu com cheddar, batata smile e molho thunder.</p>
        <button>Personalizar</button>
      </div>
      <div class="item">
        <img src="https://cdn-icons-png.flaticon.com/512/1046/1046750.png" alt="">
        <h3>Pizza Sayajin</h3>
        <p>Pizza com queijo flamejante, borda de cebola e toque especial do Goku.</p>
        <button>Personalizar</button>
      </div>
      <div class="item">
        <img src="https://cdn-icons-png.flaticon.com/512/1046/1046857.png" alt="">
        <h3>Bolo Multiverso</h3>
        <p>Bolo com camadas inspiradas em Marvel, DC e outras dimensões saborosas.</p>
        <button>Personalizar</button>
      </div>
    </div>

    <div class="recompensas">
      <h2>🪙 Sistema de Recompensas</h2>
      <p>Acumule moedas a cada pedido e troque por lanches temáticos exclusivos!</p>
      <div class="moedas">Você tem: 220 moedas</div>
    </div>
  </div>

</body>
</html>
