# vanne
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Gorditas Vanne</title>
  <style>
    body {
      background: linear-gradient(to right, #f8b500, #ff6f00);
      color: #fff;
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #b71c1c;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3em;
      margin: 0;
    }

    .content {
      padding: 20px;
      display: flex;
      justify-content: center;
      align-items: flex-start;
      flex-wrap: wrap;
      position: relative;
    }

    .main-content {
      flex: 1;
      min-width: 300px;
      max-width: 700px;
    }

    .images-right {
      display: flex;
      flex-direction: column;
      gap: 20px;
      margin-left: 30px;
    }

    .images-right img {
      width: 300px;
      height: auto;
      border-radius: 10px;
      box-shadow: 0 0 10px #000;
    }

    .video-below-table video {
      width: 400px;
      height: auto;
      border-radius: 10px;
      box-shadow: 0 0 10px #000;
    }

    table {
      width: 70%;
      margin: 0 auto 30px auto;
      border-collapse: collapse;
      background-color: rgba(255, 255, 255, 0.95);
      color: #000;
      font-size: 1.1em;
    }

    table th,
    table td {
      padding: 14px;
      border: 1px solid #ccc;
    }

    table th {
      background-color: #ff9800;
      color: #fff;
    }

    .video-below-table {
      text-align: center;
      margin-top: 30px;
    }

    footer {
      background-color: #212121;
      color: #fff;
      text-align: center;
      padding: 20px;
    }

    footer a {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 20px;
      background-color: #4fc3f7;
      color: #000;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }

    footer a:hover {
      background-color: #039be5;
      color: #fff;
    }

    .footer-gif {
      margin-top: 20px;
    }

    .footer-gif img {
      width: 150px;
      height: auto;
    }
  </style>
</head>
<body>
  <header>
    <h1>GORDITAS VANNE</h1>
  </header>

  <div class="content">
    <div class="main-content">
      <h2 style="text-align: center;">¡Deliciosas comidas!</h2>

      <table>
        <thead>
          <tr>
            <th>Guisos Disponibles</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>Picadillo rojo</td></tr>
          <tr><td>Picadillo verde</td></tr>
          <tr><td>Rajas con requesón</td></tr>
          <tr><td>Chicharrón</td></tr>
          <tr><td>Frijoles con queso</td></tr>
          <tr><td>Huevo verde</td></tr>
          <tr><td>Huevo rojo</td></tr>
          <tr><td>Nopales con huevo</td></tr>
          <tr><td>Rajas con queso</td></tr>
          <tr><td>Deshebrada</td></tr>
        </tbody>
      </table>

      <div class="video-below-table">
        <video autoplay loop muted playsinline>
          <source src="gVANNE.mp4" type="video/mp4">
        </video>
      </div>
    </div>

    <div class="images-right">
      <img src="gordita 1.jpg" alt="Gordita lateral 1" />
      <img src="gordita 2.jpg" alt="Gordita lateral 2" />
      <img src="gordita 3.jpg" alt="Gordita lateral 3" />
      <img src="gordita 4.jpg" alt="Gordita lateral 4" />
    </div>
  </div>

  <footer>
    <p>&copy; 2025 Gorditas Vanne. Todos los derechos reservados.</p>
    <a href="https://www.facebook.com/share/1BWJwFoSEK" target="_blank">Síguenos en Facebook</a>

    <div class="footer-gif">
      <img src="gorditas_vanne_animado.gif" alt="GIF animado" />
    </div>
  </footer>
</body>
</html>
