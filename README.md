<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Fairyscript Code Hub</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>💡 Fairyscript Code Hub</h1>
    <p>Free HTML, CSS, JS Codes for Everyone</p>
  </header>

  <section class="card-container">
    <div class="code-card">
      <h2>🌟 Floating Button</h2>
      <p>CSS + HTML Code for a support button</p>
      <a href="code/floating-button.html">View Code</a>
    </div>
    <div class="code-card">
      <h2>🎬 Video Embed Layout</h2>
      <p>HTML layout for embedded drama episodes</p>
      <a href="code/video-layout.html">View Code</a>
    </div>
    <!-- Add more cards as needed -->
  </section>

  <footer>
    <p>© 2025 Fairyscript | All Codes are Free</p>
  </footer>
</body>
</html>
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: #121212;
  color: #fff;
}

header {
  text-align: center;
  padding: 30px 10px;
  background: #1f1f1f;
}

.card-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
  padding: 20px;
}

.code-card {
  background: #222;
  padding: 20px;
  border-radius: 12px;
  box-shadow: 0 0 10px rgba(0,0,0,0.4);
}

.code-card a {
  color: #00f5d4;
  text-decoration: none;
}

footer {
  text-align: center;
  padding: 15px;
  background: #1a1a1a;
  font-size: 14px;
}
