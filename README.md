
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Galeria de Personagens</title>
  <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@600&family=Poppins:wght@400;600&display=swap" rel="stylesheet">

  <style>
    body {
      background-color: #0a0a0a;
      background-image: radial-gradient(#111 1px, transparent 1px);
      background-size: 40px 40px;
      color: #e1e1e1;
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 20px;
      overflow-x: hidden;
    }

    /* FILTRO ÚNICO */
    .filtros-wrap {
      margin-bottom: 20px;
    }

    .filtros button {
      font-family: 'Quicksand', sans-serif;
      font-weight: 600;
      background-color: #1f1f1f;
      color: #e1e1e1;
      border: none;
      padding: 10px 15px;
      border-radius: 12px;
      cursor: pointer;
      font-size: 1rem;
    }

    .filtros button.active {
      background-color: #e1e1e1;
      color: #0a0a0a;
    }

    /* GALERIA */
    .gallery-wrap {
      overflow-x: auto;
      white-space: nowrap;
      padding-bottom: 15px;
    }

    .gallery-personagens {
      display: inline-flex;
      gap: 30px;
      align-items: center;
    }

    /* PERSONAGEM */
    .personagem {
      background-color: #151515;
      border-radius: 18px;
      text-align: center;
      padding: 10px;
      box-shadow: 0 0 15px rgba(255,255,255,0.3);
      display: inline-block;
      animation: flutuar 3s ease-in-out infinite;
    }

    /* Animação suave */
    @keyframes flutuar {
      0% { transform: translateY(0px); }
      50% { transform: translateY(-10px); }
      100% { transform: translateY(0px); }
    }

    .personagem img {
      border-radius: 15px;
      display: block;
      max-height: 400px;
      max-width: 300px;
      margin: auto;
    }

    .personagem h2 {
      margin-top: 10px;
      color: #e1e1e1;
      font-family: 'Quicksand', sans-serif;
      font-size: 1.2em;
    }

  </style>
</head>

<body>

  <!-- FILTRO ÚNICO -->
  <div class="filtros-wrap">
    <div class="filtros">
      <button class="active">Todos</button>
    </div>
  </div>

  <!-- PERSONAGEM ÚNICO -->
  <div class="gallery-wrap">
    <div class="gallery-personagens">

      <div class="personagem">
        <img src="https://i.postimg.cc/1zDPz9vb/Gemini-Generated-Image-986owu986owu986o.png">
        <h2>Mike</h2>
      </div>

    </div>
  </div>

</body>
</html>