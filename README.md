<!DOCTYPE html><html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Blocksroute - PanoConta</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #111;
      color: white;
    }
    header {
      background-color: #c00;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2em;
    }
    .container {
      padding: 20px;
    }
    .section {
      margin-bottom: 30px;
      background-color: #222;
      padding: 20px;
      border-radius: 10px;
    }
    .section h2 {
      margin-top: 0;
      color: #ff4444;
    }
    label {
      display: block;
      margin: 10px 0 5px;
    }
    input, select {
      width: 100%;
      padding: 8px;
      border: none;
      border-radius: 5px;
      margin-bottom: 15px;
    }
    button {
      background-color: #c00;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
    }
    button:hover {
      background-color: #a00;
    }
    .insta {
      text-align: center;
      margin-top: 40px;
    }
    .insta a {
      background-color: #c00;
      padding: 12px 20px;
      color: white;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <h1>Blocksroute - Upe sua Conta com o PanoConta</h1>
  </header>
  <div class="container">
    <div class="section">
      <h2>Informações da Conta</h2>
      <label for="nick">Seu nick no Blox Fruits:</label>
      <input type="text" id="nick" placeholder="Ex: DarkPano123"><label for="nivel">Até que nível você quer upar?</label>
  <input type="number" id="nivel" placeholder="Ex: 2600">

  <label for="mar">Até qual mar você quer upar?</label>
  <select id="mar">
    <option>1º Mar</option>
    <option>2º Mar</option>
    <option>3º Mar</option>
  </select>

  <label for="pagamento">Forma de pagamento:</label>
  <select id="pagamento">
    <option>Fruta mítica (exceto Gravidade)</option>
    <option>Fruta da Luz pra cima (2º Mar)</option>
    <option>R$25 (1º ao 2º Mar)</option>
    <option>R$95 (1º ao 3º Mar ou 2º ao 3º Mar)</option>
  </select>
</div>

<div class="section">
  <h2>Descrição do Serviço</h2>
  <p>Você quer upar sua conta até o nível máximo ou até um mar específico? Aqui o PanoConta cuida disso pra você!</p>
  <ul>
    <li><strong>1º ao 2º Mar:</strong> R$25 ou fruta da Luz pra cima (ex: Buda).</li>
    <li><strong>1º ao 3º Mar ou 2º ao 3º Mar:</strong> R$95 ou fruta mítica (exceto Gravidade).</li>
    <li>Pagamento por PIX ou fruta entregue in-game.</li>
  </ul>
</div>

<div class="insta">
  <a href="#" id="instagramBtn" target="_blank">Entrar em contato no Instagram</a>
</div>

  </div>  <script>
    // Quando Davi passar o arroba, a gente substitui o link aqui
    const instagram = "https://instagram.com/furyaup";
    document.getElementById("instagramBtn").href = instagram;
  </script></body>
</html>
