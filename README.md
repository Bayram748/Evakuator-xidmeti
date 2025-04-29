
<html lang="az">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tez Yardım Evakuator</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #ffcc00;
      color: #000;
    }
    header {
      text-align: center;
      padding: 30px 15px;
    }
    header h1 {
      font-size: 36px;
      margin: 0;
    }
    header p {
      font-size: 18px;
      margin: 5px 0 0;
    }
    .banner {
      background-color: #000;
      color: #fff;
      padding: 20px;
      text-align: center;
      font-size: 24px;
      font-weight: bold;
    }
    .slideshow-container {
      position: relative;
      max-width: 90%;
      margin: 20px auto;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    }
    .slide {
      display: none;
      width: 100%;
    }
    .services {
      padding: 20px;
      font-size: 18px;
    }
    .services ul {
      list-style: none;
      padding: 0;
    }
    .services li::before {
      content: "✓ ";
      color: #000;
    }
    .call-button {
      display: block;
      background-color: #000;
      color: #ffcc00;
      text-align: center;
      padding: 15px;
      font-size: 22px;
      text-decoration: none;
      font-weight: bold;
      margin: 20px auto;
      width: 90%;
      border-radius: 8px;
    }
    footer {
      background-color: #000;
      color: #fff;
      text-align: center;
      padding: 10px;
      font-size: 14px;
    }
    .striped {
      height: 20px;
      background: repeating-linear-gradient(
        45deg,
        #000,
        #000 20px,
        #ffcc00 20px,
        #ffcc00 40px
      );
    }
  </style>
</head>
<body>
<body>

<header style="text-align: center; padding: 20px;">
  <img src="Evakuator.png" alt="Evakuator Xidməti Loqosu" style="height: 80px;">
</header>
  <header>
    <h1>Tez Yardım Evakuator</h1>
    <p>Gəncə və ətrafında 24/7 xidmətinizdəyik</p>
  </header>

  <div class="banner">
    Sürətli və etibarlı evakuator xidməti!
  </div>

  <div class="slideshow-container">
    <img class="slide" src="IMG-20250327-WA0001.jpg" alt="Evakuator 1">
    <img class="slide" src="IMG-20250327-WA0005.jpg" alt="Evakuator 2">
    <img class="slide" src="IMG-20250327-WA0003.jpg" alt="Evakuator 3"> 
    <img class="slide" src="IMG-20250327-WA0006.jpg" alt="Evakuator 4">
    <img class="slide" src="IMG-20250327-WA0008.jpg" alt="Evakuator 5">
    <img class="slide" src="IMG-20250327-WA0004.jpg" alt="Evakuator 6">
    <img class="slide" src="IMG-20250425-WA0024.jpg" alt="Evakuator 7">
  </div>

  <div class="services">
    <h2>Xidmətlərimiz</h2>
    <ul>
      <li>24 saat evakuator xidməti</li>
      <li>Gəncə və ətraf rayonlara operativ xidmət</li>
      <li>Sərfəli qiymətlərlə avtomobil daşınması</li>
    </ul>
  </div>

  <a class="call-button" href="tel:+994552424275">Zəng et: +994 55 242 42 75</a>

  <div class="striped"></div>

  <footer>
    © 2025 Tez Yardım Evakuator - Bütün hüquqlar qorunur.
  </footer>

  <script>
    let slideIndex = 0;
    showSlides();

    function showSlides() {
      let slides = document.getElementsByClassName("slide");
      for (let i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";  
      }
      slideIndex++;
      if (slideIndex > slides.length) {slideIndex = 1}    
      slides[slideIndex-1].style.display = "block";  
      setTimeout(showSlides, 3000); // hər 3 saniyədə dəyişir
    }
  </script>

</body>
</html>
