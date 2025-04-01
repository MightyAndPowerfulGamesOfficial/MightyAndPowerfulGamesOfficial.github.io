<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>About Me</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background-color: #f9f9f9;
      color: #333;
    }

    header {
      background-color: #a60707;
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
      color: #4f46e5;
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
      color: #a60707;
      border: 1px solid #4f46e5;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      transition: background 0.2s, color 0.2s;
    }

    .social-links a:hover {
      background-color: #4f46e5;
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
      background-color: #4f46e5;
      color: white;
      border: none;
      padding: 0.75rem;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
    }

    button:hover {
      background-color: #4338ca;
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
    <p>Game Developer</p>
  </header>
  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>
        I am a Game Developer with over 10 years of experience in Unity.
      </p>
    </section>

    <section id="social">
      <h2>Connect with me</h2>
      <div class="social-links">
        <a href="https://github.com/" target="_blank" rel="noopener">
          <svg width="20" height="20" fill="currentColor" viewBox="0 0 24 24">
            <path d="M12 0C5.37 0 0 5.373 0 12a12 12 0 008.21 11.43c.6.111.82-.261.82-.577 0-.285-.01-1.04-.015-2.04-3.338.726-4.042-1.61-4.042-1.61-.546-1.387-1.333-1.757-1.333-1.757-1.089-.745.083-.729.083-.729 1.205.085 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.108-.775.418-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.468-2.38 1.236-3.22-.124-.303-.535-1.523.117-3.176 0 0 1.008-.323 3.3 1.23a11.5 11.5 0 016 0c2.292-1.553 3.297-1.23 3.297-1.23.654 1.653.243 2.873.12 3.176.77.84 1.235 1.91 1.235 3.22 0 4.61-2.803 5.625-5.475 5.92.43.372.814 1.102.814 2.222 0 1.606-.015 2.903-.015 3.296 0 .319.216.694.825.576A12.005 12.005 0 0024 12c0-6.627-5.373-12-12-12z"/>
          </svg>
          GitHub
        </a>
        <a href="https://linkedin.com/" target="_blank" rel="noopener">
          <svg width="20" height="20" fill="currentColor" viewBox="0 0 24 24">
            <path d="M4.98 3.5C4.98 4.88 3.87 6 2.49 6 1.11 6 0 4.88 0 3.5 0 2.12 1.11 1 2.49 1c1.38 0 2.49 1.12 2.49 2.5zM0 8h5v16H0V8zm7.5 0h4.8v2.2h.07c.67-1.26 2.3-2.6 4.73-2.6C22.1 7.6 24 10.14 24 14.06V24h-5v-8.6c0-2.05-.04-4.7-2.86-4.7-2.87 0-3.3 2.24-3.3 4.55V24h-5V8z"/>
          </svg>
          LinkedIn
        </a>
      </div>
    </section>

    <section id="contact">
      <h1>Contact: team@mightyandpowerful.games</h1>
    </section>
  </main>
</body>
</html>
