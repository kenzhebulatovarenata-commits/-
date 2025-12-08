<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Мои анимации</title>
  <style>
    body {
      font-family: sans-serif;
      max-width: 800px;
      margin: auto;
      padding: 20px;
      line-height: 1.5;
    }
    video {
      width: 100%;
      margin-bottom: 20px;
      border-radius: 5px;
      pointer-events: none; /* человек не сможет нажимать и случайно открывать fullscreen */
    }
    p {
      font-size: 18px;
      margin-bottom: 20px;
    }
  </style>
</head>
<body>

  <!-- Блок 1 -->
  <video autoplay muted playsinline loop>
    <source src="vid 1.mp4" type="video/mp4">
  </video>
  <p>Текст между анимациями 1 и 2</p>

  <!-- Блок 2 -->
  <video autoplay muted playsinline loop>
    <source src="vid 2.mp4" type="video/mp4">
  </video>
  <p>Текст после второй анимации</p>

  <!-- Блок 3 -->
  <video autoplay muted playsinline loop>
    <source src="animation3.mp4" type="video/mp4">
  </video>
  <p>Текст после третьей анимации</p>

  <!-- Шаблон для добавления новых -->
  <!--
  <video autoplay muted playsinline loop>
    <source src="название.mp4" type="video/mp4">
  </video>
  <p>Текст между видео</p>
  -->

</body>
</html>
