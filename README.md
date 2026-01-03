<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mi Web de Manga</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #0f0f0f;
      color: #fff;
    }
    header {
      background-color: #1c1c1c;
      padding: 15px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      font-size: 24px;
      color: #ff3c3c;
    }
    nav a {
      color: #ccc;
      margin-left: 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      color: #ff3c3c;
    }
    .container {
      max-width: 1200px;
      margin: auto;
      padding: 20px;
    }
    .section {
      margin-bottom: 40px;
    }
    .section h2 {
      border-left: 5px solid #ff3c3c;
      padding-left: 10px;
      margin-bottom: 20px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
      gap: 15px;
    }
    .card {
      background-color: #1a1a1a;
      border-radius: 8px;
      overflow: hidden;
      cursor: pointer;
      transition: transform 0.2s;
    }
    .card:hover {
      transform: scale(1.05);
    }
    .card img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }
    .card .info {
      padding: 10px;
    }
    .card .info h3 {
      font-size: 14px;
      margin: 0 0 5px;
    }
    .card .info span {
      font-size: 12px;
      color: #aaa;
    }
    footer {
      background-color: #1c1c1c;
      text-align: center;
      padding: 15px;
      font-size: 13px;
      color: #aaa;
    }
  </style>
</head>
<body>

<header>
  <h1>MiManga</h1>
  <nav>
    <a href="#emision">Emisión</a>
    <a href="#completo">Completo</a>
  </nav>
</header>

<div class="container">

  <!-- SECCIÓN EMISIÓN -->
  <section class="section" id="emision">
    <h2>📺 En Emisión</h2>
    <div class="grid">
      <div class="card">
        <img src="https://via.placeholder.com/300x450" alt="Manga">
        <div class="info">
          <h3>Título en emisión</h3>
          <span>Capítulo 12</span>
        </div>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x450" alt="Manga">
        <div class="info">
          <h3>Otro manga</h3>
          <span>Capítulo 8</span>
        </div>
      </div>
    </div>
  </section>

  <!-- SECCIÓN COMPLETO -->
  <section class="section" id="completo">
    <h2>📚 Completos</h2>
    <div class="grid">
      <div class="card">
        <img src="https://via.placeholder.com/300x450" alt="Manga">
        <div class="info">
          <h3>Manga completo</h3>
          <span>Finalizado</span>
        </div>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x450" alt="Manga">
        <div class="info">
          <h3>Serie terminada</h3>
          <span>100 capítulos</span>
        </div>
      </div>
    </div>
  </section>

</div>

<footer>
  © 2026 MiManga — Sitio de lectura
</footer>

</body>
</html>
