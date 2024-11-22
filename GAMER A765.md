<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Official website for GAMER A765">
  <title>GAMER A765</title>
  <style>
    /* General Styling */
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #121212, #1e2a47); /* Dark gradient background */
      color: #fff;
      overflow-x: hidden;
      scroll-behavior: smooth;
      cursor: url('https://www.example.com/futuristic-cursor.png'), auto; /* Custom futuristic cursor */
      background-size: cover;
      background-attachment: fixed;
    }

    /* Parallax Background */
    .parallax {
      position: relative;
      background: url('https://www.example.com/tech-bg.jpg') no-repeat center center;
      background-size: cover;
      height: 100vh;
      overflow: hidden;
      z-index: -1;
    }

    /* Header Styling */
    header {
      background: linear-gradient(to left, #0a1b34, #1e90ff);
      color: white;
      padding: 100px 20px;
      text-align: center;
      box-shadow: 0 6px 30px rgba(0, 0, 0, 0.8);
      border-bottom: 5px solid #1e90ff;
    }
    header h1 {
      font-size: 3.5em;
      text-transform: uppercase;
      letter-spacing: 5px;
      text-shadow: 0 0 25px rgba(30, 144, 255, 0.9), 0 0 15px rgba(255, 255, 255, 0.3);
      animation: neonGlow 1.5s ease-in-out infinite alternate;
    }
    header p {
      font-size: 1.4em;
      color: #bbb;
      margin-top: 15px;
      letter-spacing: 2px;
      text-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
    }

    /* Navigation Bar Styling */
    nav {
      display: flex;
      justify-content: center;
      background-color: #0a1b34;
      padding: 15px 0;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.6);
      position: sticky;
      top: 0;
      z-index: 10;
    }
    nav a {
      color: #fff;
      padding: 15px 30px;
      text-decoration: none;
      text-align: center;
      font-size: 1.2em;
      transition: all 0.3s ease;
      position: relative;
    }
    nav a:hover {
      background-color: #1e90ff;
      color: #121212;
      transform: scale(1.1);
      box-shadow: 0 0 15px rgba(30, 144, 255, 0.8);
      text-shadow: 0 0 10px rgba(30, 144, 255, 0.9);
    }
    nav a::after {
      content: '';
      position: absolute;
      width: 100%;
      height: 3px;
      background-color: #1e90ff;
      bottom: 0;
      left: 0;
      transform: scaleX(0);
      transform-origin: bottom right;
      transition: transform 0.3s ease-in-out;
    }
    nav a:hover::after {
      transform: scaleX(1);
      transform-origin: bottom left;
    }

    /* Container Styling */
    .container {
      padding: 50px 20px;
      max-width: 1200px;
      margin: 0 auto;
      position: relative;
    }

    /* Video Section Styling */
    .video-embed {
      text-align: center;
      margin-top: 40px;
      transition: transform 0.3s ease;
    }
    iframe {
      border-radius: 15px;
      box-shadow: 0 6px 20px rgba(0, 0, 0, 0.8);
    }
    iframe:hover {
      transform: scale(1.05) rotate(2deg); /* 3D tilt effect */
    }

    /* About Section Styling */
    section {
      margin-top: 50px;
      padding: 30px;
      border-radius: 20px;
      background-color: rgba(0, 0, 0, 0.7);
      box-shadow: 0 8px 30px rgba(0, 0, 0, 0.6);
      transition: transform 0.3s ease;
      z-index: 2;
    }
    section:hover {
      transform: translateY(-10px); /* Lift effect */
    }

    h2 {
      font-size: 2.5em;
      color: #1e90ff;
      text-align: center;
      text-transform: uppercase;
      margin-bottom: 30px;
      letter-spacing: 3px;
      animation: fadeIn 1.2s ease-out;
    }
    p {
      font-size: 1.2em;
      line-height: 1.6;
      color: #ccc;
      letter-spacing: 1px;
    }

    /* Hover and Neon Glow Animation */
    @keyframes neonGlow {
      0% {
        text-shadow: 0 0 15px #1e90ff, 0 0 30px #1e90ff, 0 0 60px #1e90ff;
      }
      50% {
        text-shadow: 0 0 30px #ff00ff, 0 0 60px #ff00ff, 0 0 90px #ff00ff;
      }
      100% {
        text-shadow: 0 0 15px #1e90ff, 0 0 30px #1e90ff, 0 0 60px #1e90ff;
      }
    }

    /* Fade-In Animation */
    @keyframes fadeIn {
      0% { opacity: 0; transform: translateY(30px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    /* 3D Button Effect */
    .btn {
      display: inline-block;
      padding: 18px 35px;
      background-color: #1e90ff;
      color: #fff;
      text-decoration: none;
      border-radius: 12px;
      box-shadow: 0 12px 30px rgba(30, 144, 255, 0.3);
      font-size: 1.2em;
      transition: all 0.3s ease;
    }
    .btn:hover {
      transform: translateY(-6px);
      box-shadow: 0 18px 40px rgba(30, 144, 255, 0.5);
      text-shadow: 0 0 10px rgba(30, 144, 255, 0.9);
    }
  </style>
</head>
<body>

<div class="parallax"></div>

<header>
  <h1>GAMER_A765</h1>
  <p>Welcome to the official website of GAMER A765!</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#videos">Videos</a>
  <a href="https://www.youtube.com/@GamerA765_official" target="_blank">YouTube Channel</a>
  <a href="#contact">Contact</a>
</nav>

<div class="container">
  <section id="home">
    <h2>Latest Video</h2>
    <div class="video-embed">
      <iframe width="560" height="315" src="https://www.youtube.com/watch?v=VfYlz5FS2vE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <p>Check out more videos on my <a href="https://www.youtube.com/@GamerA765_official" target="_blank" class="btn">YouTube Channel</a></p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>Hi, I'm Adarsh Satheesan, the creator behind GAMER A765. I create content about gaming and vlogging. Join me on my journey and subscribe to stay updated with my latest videos!</p>
  </section>

  <section id="videos">
    <h2>My Videos</h2>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=VfYlz5FS2vE">Video 1</a></li>
      <li><a href="https://www.youtube.com/watch?v=8BjKZOKexio&t=43s">Video 2</a></li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Feel free to reach out to me through social media or email. I'm always open to feedback and collaboration!</p>
    <ul>
      <li><a href="https://www.instagram.com/akku_a765/" target="_blank">Instagram</a></li>
      <li><a href="https://x.com/a765_gamer" target="_blank">Twitter</a></li>
      <li><a href="mailto:adarshsatheesan7654@gmail.com">Email</a></li>
      <li><a href="https://www.youtube.com/@GamerA765_official" target="_blank">Visit My YouTube Channel</a></li>
    </ul>
  </section>
</div>

<footer>
  <p>&copy; 2024 GAMER_A765 (official). All rights reserved.</p>
</footer>

</body>
</html>

