
<html>
<head>
  <title>Happy Hug Day ❤️</title>
  <style>
    body {
      font-family: 'Georgia', serif;
      text-align: center;
      margin: 0;
      padding: 0;
      background: #fff0f5;
      color: #333;
    }
    section {
      display: none;
      padding: 60px 20px;
      min-height: 100vh;
    }
    section.active {
      display: block;
    }
    h1 { color: #d6336c; }
    p { font-size: 18px; line-height: 1.6; }

    .heart-button {
      background-color: #ff4d6d; border: none; color: white; padding: 20px;
      font-size: 24px; border-radius: 50%; cursor: pointer; transition: transform 0.2s;
    }
    .heart-button:hover { transform: scale(1.2); background-color: #e63950; }
    .caption { margin-top: 15px; font-size: 18px; color: #d6336c; font-weight: bold; }

    button {
      margin: 15px; padding: 15px 25px; font-size: 18px;
      background-color: #ff4d6d; color: white; border: none; border-radius: 8px;
      cursor: pointer; transition: transform 0.2s;
    }
    button:hover { transform: scale(1.1); background-color: #e63950; }

    .map-button {
      margin-top: 30px; padding: 15px 25px; font-size: 18px;
      background-color: #ff4d6d; color: white; border: none; border-radius: 8px;
      cursor: pointer; transition: transform 0.2s; text-decoration: none; display: inline-block;
    }
    .map-button:hover { transform: scale(1.1); background-color: #e63950; }

    /* Background for options page */
    #options::before {
      content: ""; position: absolute; top: 0; left: 0; width: 100%; height: 100%;
      background: url(['your-image.jpeg'](https://github.com/rudraprasadsangramsingh-pixel/Inviteforarpitajena143.github.io/blob/main/WhatsApp%20Image%202026-02-12%20at%2011.46.06%20AM.jpeg)) no-repeat center center fixed;
      background-size: cover; opacity: 0.3; z-index: -1;
    }
  </style>
</head>
<body>

  <!-- Page 1 -->
  <section id="welcome" class="active">
    <h1>Happy Hug Day to my prettiest lady, Miss Wonderful!</h1>
    <p>Can't wait to wrap you in the biggest hug. ❤️</p>
    <button class="heart-button" onclick="showPage('options')">❤️</button>
    <div class="caption">Adore me Baby!!</div>
  </section>

  <!-- Page 2 -->
  <section id="options">
    <h1>We welcome you Miss Wonderful to the world of AR & Company</h1>
    <p>I am Rudra and I am here to help you and serve you.<br>
       But before that, I ask your permission to choose one of these options.<br>
       Please choose what you would like to get served today:</p>

    <button onclick="showPage('dinner')">Option 1: Dinner under the stars</button>
    <button onclick="alert('Movie night 🎬 - Saturday, 14th February, 7 PM, cozy setup at home!')">Option 2: Movie night</button>
    <button onclick="alert('Surprise adventure ✨ - Sunday morning, be ready!')">Option 3: Surprise adventure with our company</button>

    <audio autoplay loop>
      <source src="[romantic-jazz.mp3](https://github.com/rudraprasadsangramsingh-pixel/Inviteforarpitajena143.github.io/blob/main/happinessinmusic-romantic-jazz-free-480577.mp3)" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </section>

  <!-- Page 3 -->
  <section id="dinner">
    <h1>My Dearest Love,</h1>
    <p>
      You are hereby highly invited to an evening of enchantment at <strong>Cabana by Regal</strong>, 
      nestled along KIIT Rd, Chandaka Industrial Estate, Bajrang Vihar, Patia, Bhubaneswar, Odisha 751024.
    </p>
    <p><strong>Date:</strong> 14th February – the day our hearts beat as one under the stars.</p>
    <p>
      Our best-in-class driver, the impeccable <strong>Mr. Rudra Sangram Singh</strong>, shall whisk you away 
      in utmost elegance to this dreamlike haven, straight from your preferred spot.
    </p>
    <p>Prepare to be swept into romance eternal. 💕</p>

    <a href="https://share.google/fybSnltHt6ULYX8O8" target="_blank" class="map-button">
      Click here to view the place virtually
    </a>
  </section>

  <script>
    function showPage(pageId) {
      document.querySelectorAll('section').forEach(sec => sec.classList.remove('active'));
      document.getElementById(pageId).classList.add('active');
    }
  </script>

</body>
</html>
