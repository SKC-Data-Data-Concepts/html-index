# skc-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SKC Data Concepts – Portfolio</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      background: #0b0b0b;
      color: #f5f5f5;
      font-family: "Space Mono", monospace;
      line-height: 1.6;
      padding: 40px 20px;
    }
    header {
      text-align: center;
      margin-bottom: 50px;
    }
    header h1 {
      font-size: 2rem;
      letter-spacing: 2px;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1rem;
      color: #ccc;
    }
    section {
      max-width: 800px;
      margin: 0 auto 60px;
    }
    h2 {
      border-bottom: 1px solid #333;
      margin-bottom: 20px;
      padding-bottom: 10px;
      font-size: 1.2rem;
      text-transform: uppercase;
      letter-spacing: 1px;
    }
    .project {
      background: #141414;
      border: 1px solid #222;
      border-radius: 8px;
      padding: 20px;
      margin-bottom: 30px;
      transition: border-color 0.2s, transform 0.2s;
    }
    .project:hover {
      border-color: cyan;
      transform: scale(1.02);
    }
    .project h3 {
      margin-bottom: 10px;
      color: cyan;
    }
    .project a {
      color: cyan;
      text-decoration: none;
    }
    .project a:hover { text-decoration: underline; }
    footer {
      text-align: center;
      font-size: 0.9rem;
      color: #888;
      margin-top: 60px;
    }
  </style>
</head>

<body>
  <header>
    <h1>Shana Campbell</h1>
    <p>Digital Creator • Web Portfolio • SKC Data Concepts</p>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>
      I’m a creative digital thinker with a passion for clean, purposeful design
      and accessible web experiences. My background blends coding, data,
      and digital communication — bringing clarity to complex ideas through
      simple, intuitive visuals.
    </p>
  </section>

  <section id="projects">
    <h2>Projects</h2>

    <div class="project">
      <h3>SKC Portal</h3>
      <p>
        A live frontend concept built and hosted via Bolt, exploring the bridge
        between data and digital therapy concepts. Demonstrates deployment skills,
        web design, and creative application of modern web frameworks.
      </p>
      <p>
        <strong>Tech:</strong> HTML, CSS, JavaScript
      </p>
      <p>
        🔗 <a href="https://skc-portal-mv2w.bolt.host/" target="_blank">Visit SKC Portal</a>
      </p>
    </div>
  </section>

  <footer>
    <p>© 2025 Shana Campbell | SKC Data Concepts</p>
    <p>Connect: <a href="mailto:shanacampbell93@gmail.com" style="color: cyan;">Email</a></p>
  </footer>
</body>
</html>
