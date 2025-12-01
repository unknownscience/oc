<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Galeria OC</title>
  <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@600&family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      background-color: #fff;
      color: #b71c1c;
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 20px;
      overflow-x: hidden;
    }

    h1 {
      text-align: center;
      font-family: 'Quicksand', sans-serif;
      font-size: 2em;
      margin-bottom: 30px;
      color: #b71c1c;
    }

    /* CARROSSEL */
    .carousel-wrap {
      display: flex;
      overflow-x: auto;
      scroll-behavior: smooth;
      gap: 20px;
      padding-bottom: 20px;
    }

    .carousel-card {
      flex: 0 0 auto;
      width: 300px;
      border-radius: 20px;
      background-color: #fff;
      border: 2px solid #b71c1c;
      box-shadow: 0 5px 15px rgba(183,28,28,0.3);
      transition: transform 0.3s, box-shadow 0.3s;
      cursor: pointer;
      text-align: center;
      padding: 15px;
    }

    .carousel-card:hover {
      transform: translateY(-10px) rotateZ(1deg);
      box-shadow: 0 15px 25px rgba(183,28,28,0.5);
    }

    .carousel-card img {
      width: 100%;
      border-radius: 15px;
      margin-bottom: 10px;
    }

    .carousel-card h2 {
      font-family: 'Quicksand', sans-serif;
      color: #b71c1c;
      margin: 0;
    }

    /* Botão de Todos */
    .filter-btn {
      display: block;
      margin: 0 auto 30px auto;
      padding: 10px 20px;
      border-radius: 12px;
      border: 2px solid #b71c1c;
      background-color: #fff;
      color: #b71c1c;
      font-family: 'Quicksand', sans-serif;
      font-weight: 600;
      cursor: pointer;
      transition: background-color 0.2s, color 0.2s;
    }

    .filter-btn:hover {
      background-color: #b71c1c;
      color: #fff;
    }
  </style>
</head>
<body>

  <h1>Galeria OC</h1>

  <button class="filter-btn">Todos</button>

  <div class="carousel-wrap">
    <div class="carousel-card">
      <img src="https://i.postimg.cc/1zDPz9vb/Gemini-Generated-Image-986owu986owu986o.png" alt="Seu OC">
      <h2>Mike</h2>
    </div>
    <!-- Você pode duplicar esse card e mudar as imagens/lore depois -->
  </div>

</body>
</html>