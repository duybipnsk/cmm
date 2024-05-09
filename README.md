<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Text Animation</title>
<style>
  @keyframes neon {
    0% {
      text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 15px #fff, 0 0 20px #ffcc00, 0 0 30px #ffcc00, 0 0 40px #ffcc00, 0 0 50px #ffcc00, 0 0 75px #ffcc00;
    }
    50% {
      text-shadow: none;
    }
    100% {
      text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 15px #fff, 0 0 20px #ffcc00, 0 0 30px #ffcc00, 0 0 40px #ffcc00, 0 0 50px #ffcc00, 0 0 75px #ffcc00;
    }
  }

  h1 {
    font-size: 4em;
    text-align: center;
    color: #fff;
    font-family: 'Arial', sans-serif;
    animation: neon 2s infinite alternate;
  }
</style>
</head>
<body style="background-color: #333;">
  <h1>Mày Vô Wed Này Là Mày Ngu Như Con Chó Đỉ Mẹ Mày Ra</h1>
</body>
</html>
