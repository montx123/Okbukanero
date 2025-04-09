<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Okey Bukanero Radio</title>
  <style>
    body {
      background-color: #121212;
      color: #ffffff;
      font-family: Arial, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
    }

    h1 {
      color: #00ffe1;
      margin-bottom: 20px;
    }

    .player {
      background: #1e1e1e;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px #00ffe1;
    }

    audio {
      width: 300px;
      outline: none;
    }
  </style>
</head>
<body>
  <h1>Okey Bukanero Radio</h1>
  <div class="player">
    <audio id="radioPlayer" controls>
      <source src="https://stream.zeno.fm/utaaqemlboovv" type="audio/mpeg">
      Tu navegador no soporta audio HTML5.
    </audio>
  </div>
</body>
</html>
  
