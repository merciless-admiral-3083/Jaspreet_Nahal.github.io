<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Jaspreet Singh Nahal</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css">
  <style>
    /* General Reset */
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #111;
      color: white;
      scroll-behavior: smooth;
    }

    /* Navigation Bar */
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background: #111;
      z-index: 10;
      padding: 10px 30px;
    }

    nav ul {
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: flex-end;
      list-style: none;
    }

    nav li {
      margin-left: 20px;
    }

    nav a {
      color: #fff;
      font-size: 1.1rem;
      text-decoration: none;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #00c2ff;
    }

    /* Full-page Sections */
    section {
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
      transition: all 0.3s ease-in-out;
    }

    /* Home Section */
    #home {
      background: #000;
    }

    #home h1 {
      font-size: 4rem;
      font-weight: bold;
      margin-bottom: 20px;
    }

    #home p {
      font-size: 1.5rem;
      max-width: 600px;
      margin: 0 auto 30px;
    }

    #home a {
      color: #fff;
      border: 2px solid #00c2ff;
      padding: 10px 25px;
      border-radius: 5px;
      font-size: 1rem;
      text-transform: uppercase;
      transition: all 0.3s ease;
    }

    #home a:hover {
      background: #00c2ff;
      color: #000;
    }

    /* About Section */
    #about {
      background: #222;
    }

    #about h1 {
      font-size: 3rem;
      margin-bottom: 20px;
    }

    #about p {
      font-size: 1.2rem;
      max-width: 800px;
      margin: 0 auto;
      line-height: 1.8;
    }

    /* Contact Section */
    #contact {
      background: #333;
    }

    #contact h1 {
      font-size: 3rem;
      margin-bottom: 20px;
    }

    #contact form {
      max-width: 600px;
      width: 100%;
      margin: 0 auto;
    }

    #contact .form-control {
      background: #444;
      color: white;
      border: 1px solid #555;
      margin-bottom: 15px;
      border-radius: 5px;
    }

    #contact .form-control:focus {
      border-color: #00c2ff;
      box-shadow: none;
    }

    #contact button {
      background: #00c2ff;
      color: #000;
      border: none;
      padding: 10px;
      font-size: 1rem;
      border-radius: 5px;
      transition: background 0.3s ease;
    }

    #contact button:hover {
      background: #008bb5;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px;
      background: #000;
      color: white;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="home">
    <div>
      <h1>Jaspreet Singh Nahal</h1>
      <p>A passionate learner and software developer creating meaningful solutions.</p>
      <a href="Profile.pdf" target="_blank" download="Profile.pdf">View Resume</a>
    </div>
  </section>

  <section id="about">
    <div>
      <h1>About Me</h1>
      <p>I am Jaspreet Singh Nahal, currently pursuing a B.Tech degree. I am passionate about software development, open-source contributions, and solving real-world problems through technology.</p>
    </div>
  </section>

  <section id="contact">
    <div>
      <h1>Contact Me</h1>
      <form>
        <input type="email" class="form-control" placeholder="Your Email Address" required>
        <textarea class="form-control" rows="4" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </section>

  <footer>
    <p>&copy; 2024 Jaspreet Singh Nahal. All Rights Reserved.</p>
  </footer>
</body>
</html>
