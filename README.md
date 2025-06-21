<!DOCTYPE html>
<html>
<head>
  <title>Сюрприз 😈</title>
  <style>
    body {
      background-color: black;
      color: white;
      text-align: center;
      font-family: sans-serif;
      margin-top: 100px;
    }
    img {
      max-width: 100%;
    }
  </style>
</head>
<body>
  <h1>Подарок от друга 🎁</h1>
  <button onclick="showScreamer()">Открыть</button>

  <div id="screamer" style="display:none;">
    <img src="https://i.imgur.com/BO3XWqv.jpg" alt="BOO!">
    <audio autoplay>
      <source src="https://www.soundjay.com/human/screaming-woman-01.mp3" type="audio/mpeg">
    </audio>
  </div>

  <script>
    function showScreamer() {
      document.body.innerHTML = document.getElementById('screamer').outerHTML;
    }
  </script>
</body>
</html>
