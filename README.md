# try
my-girl-birthday
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Happy Birthday, My Girl ❤️</title>
  <style>
    body {
      margin: 0;
      font-family: Georgia, serif;
      background: #10090e;
      color: white;
      text-align: center;
    }
    .hero {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 25px;
      box-sizing: border-box;
      background: radial-gradient(circle, #54142c, #10090e 70%);
    }
    h1 {
      color: #ff719f;
      font-size: 42px;
    }
    p {
      line-height: 1.8;
      max-width: 500px;
    }
    button {
      background: #ff477e;
      color: white;
      border: 0;
      border-radius: 25px;
      padding: 14px 24px;
      font-size: 16px;
      cursor: pointer;
    }
    #surprise {
      display: none;
      margin-top: 25px;
      color: #ffd3e1;
    }
  </style>
</head>
<body>
  <section class="hero">
    <p>A LITTLE SURPRISE FOR SOMEONE SPECIAL ❤️</p>
    <h1>Happy Birthday, My Girl! 🎂</h1>
    <p>
      Today is all about you.
      You make ordinary moments feel special,
      and I hope your birthday brings you
      as much happiness as you bring into my life.
    </p>
    <button onclick="showSurprise()">
      Open Your Surprise 💌
    </button>
    <div id="surprise">
      <h2>You Are So Special to Me ❤️</h2>
      <p>
        Happy birthday, my love!
        May your new year be full of beautiful memories,
        laughter, and dreams coming true.
        I'm so happy to celebrate you!
      </p>
      <p>With love, always ❤️</p>
    </div>
  </section>
  <script>
    function showSurprise() {
      document.getElementById("surprise").style.display = "block";
    }
  </script>
</body>
</html>
