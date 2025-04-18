# gptech-website-<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GP Tech | Developer & Designer</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }
    body {
      background: #0f172a;
      color: #f1f5f9;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(to right, #0f172a, #1e293b);
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }
    .btn {
      background: #38bdf8;
      color: #0f172a;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
      transition: background 0.3s;
    }
    .btn:hover {
      background: #0ea5e9;
    }
    section {
      padding: 60px 20px;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      color: #38bdf8;
      margin-bottom: 20px;
    }
    .services ul, .portfolio {
      list-style: none;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .portfolio img {
      width: 100%;
      border-radius: 10px;
    }
    .contact a {
      color: #38bdf8;
      display: block;
      margin: 10px 0;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>GP Tech</h1>
    <p>Creative Developer & Graphic Designer</p>
    <button class="btn">Hire Me</button>
  </header>  <section class="about">
    <h2>About Me</h2>
    <p>I’m a passionate computer developer and graphic designer with a focus on clean, modern design and functional, responsive code. I love building digital experiences that are both beautiful and efficient.</p>
  </section>  <section class="services">
    <h2>Services</h2>
    <ul>
      <li>Web Development</li>
      <li>Graphic Design</li>
      <li>UI/UX Design</li>
      <li>Branding</li>
    </ul>
  </section>  <section class="portfolio">
    <h2>Portfolio</h2>
    <div>
      <img src="https://via.placeholder.com/400x250?text=Project+1" alt="Project 1">
      <img src="https://via.placeholder.com/400x250?text=Project+2" alt="Project 2">
      <img src="https://via.placeholder.com/400x250?text=Project+3" alt="Project 3">
    </div>
  </section>  <section class="contact">
    <h2>Contact</h2>
    <a href="mailto:youremail@example.com">youremail@example.com</a>
    <a href="#">LinkedIn</a>
    <a href="#">Instagram</a>
  </section>
</body>
</html>
