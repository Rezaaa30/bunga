<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bunga Cantik</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(to top right, #fbc2eb, #a6c1ee);
    }
    .flower {
      position: relative;
      width: 200px;
      height: 200px;
    }
    .petal {
      position: absolute;
      top: 50%;
      left: 50%;
      width: 80px;
      height: 120px;
      background: pink;
      border-radius: 50% 50% 0 0;
      transform-origin: 50% 100%;
    }
    .petal:nth-child(1) { transform: rotate(0deg) translateY(-70px); }
    .petal:nth-child(2) { transform: rotate(72deg) translateY(-70px); }
    .petal:nth-child(3) { transform: rotate(144deg) translateY(-70px); }
    .petal:nth-child(4) { transform: rotate(216deg) translateY(-70px); }
    .petal:nth-child(5) { transform: rotate(288deg) translateY(-70px); }
    .center {
      position: absolute;
      top: 50%;
      left: 50%;
      width: 70px;
      height: 70px;
      background: yellow;
      border-radius: 50%;
      transform: translate(-50%, -50%);
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>
  <div class="flower">
    <div class="petal"></div>
    <div class="petal"></div>
    <div class="petal"></div>
    <div class="petal"></div>
    <div class="petal"></div>
    <div class="center"></div>
  </div>
</body>
</html>
