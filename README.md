<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Vconecta - Telemetria e Rastreamento</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    /* Custom CSS */
    body {
      background-color: #f8f9fa;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }
    header {
      background-color: rgb(184, 50, 92);
      color: #fff;
      padding: 10px;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-shrink: 0;
    }
    header img {
      width: 100px;
    }
    header ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }
    header ul li {
      position: relative;
    }
    header ul li a {
      color: #fff;
      text-decoration: none;
    }
    header ul li:hover ul {
      display: block;
    }
    header ul ul {
      display: none;
      position: absolute;
      top: 100%;
      left: 0;
      background-color: rgb(184, 50, 92);
      padding: 10px;
      border-radius: 5px;
    }
    header ul ul li {
      width: 150px;
      margin: 5px 0;
    }
    section {
      padding: 20px;
      flex-grow: 1;
      text-align: center;
    }
    .form-container {
      background-color: rgb(184, 50, 92);
      color: #fff;
      padding: 20px;
      width: 300px;
      margin: 0 auto;
    }
    #app-info {
      background-color: rgb(184, 50, 92);
      color: #fff;
      padding: 20px;
      width: 300px;
      margin: 0 auto;
    }
    #footer {
      background-color: #343a40;
      color: #fff;
      padding: 10px;
      text-align: center;
      flex-shrink: 0;
    }
    #footer a {
      color: #fff;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.png" alt="Vconecta Logo">
    <ul>
      <li>
        <a href="#">Conheça Nossos Planos</a>
        <ul>
          <li><a href="#">Plano A</a></li>
          <li><a href="#">Plano B</a></li>
          <li><a href="#">Plano C</a></li>
        </ul>
      </li>
      <li>
        <a href="#">Faça um Teste</a>
        <ul>
          <li><a href="#">Teste Gratuito</a></li>
          <li><a href="#">Teste Premium</a></li>
        </ul>
      </li>
      <li>
        <a href="#">Fale Conosco</a>
        <ul>
          <li><a href="#">Contato</a></li>
          <li><a href="#">Suporte</a></li>
        </ul>
      </li>
    </ul>
  </header>

  <section>
    <h1>SISTEMA DE RASTREAMENTO E TELEMETRIA PARA SUA FROTA</h1>
    <p>Venha conhecer nossa solução de telemetria.</p>
  </section>

  <section>
    <h2>Breve Explicação sobre Telemetria e Rastreamento Veicular</h2>
    <p>Texto de exemplo sobre telemetria e rastreamento veicular.</p>
  </section>

  <div class="form-container">
    <h2>Faça um Teste</h2>
    <form>
      <div class="mb-3">
        <label for="nome" class="form-label">Nome:</label>
        <input type="text" class="form-control" id="nome" required>
      </div>
      <div class="mb-3">
        <label for="email" class="form-label">Email:</label>
        <input type="email" class="form-control" id="email" required>
      </div>
      <div class="mb-3">
        <label for="telefone" class="form-label">Telefone:</label>
        <input type="tel" class="form-control" id="telefone" required>
      </div>
      <div class="mb-3">
        <label for="quantidadeVeiculos" class="form-label">Quantidade de Veículos:</label>
        <input type="number" class="form-control" id="quantidadeVeiculos" required>
      </div>
      <button type="submit" class="btn btn-primary">Enviar</button>
    </form>
  </div>

  <div id="app-info">
    <h3>App Vconecta</h3>
    <p>Faça o download do app Vconecta e fique por dentro de todas as informações do seu veículo ou frota!</p>
    <div>
      <a href="#" class="btn btn-secondary">Download no Google Play</a>
      <a href="#" class="btn btn-secondary">Download na Apple Store</a>
    </div>
  </div>

  <footer id="footer">
    <p>suporte@vconecta.com.br<br>Política de Privacidade</p>
  </footer>

  <!-- Bootstrap JS and Popper.js (required for Bootstrap components) -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
