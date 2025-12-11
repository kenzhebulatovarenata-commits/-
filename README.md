АРКИ СРЕДИ НАС
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Мои анимации</title>
  <style>
    body {
      font-family: Inter Tight;
      max-width: 800px;
      margin: auto;
      padding: 20px;
      line-height: 2.5;
    }
    video {
      width: 100%;
      margin-bottom: 20px;
      border-radius: 5px;
      pointer-events: none;
    }
    p {
      font-size: 18px;
      margin-bottom: 20px;
    }
  </style>
</head>
<body>

  <video class="autoplay" muted playsinline loop>
    <source src="vid 1.mp4" type="video/mp4">
  </video>
  <p>Текст между анимациями 1 и 2</p>

  <video class="autoplay" muted playsinline loop>
    <source src="vid 2.mp4" type="video/mp4">
  </video>
  <p>Текст после второй анимации</p>

  <video class="autoplay" muted playsinline loop>
    <source src="vid 3.mp4" type="video/mp4">
  </video>
  <p>Текст после третьей анимации</p>
  
  <video class="autoplay" muted playsinline loop>
    <source src="vid 4.mp4" type="video/mp4">
  </video>
  <p>Текст после третьей анимации</p>

  <video class="autoplay" muted playsinline loop>
    <source src="vid 5.mp4" type="video/mp4">
  </video>
  <p>Текст после третьей анимации</p>

  <video class="autoplay" muted playsinline loop>
    <source src="vid 6.mp4" type="video/mp4">
  </video>
  <p>Текст после третьей анимации</p>

  <video class="autoplay" muted playsinline loop>
    <source src="vid 7.mp4" type="video/mp4">
  </video>
  <p>Текст после третьей анимации</p>

  <video class="autoplay" muted playsinline loop>
    <source src="vid 8.mp4" type="video/mp4">
  </video>
  <p>Текст после третьей анимации</p>

  <video class="autoplay" muted playsinline loop>
    <source src="vid 9.mp4" type="video/mp4">
  </video>
  <p>Текст после третьей анимации</p>

  <video class="autoplay" muted playsinline loop>
    <source src="vid 10.mp4" type="video/mp4">
  </video>
  <p>Текст после третьей анимации</p>

  <video class="autoplay" muted playsinline loop>
    <source src="vid 11.mp4" type="video/mp4">
  </video>
  <p>Текст после третьей анимации</p>

  <video class="autoplay" muted playsinline loop>
    <source src="vid 12.mp4" type="video/mp4">
  </video>
  <p>Текст после третьей анимации</p>

  <video class="autoplay" muted playsinline loop>
    <source src="vid 13.mp4" type="video/mp4">
  </video>
  <p>Текст после третьей анимации</p>

  <video class="autoplay" muted playsinline loop>
    <source src="vid 14.mp4" type="video/mp4">
  </video>
  <p>Текст после третьей анимации</p>

  <video class="autoplay" muted playsinline loop>
    <source src="vid 15.mp4" type="video/mp4">
  </video>
  <p>Текст после третьей анимации</p>

  <video class="autoplay" muted playsinline loop>
    <source src="vid 16.mp4" type="video/mp4">
  </video>
  <p>Текст после третьей анимации</p>

  <script>
    // насильный автоплей
    document.querySelectorAll('video.autoplay').forEach(v => {
      v.addEventListener('canplay', () => {
        v.play().catch(() => {});
      });
    });

    // запасной вариант — попытаться проиграть через 1 секунду
    setTimeout(() => {
      document.querySelectorAll('video.autoplay').forEach(v => {
        v.play().catch(() => {});
      });
    }, 1000);
  </script>

</body>
</html>
