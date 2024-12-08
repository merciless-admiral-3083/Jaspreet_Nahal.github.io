<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Jaspreet Singh Nahal</title>
  <link 
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" 
    rel="stylesheet">
  <link 
    rel="stylesheet" 
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    /* General Reset */
    body {
      margin: 0;
      font-family: 'Helvetica Neue', Arial, sans-serif;
      background-color: #121212;
      color: #fff;
      scroll-behavior: smooth;
    }

    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background: #000;
      z-index: 1000;
      padding: 15px 30px;
    }

    nav ul {
      margin: 0;
      padding: 0;
      list-style: none;
      display: flex;
      justify-content: flex-end;
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

    section {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 0 20px;
    }

    #home {
      background: #000;
    }

    #home h1 {
      font-size: 3.5rem;
      font-weight: bold;
      margin-bottom: 20px;
    }

    #home p {
      font-size: 1.5rem;
      max-width: 600px;
      margin: 0 auto 30px;
    }

    #home a {
      display: inline-block;
      color: #fff;
      border: 2px solid #00c2ff;
      padding: 10px 25px;
      border-radius: 25px;
      font-size: 1.2rem;
      text-transform: uppercase;
      transition: all 0.3s ease;
    }

    #home a:hover {
      background: #00c2ff;
      color: #000;
    }

    #about {
      background: #1a1a1a;
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

    #contact {
      background: #0f0f0f;
    }

    #contact h1 {
      font-size: 3rem;
      margin-bottom: 20px;
    }

    #contact form {
      max-width: 600px;
      width: 100%;
      text-align: left;
    }

    #contact .form-control {
      background: #1a1a1a;
      color: #fff;
      border: 1px solid #333;
      border-radius: 5px;
      margin-bottom: 15px;
    }

    #contact .form-control:focus {
      border-color: #00c2ff;
      box-shadow: none;
    }

    #contact button {
      display: block;
      width: 100%;
      background: #00c2ff;
      color: #000;
      border: none;
      padding: 10px;
      font-size: 1rem;
      text-transform: uppercase;
      border-radius: 5px;
      transition: background 0.3s ease;
    }

    #contact button:hover {
      background: #008bb5;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #000;
      color: #fff;
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
    <h1>Jaspreet Singh Nahal</h1>
    <p>A passionate learner and software developer with a knack for open-source contributions.</p>
    <a href="Profile.pdf" target="_blank" download="Profile.pdf">Download Resume</a>
  </section>

  <section id="about">
    <h1>About Me</h1>
    <p>I am Jaspreet Singh Nahal, currently pursuing a B.Tech degree in Computer Science. I specialize in building modern web applications, contributing to open-source projects, and learning cutting-edge technologies.</p>
  </section>

  <section id="contact">
    <h1>Contact Me</h1>
    <form>
      <input 
        type="email" 
        class="form-control" 
        placeholder="Your Email Address" 
        required>
      <textarea 
        class="form-control" 
        rows="4" 
        placeholder="Your Message" 
        required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2024 Jaspreet Singh Nahal. All Rights Reserved.</p>
  </footer>
</body>
</html>
