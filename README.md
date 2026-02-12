<html>
<head>
  <title>Happy Hug Day ❤️</title>
  <!-- Romantic Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Georgia', serif;
      text-align: center;
      margin: 0;
      padding: 0;
      background: #fff0f5;
      color: #000;
    }
    section {
      display: none;
      padding: 60px 20px;
      min-height: 100vh;
    }
    section.active { display: block; }
    h1 { color: #000; }
    p { font-size: 18px; line-height: 1.6; color: #000; }

    /* Romantic font for continuous sentences */
    .invitation p {
      font-family: 'Great Vibes', cursive;
      font-size: 26px;
      line-height: 1.8;
    }

    /* Premium Heading for titles and labels */
    .premium-heading {
      font-family: 'Great Vibes', cursive;
      font-size: 32px;
      font-weight: bold;
      font-style: normal;
      color: #d6336c;
      margin-bottom: 20px;
    }

    .label-heading {
      font-family: 'Great Vibes', cursive;
      font-size: 24px;
      font-weight: bold;
      font-style: normal;
      color: #000;
      margin-top: 15px;
    }

    .heart-button {
      background-color: #ff4d6d; border: none; color: white; padding: 20px;
      font-size: 24px; border-radius: 50%; cursor: pointer; transition: transform 0.2s;
    }
    .heart-button:hover { transform: scale(1.2); background-color: #e63950; }
    .caption { margin-top: 15px; font-size: 18px; color: #000; font-weight: bold; }

    button, .map-button, .link-button {
      margin: 15px; padding: 15px 25px; font-size: 18px;
      background-color: #ff4d6d; color: white; border: none; border-radius: 8px;
      cursor: pointer; transition: transform 0.2s; text-decoration: none; display: inline-block;
    }
    button:hover, .map-button:hover, .link-button:hover {
      transform: scale(1.1); background-color: #e63950;
    }
  </style>
</head>
<body>

  <!-- Background music (hidden, starts after click) -->
  <audio id="bgMusic" loop style="display:none;">
    <source src="happinessinmusic-romantic-jazz-free-480577.mp3" type="audio/mpeg">
  </audio>

  <!-- Page 1 -->
  <section id="welcome" class="active">
    <h1>Happy Hug Day to my prettiest lady, Miss Wonderful!</h1>
    <p>Can't wait to wrap you in the biggest hug. ❤️</p>
    <button class="heart-button" onclick="startJourney()">❤️</button>
    <div class="caption">Adore me Baby!!</div>
  </section>

  <!-- Page 2 -->
  <section id="options">
    <h1>We welcome you Miss Wonderful to the world of AR & Company</h1>
    <p>I am Rudra and I am here to help you and serve you.<br>
       But before that, I ask your permission to choose one of these options.<br>
       Please choose what you would like to get served today:</p>

    <button onclick="showPage('dinner')">Option 1: Dinner under the stars</button>
    <button onclick="showPage('movie')">Option 2: Movie night</button>
    <button onclick="showPage('adventure')">Option 3: Surprise adventure with our company</button>
  </section>

  <!-- Page 3A: Dinner Invitation -->
  <section id="dinner" class="invitation">
    <div class="premium-heading">Dinner Under the Stars</div>
    <p>You are hereby highly invited to an evening of enchantment...</p>
    <div class="label-heading">Date:</div>
    <p>14th February – the day our hearts beat as one under the stars.</p>
    <div class="label-heading">Venue:</div>
    <p>Cabana by Regal, KIIT Rd, Bhubaneswar</p>
    <p>Prepare to be swept into romance eternal. 💕</p>

    <a href="https://share.google/fybSnltHt6ULYX8O8" target="_blank" class="map-button">
      Click here to view the place virtually
    </a>
    <br><br>
    <button onclick="showPage('options')">⬅ Back to Options</button>
  </section>

  <!-- Page 3B: Movie Night Invitation -->
  <section id="movie" class="invitation">
    <div class="premium-heading">🎬✨ Movie Night Golden Invitation ✨🎬</div>
    <p><strong>Miss Arpita Jena</strong><br>You are cordially invited...</p>
    <div class="label-heading">Event:</div>
    <p>Bara Badhu Screening Premiere</p>
    <div class="label-heading">Date:</div>
    <p>Saturday, 14th February</p>
    <div class="label-heading">Time:</div>
    <p>7:00 PM Sharp</p>
    <div class="label-heading">Venue:</div>
    <p>Maharaja Picture Palace [Christie 4K], Bhubaneswar</p>
    <div class="label-heading">RSVP:</div>
    <p>Your presence is non-negotiable, my love.</p>
    <p>Tonight, the movie stars fade – because you'll outshine them all.</p>
    <p>With eternal admiration,<br>Your Leading Man<br>Rudra</p>

    <p>Till then please enjoy the trailer:</p>
    <a href="https://www.youtube.com/watch?v=JiBjnGMaw2Y" target="_blank" class="link-button">
      Watch Trailer 🎬
    </a>
    <p>We hope you will enjoy it.</p>
    <br>
    <button onclick="showPage('options')">⬅ Back to Options</button>
  </section>

  <!-- Page 3C: Surprise Adventure Invitation -->
  <section id="adventure" class="invitation">
    <div class="premium-heading">🌟✨ Surprise Adventure Passport ✨🌟</div>
    <p><strong>Dearest Miss Arpita Jena,</strong><br>Your heart's greatest explorer calls...</p>
    <div class="label-heading">Date:</div>
    <p>Sunday Morning (Pack for wonder & wander!)</p>
    <div class="label-heading">Mission:</div>
    <p>Pack your bags, dreams, and that radiant smile.</p>
    <p>Venue, time, and magical details will be revealed exclusively by AR&Company.</p>
    <p>Adventure awaits. Are you ready, my love?<br>Issued by your forever companion,<br><strong>Mr. Rudra Sangram Singh</strong></p>

    <p>Pause! Enjoy the song till the details are being shared by AR& Company:</p>
    <a href="https://www.youtube.com/watch?v=oZ7PnR_ZKRE" target="_blank" class="link-button">
      Play Song 🎵
    </a>
    <br><br>
    <button onclick="showPage('options')">⬅ Back to Options</button>
  </section>

  <script>
    function showPage(pageId) {
      document.querySelectorAll('section').forEach(sec => sec.classList.remove('active'));
      document.getElementById(pageId).classList.add('active');
    }
    function startJourney() {
      showPage('options');
      const music = document.getElementById('bgMusic');
      music.play().catch(err => {
        console.log("Music play blocked:", err);
      });
    }
  </script>

</body>
</html>
