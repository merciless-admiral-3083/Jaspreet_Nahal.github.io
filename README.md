<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Jaspreet Singh Nahal</title>
    <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" crossorigin="anonymous" />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" crossorigin="anonymous" />
    <style>
      body {
        font-family: "Roboto", sans-serif;
        line-height: 1.6;
        color: #333;
      }

      nav {
        background: linear-gradient(90deg, #6a11cb, #2575fc);
        color: white;
      }

      nav .navbar-brand {
        font-size: 1.8rem;
        font-weight: bold;
        color: white;
      }

      nav .nav-link {
        color: white;
        transition: color 0.3s ease-in-out;
      }

      nav .nav-link:hover {
        color: #ffcc00;
      }

      section {
        padding: 60px 20px;
        scroll-margin-top: 70px;
      }

      section h1, section h4 {
        text-align: center;
        color: #6a11cb;
      }

      #home {
        background: linear-gradient(135deg, #6a11cb, #2575fc);
        color: white;
        text-align: center;
        padding: 100px 20px;
        clip-path: polygon(0 0, 100% 0, 100% 85%, 0 100%);
      }

      #home img {
        border-radius: 50%;
        border: 5px solid #fff;
        box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        transition: transform 0.5s ease;
      }

      #home img:hover {
        transform: scale(1.1);
      }

      #home h1 {
        font-size: 3rem;
        margin-bottom: 10px;
      }

      #home a {
        color: white;
        background: #ffcc00;
        padding: 10px 20px;
        border-radius: 25px;
        text-decoration: none;
        transition: background 0.3s ease;
      }

      #home a:hover {
        background: white;
        color: #ffcc00;
      }

      #about p {
        text-align: justify;
        font-size: 1.1rem;
      }

      /* Tech-Stack Section */
      .tech-stack {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 2rem;
      }

      .tech-stack .logo {
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 100px;
        text-align: center;
        transition: transform 0.3s ease, background 0.3s ease;
        padding: 15px;
        border-radius: 10px;
        background: #f5f5f5;
        box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
      }

      .tech-stack .logo:hover {
        transform: translateY(-10px);
        background: #6a11cb;
        color: white;
      }

      .tech-stack .logo img,
      .tech-stack .logo i {
        width: 50px;
        height: 50px;
      }

      #contact form {
        background: #f9f9f9;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
      }

      #contact form button {
        background: #6a11cb;
        border: none;
        color: white;
        transition: background 0.3s ease;
      }

      #contact form button:hover {
        background: #2575fc;
      }

      .fade-in {
        animation: fadeIn 2s ease-in-out;
      }

      @keyframes fadeIn {
        from {
          opacity: 0;
        }
        to {
          opacity: 1;
        }
      }

      footer {
        text-align: center;
        padding: 20px;
        background: #333;
        color: white;
        margin-top: 20px;
      }
    </style>
  </head>
  <body>
    <!-- Navbar -->
    <nav class="navbar sticky-top navbar-expand-lg">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Jaspreet Singh Nahal</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
            <li class="nav-item"><a class="nav-link" href="#about">About Me</a></li>
            <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
            <li class="nav-item"><a class="nav-link" href="#education">Education</a></li>
            <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
          </ul>
        </div>
      </div>
    </nav>

    <main>
      <section id="home" class="fade-in">
        <h1>Welcome to My Portfolio</h1>
        <p>A passionate learner and software developer</p>
        <a href="#">View Resume</a>
        <img src="WhatsApp Image 2024-05-26 at 12.50.18_72ee008f.jpg" alt="Jaspreet Singh Nahal" />
      </section>

      <section id="about">
        <h1>About Me</h1>
        <p>I am Jaspreet Singh Nahal, currently pursuing a B.Tech degree with a keen interest in software development and open-source contributions.</p>
      </section>

      <section id="skills">
        <h1>Skills</h1>
        <div class="tech-stack">
          <div class="logo">
            <i class="fab fa-html5" style="color: #f4470b;"></i>
            <span>HTML5</span>
          </div>
          <div class="logo">
            <i class="fab fa-css3-alt" style="color: #2965f1;"></i>
            <span>CSS3</span>
          </div>
          <div class="logo">
            <i class="fab fa-js-square" style="color: #f0db4f;"></i>
            <span>JavaScript</span>
          </div>
        </div>
      </section>

      <section id="contact">
        <h1>Contact Me</h1>
        <form>
          <div class="mb-3">
            <label for="email" class="form-label">Email Address</label>
            <input type="email" class="form-control" id="email" placeholder="name@example.com" required />
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">Message</label>
            <textarea class="form-control" id="message" rows="3" placeholder="Your message" required></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </section>
    </main>

    <footer>
      <p>&copy; 2024 Jaspreet Singh Nahal. All Rights Reserved.</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
