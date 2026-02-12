<!DOCTYPE html>
<html>
<head>
  <title>Welcome Miss Wonderful</title>
  <style>
    body {
      font-family: 'Georgia', serif;
      text-align: center;
      margin: 0;
      padding: 0;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      color: #fff;
      position: relative;
      z-index: 1;
    }

    /* Background image with dim overlay */
    body::before {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: url('your-image.jpeg') no-repeat center center fixed;
      background-size: cover;
      opacity: 0.3; /* controls dimness */
      z-index: -1;
    }

    h1 {
      font-size: 28px;
      margin-bottom: 20px;
    }
    p {
      font-size: 18px;
      margin-bottom: 30px;
    }
    button {
      margin: 15px;
      padding: 15px 25px;
      font-size: 18px;
      background-color: #ff4d6d;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: transform 0.2s;
    }
    button:hover {
      transform: scale(1.1);
      background-color: #e63950;
    }
  </style>
</head>
<body>
  <h1>We welcome you Miss Wonderful to the world of AR & Company</h1>
  <p>I am Rudra and I am here to help you and serve you.<br>
     But before that, I ask your permission to choose one of these options.<br>
     Please choose what you would like to get served today:</p>

  <button onclick="alert('Dinner under the stars 🌌 - Saturday 7 PM at our favorite spot!')">Option 1: Dinner under the stars</button>
  <button onclick="alert('Movie night 🎬 - Saturday, 14th February, 7 PM, cozy setup at home!')">Option 2: Movie night</button>
  <button onclick="alert('Surprise adventure ✨ - Sunday morning, be ready!')">Option 3: Surprise adventure with our company</button>

  <!-- Background music -->
  <audio autoplay loop>
    <source src="romantic-jazz.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>
</body>
</html>
