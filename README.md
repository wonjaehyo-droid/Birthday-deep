birthday deep💕

<!DOCTYPE html>
<html>
<head>
  <title>Happy Birthday Deepuuu 💖</title>
  <style>
    body { text-align: center; background: linear-gradient(to right, #ff9a9e, #fad0c4); font-family: Arial; padding: 30px; }
    .box { background: white; padding: 20px; border-radius: 15px; max-width: 600px; margin: auto; box-shadow: 0 0 10px rgba(0,0,0,0.2); }
    h1 { color: #ff4d6d; }
    #slideshow { width: 300px; height: 300px; margin: 20px auto; border-radius: 15px; box-shadow: 0 0 10px rgba(0,0,0,0.3); }
  </style>
</head>
<body>

<div class="box">
  <h1>🎂 Happy Birthday Deepuuu 💖</h1>
  <p>
    Deepak,<br>
    Sach bolu… main tumhare saath bahut khush rehti hoon.<br>
    Tumhari smile mujhe itni achchi lagti hai ki mood instantly better ho jata hai.<br>
    Tumhara gaana sunna… woh alag hi feeling deta hai.<br>
    Kabhi kabhi tumhari yaad bhi aati hai… kaafi zyada.<br>
    Bas aise hi hamesha smile karte rehna.<br>
    💖
  </p>

  <!-- Slideshow -->
  <img id="slideshow" src="deep5244__14050109_185847271.jpg">

  <!-- Audio -->
  <audio autoplay loop controls>
    <source src="song.mp3" type="audio/mpeg">
  </audio>
</div>

<script>
  const images = [
    "deep5244__14050109_185847271.jpg",
    "SAVE_20250929_224254.jpg",
    "IMG-20260211-WA0006.jpg"
  ];
  let index = 0;
  const slide = document.getElementById("slideshow");
  setInterval(() => {
    index = (index + 1) % images.length;
    slide.src = images[index];
  }, 3000);
</script>

</body>
</html>
