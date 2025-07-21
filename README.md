
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Welcome | Prerna's Web</title>
  <link href="https://fonts.googleapis.com/css2?family=Nunito:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Nunito', sans-serif;
      background: linear-gradient(to right, #a1c4fd, #c2e9fb);
      color: #333;
    }

    header {
      text-align: center;
      padding: 100px 20px 60px;
      background: linear-gradient(to right, #667eea, #764ba2);
      color: white;
    }

    header h1 {
      font-size: 3.2em;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2em;
      color: #e0e0e0;
    }

    section {
      padding: 60px 20px;
      text-align: center;
    }

    section h2 {
      font-size: 2.2em;
      color: #4a4a4a;
      margin-bottom: 20px;
    }

    section p {
      max-width: 700px;
      margin: auto;
      font-size: 1.1em;
      line-height: 1.6;
      color: #555;
    }

    .services {
      margin-top: 40px;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 25px;
    }

    .card {
      background: white;
      padding: 25px;
      border-radius: 15px;
      width: 260px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.1);
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 15px 35px rgba(0,0,0,0.15);
    }

    footer {
      background: #333;
      color: #ccc;
      text-align: center;
      padding: 30px 20px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>

  <header>
    <h1>Hi, I'm Prerna 👋</h1>
    <p>Welcome to my world of creativity, code, and cloud!</p>
  </header>

  <section>
    <h2>About Me</h2>
    <p>
      I'm a tech explorer with passion for Linux servers, Docker, cloud infrastructure, and beautiful UI.  
      I love building powerful backend systems and stunning frontend designs too.
    </p>

    <div class="services">
      <div class="card">
        <h3>💻 Web Development</h3>
        <p>Modern websites using HTML, CSS, JavaScript, and PHP.</p>
      </div>
      <div class="card">
        <h3>☁️ Cloud & DevOps</h3>
        <p>Experience with Docker, Ceph, and virtualization tools.</p>
      </div>
      <div class="card">
        <h3>📢 Tech Content</h3>
        <p>Clear documentation, tutorials & blogs for tech learners.</p>
      </div>
    </div>
  </section>

  <footer>
    &copy; 2025 Prerna | Connect: prerna@example.com | Powered by Passion 🔥
  </footer>

</body>
</html>
