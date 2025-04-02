<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>About Me</title>
  <style>
    :root {
      --burgundy: #800020;
      --burgundy-dark: #5e0018;
      --background: #f9f9f9;
      --text-color: #333;
    }

    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background-color: var(--background);
      color: var(--text-color);
    }

    header {
      background-color: var(--burgundy);
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }

    main {
      max-width: 800px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    section {
      margin-bottom: 3rem;
    }

    h2 {
      color: var(--burgundy);
      margin-bottom: 1rem;
    }

    .social-links {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .social-links a {
      display: inline-flex;
      align-items: center;
      text-decoration: none;
      color: var(--burgundy);
      border: 1px solid var(--burgundy);
      padding: 0.5rem 1rem;
      border-radius: 5px;
      transition: background 0.2s, color 0.2s;
    }

    .social-links a:hover {
      background-color: var(--burgundy);
      color: white;
    }

    .social-links a svg {
      margin-right: 0.5rem;
    }

    form {
      display: flex;
      flex-direction: column;
    }

    input, textarea {
      padding: 0.75rem;
      margin-bottom: 1rem;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1rem;
    }

    button {
      background-color: var(--burgundy);
      color: white;
      border: none;
      padding: 0.75rem;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
    }

    button:hover {
      background-color: var(--burgundy-dark);
    }

    @media (max-width: 600px) {
      .social-links {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Mighty And Powerful Games</h1>
    <p>Micajah Capehart - Game Developer</p>
  </header>
  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>
        I’m a generalist Unity Developer with over 6 years of experience in programming, technical art, UI and tool dev. 
        I love to create systems that drive gameplay, and the fancy editor tools that make design and creation fast and convenient.
        In my free time, I like to practice art and music.
      </p>
    </section>

    <section id="social">
      <h2>Connect with me</h2>
      <div class="social-links">
        <a href="https://www.linkedin.com/in/micajah-capehart-bb5a76309/" target="_blank" rel="noopener">
          <svg width="20" height="20" fill="currentColor" viewBox="0 0 24 24">
            <path d="M4.98 3.5C4.98 4.88 3.87 6 2.49 6 1.11 6 0 4.88 0 3.5 0 2.12 1.11 1 2.49 1c1.38 0 2.49 1.12 2.49 2.5zM0 8h5v16H0V8zm7.5 0h4.8v2.2h.07c.67-1.26 2.3-2.6 4.73-2.6C22.1 7.6 24 10.14 24 14.06V24h-5v-8.6c0-2.05-.04-4.7-2.86-4.7-2.87 0-3.3 2.24-3.3 4.55V24h-5V8z"/>
          </svg>
          LinkedIn
        </a>
        <a href="mailto:team@mightyandpowerful.games">
          <svg width="20" height="20" fill="currentColor" viewBox="0 0 24 24">
            <path d="M1.5 4.5h21a1.5 1.5 0 011.5 1.5v12a1.5 1.5 0 01-1.5 1.5h-21A1.5 1.5 0 010 18V6a1.5 1.5 0 011.5-1.5zm0 1.5v.511l10.5 6.479 10.5-6.479V6h-21zm21 1.978L12 14.5 1.5 8.478V18h21V7.978z"/>
          </svg>
          Email
        </a>
      </div>
    </section>
  </main>
</body>
</html>
