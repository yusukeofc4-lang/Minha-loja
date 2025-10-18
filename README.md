<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minha Loja</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f8f9fa;
      color: #333;
    }
    header {
      background: #4CAF50;
      color: white;
      text-align: center;
      padding: 1rem;
    }
    .produtos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      padding: 15px;
      text-align: center;
    }
    .card img {
      max-width: 100%;
      border-radius: 10px;
    }
    .preco {
      font-size: 18px;
      color: #4CAF50;
      font-weight: bold;
    }
    .botao {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 15px;
      background: #4CAF50;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>🌟 Minha Loja Online 🌟</h1>
    <p>Bem-vindo(a)! Escolha seu produto favorito</p>
  </header>

  <section class="produtos">
    <div class="card">
      <img src="https://via.placeholder.com/300" alt="Produto 1">
      <h2>Produto 1</h2>
      <p class="preco">R$ 49,90</p>
      <a class="botao" href="https://wa.me/55SEUNUMERO" target="_blank">Comprar</a>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/300" alt="Produto 2">
      <h2>Produto 2</h2>
      <p class="preco">R$ 79,90</p>
      <a class="botao" href="https://wa.me/55SEUNUMERO" target="_blank">Comprar</a>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/300" alt="Produto 3">
      <h2>Produto 3</h2>
      <p class="preco">R$ 99,90</p>
      <a class="botao" href="https://wa.me/55SEUNUMERO" target="_blank">Comprar</a>
    </div>
  </section>

  <footer>
    <p>© 2025 Minha Loja - Todos os direitos reservados</p>
  </footer>
</body>
</html>
