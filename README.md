<html>
<head>
  <title>Happy Birthday ❤️</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      /* Premium golden gradient with subtle pattern */
      background: linear-gradient(135deg, #fff8dc, #ffd700);
      font-family: 'Great Vibes', cursive;
      color: #d6336c;
      text-align: center;
      background-image: radial-gradient(#ffe066 10%, transparent 11%);
      background-size: 40px 40px;
    }

    h1 {
      font-size: 64px;
      margin: 30px 0 10px;
      animation: glow 2s ease-in-out infinite alternate;
    }

    p {
      font-size: 32px;
      color: #000;
      margin: 0 0 40px;
    }

    @keyframes glow {
      from { text-shadow: 0 0 10px #ff4d6d, 0 0 20px #ff4d6d; }
      to { text-shadow: 0 0 20px #ff99ac, 0 0 30px #ff99ac; }
    }

    .album {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
      max-width: 1200px;
      margin: auto;
    }

    .album img {
      width: 100%;
      height: auto;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
      transition: transform 0.3s;
    }

    .album img:hover {
      transform: scale(1.05);
    }

    /* Play button styling */
    #playButton {
      background: #d6336c;
      color: white;
      border: none;
      padding: 15px 30px;
      font-size: 20px;
      border-radius: 8px;
      cursor: pointer;
      margin-bottom: 20px;
      font-family: 'Great Vibes', cursive;
    }
    #playButton:hover {
      background: #ff4d6d;
    }
  </style>
</head>
<body>

  <h1>🎂 Happy Birthday to mo Salu Guddu ❤️</h1>
  <p>My world shines brighter today because of you 💖</p>

  <!-- Play Music Button -->
  <button id="playButton">▶ Play Music</button>
  <audio id="bgMusic" loop>
    <source src="https://raw.githubusercontent.com/rudraprasadsangramsingh-pixel/Inviteforarpitajena143.github.io/main/10.mp3" type="audio/mpeg">
  </audio>

  <!-- Album Section -->
  <div class="album">
    <img src="https://raw.githubusercontent.com/rudraprasadsangramsingh-pixel/Inviteforarpitajena143.github.io/main/1.jpeg" alt="Memory 1">
    <img src="https://raw.githubusercontent.com/rudraprasadsangramsingh-pixel/Inviteforarpitajena143.github.io/main/2.jpeg" alt="Memory 2">
    <img src="https://raw.githubusercontent.com/rudraprasadsangramsingh-pixel/Inviteforarpitajena143.github.io/main/3.jpeg" alt="Memory 3">
    <img src="https://raw.githubusercontent.com/rudraprasadsangramsingh-pixel/Inviteforarpitajena143.github.io/main/4.jpeg" alt="Memory 4">
    <img src="https://raw.githubusercontent.com/rudraprasadsangramsingh-pixel/Inviteforarpitajena143.github.io/main/5.jpeg" alt="Memory 5">
    <img src="https://raw.githubusercontent.com/rudraprasadsangramsingh-pixel/Inviteforarpitajena143.github.io/main/6.jpeg" alt="Memory 6">
    <img src="https://raw.githubusercontent.com/rudraprasadsangramsingh-pixel/Inviteforarpitajena143.github.io/main/7.jpeg" alt="Memory 7">
    <img src="https://raw.githubusercontent.com/rudraprasadsangramsingh-pixel/Inviteforarpitajena143.github.io/main/8.jpeg" alt="Memory 8">
    <img src="https://raw.githubusercontent.com/rudraprasadsangramsingh-pixel/Inviteforarpitajena143.github.io/main/9.jpeg" alt="Memory 9">
  </div>

  <script>
    const playButton = document.getElementById('playButton');
    const bgMusic = document.getElementById('bgMusic');
    playButton.addEventListener('click', () => {
      bgMusic.play();
      playButton.style.display = 'none'; // hide button after playing
    });
  </script>

</body>
</html>
