<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My GitHub Website</title>
  <style>
    /* Reset */
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #4facfe, #00f2fe);
      color: #333;
      line-height: 1.6;
    }

    header {
      background: rgba(255,255,255,0.2);
      color: #fff;
      padding: 20px;
      text-align: center;
      font-size: 1.8rem;
      font-weight: bold;
      backdrop-filter: blur(6px);
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin: 20px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      color: yellow;
    }

    .container {
      max-width: 900px;
      margin: auto;
      padding: 20px;
      text-align: center;
    }

    h1 {
      margin-bottom: 10px;
      font-size: 2rem;
      color: #fff;
    }

    p {
      font-size: 1.1rem;
      color: #eee;
      margin-bottom: 20px;
    }

    button {
      padding: 10px 20px;
      background: #ff9800;
      border: none;
      color: #fff;
      font-size: 1rem;
      border-radius: 5px;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background: #e68900;
    }

    footer {
      margin-top: 40px;
      text-align: center;
      padding: 15px;
      background: rgba(0,0,0,0.2);
      color: #fff;
    }
  </style>
</head>
<body>

  <header>
    🌐 My GitHub Website
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">
    <h1>Welcome to My Website 🎉</h1>
    <p>This site is hosted for free using GitHub Pages. You can customize it with your own content.</p>
    <button onclick="sayHello()">Click Me</button>
  </div>

  <footer>
    &copy; 2025 My GitHub Website | Built with ❤️
  </footer>

  <script>
    function sayHello() {
      alert("Hello! Thanks for visiting my GitHub Website 🚀");
    }
  </script>

</body>
</html>
