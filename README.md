<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Universo Geek Food</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      background: #f5f6fa;
      color: #2f3640;
    }

    header {
      background: #6c5ce7;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background: #a29bfe;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 10px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .container {
      max-width: 1100px;
      margin: 30px auto;
      padding: 20px;
    }

    .cardapio {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .item {
      background: white;
      border-radius: 15px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      padding: 20px;
      text-align: center;
      transition: 0.3s;
    }

    .item:hover {
      transform: translateY(-5px);
    }

    .item img {
      width: 100px;
      margin-bottom: 15px;
    }

    .item h3 {
      margin-bottom: 10px;
    }

    .item button {
      background: #6c5ce7;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 25px;
      cursor: pointer;
      transition: 0.3s;
    }

    .item button:hover {
      background: #4834d4;
    }

    .recompensas {
      background: #ffeaa7;
      padding: 20px;
      border-radius: 15px;
      margin-top: 40px;
      text-align: center;
    }

    .moedas {
      font-size: 30px;
      margin-top: 10px;
      color: #fdcb6e;
    }
  </style>
</head>
<body>

  <header>
    <h1>🍔 Universo Geek Food 🍕</h1>
    <p>Seu universo favorito agora tem sabor!</p>
  </header>

  <nav>
    <a href="#">Início</a>
    <a href="#">Cardápio</a>
    <a href="#">Recompensas</a>
    <a href="#">Contato</a>
  </nav>

  <div class="container">
    <h2>🌟 Escolha seu lanche</h2>
    <div class="cardapio">
      <div class="item">
        <img src="https://cdn-icons-png.flaticon.com/512/3075/3075977.png" alt="Burger Naruto">
        <h3>Rasengan Burguer</h3>
        <p>Hambúrguer apimentado com molho especial e queijo cheddar.</p>
        <button>Personalizar</button>
      </div>
      <div class="item">
        <img src="https://cdn-icons-png.flaticon.com/512/3075/3075898.png" alt="Pizza One Piece">
        <h3>One Slice Pizza</h3>
        <p>Pizza 4 queijos com massa fina e borda recheada.</p>
        <button>Personalizar</button>
      </div>
      <div class="item">
        <img src="https://cdn-icons-png.flaticon.com/512/3075/3075986.png" alt="Bolo Gumball">
        <h3>Bolo do Mundo de Gumball</h3>
        <p>Bolo arco-íris com recheio de morango e chantilly colorido.</p>
        <button>Personalizar</button>
      </div>
    </div>

    <div class="recompensas">
      <h2>💰 Suas Moedas Virtuais</h2>
      <p>A cada compra, você ganha moedas que podem ser trocadas por lanches grátis!</p>
      <div class="moedas">🪙 150 moedas</div>
    </div>
  </div>

</body>
</html>
