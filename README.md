<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minha Vitrine de Produtos</title>
  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
      margin: 0;
      background: #fff5f8;
      color: #333;
    }
    header {
      background: #e91e63;
      color: white;
      padding: 30px 20px;
      text-align: center;
    }
    section {
      padding: 40px 20px;
      max-width: 1100px;
      margin: auto;
    }
    .produtos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .produto {
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      padding: 20px;
      text-align: center;
    }
    .produto img {
      max-width: 100%;
      border-radius: 10px;
    }
    .produto a {
      display: inline-block;
      margin-top: 15px;
      background: #e91e63;
      color: white;
      padding: 10px 20px;
      border-radius: 20px;
      text-decoration: none;
      font-weight: bold;
    }
    .produto a:hover {
      background: #c2185b;
    }
  </style>
</head>
<body>

<header>
  <h1>Minha Vitrine de Produtos</h1>
  <p>Utensílios domésticos e beleza que facilitam seu dia 💖</p>
</header>

<section>
  <h2>🛍️ Produtos em Destaque</h2>
  <div class="produtos">

    <div class="produto">
      <img src="https://via.placeholder.com/300x200">
      <h3>Produto de Beleza</h3>
      <p>Descrição simples e atrativa do produto.</p>
      <a href="SEU_LINK_TIKTOK_AQUI" target="_blank">Comprar agora</a>
    </div>

  </div>
</section>

</body>
</html>
