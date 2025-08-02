# happy-gf-day
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Happy GF Day</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      background: linear-gradient(to top right, #ffd6ec, #ffe2f7);
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      font-family: 'Segoe UI', sans-serif;
      color: #ff2e8d;
      overflow: hidden;
    }

    h1 {
      font-size: 2.5em;
      text-align: center;
    }

    .petal {
      position: absolute;
      width: 20px;
      height: 20px;
      background: pink;
      border-radius: 50%;
      opacity: 0.8;
      animation: fall 5s linear infinite;
    }

    @keyframes fall {
      0% {transform: translateY(-10vh) rotate(0);}
      100% {transform: translateY(110vh) rotate(360deg);}
    }
  </style>
</head>
<body>
  <h1>Happy GF Day Putriii ❤️</h1>
  <audio autoplay loop>
    <source src="https://docs.google.com/uc?export=download&id=1-hR-zlEpdhtLM_k2E5UgAYSwV3BPydNS" type="audio/mp3">
    Your browser does not support the audio tag.
  </audio>

  <script>
    for (let i = 0; i < 40; i++) {
      const petal = document.createElement("div");
      petal.classList.add("petal");
      petal.style.left = Math.random() * 100 + "vw";
      petal.style.animationDuration = (Math.random() * 3 + 2) + "s";
      document.body.appendChild(petal);
    }
  </script>
</body>
</html>
