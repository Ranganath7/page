<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Welcome - My Bio</title>
  <style>
    body {
      margin: 0;
      font-family: sans-serif;
      background: linear-gradient(to bottom right, #111, #222);
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
      padding: 20px;
    }

    .container {
      max-width: 500px;
    }

    h1 {
      font-size: 2rem;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.1rem;
      color: #ccc;
      margin-bottom: 30px;
    }

    a.button {
      background: #0af;
      color: white;
      padding: 12px 24px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s;
    }

    a.button:hover {
      background: #08c;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Hello, I'm [Your Name]</h1>
    <p>I’m a creative developer with a love for clean design, responsive UI, and mobile-first experiences.</p>
    <a href="projects.html" class="button">View My Projects →</a>
  </div>
</body>
</html>

