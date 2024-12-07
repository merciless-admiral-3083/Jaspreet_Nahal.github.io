<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Jaspreet Singh Nahal</title>
    <link
      rel="stylesheet"
      href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css"
      crossorigin="anonymous"
    />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css"
      rel="stylesheet"
      crossorigin="anonymous"
    />
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

      section h1 {
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

      #home h1 {
        font-size: 3rem;
        margin-bottom: 10px;
      }

      #home a {
        display: inline-block;
        color: white;
        background: #ffcc00;
        padding: 10px 20px;
        border-radius: 25px;
        text-decoration: none;
        font-weight: bold;
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
    <nav class="navbar sticky-top navbar-expand-lg">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Jaspreet Singh Nahal</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
            <li class="nav-item"><a class="nav-link" href="#about">About Me</a></li>
            <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
          </ul>
        </div>
      </div>
    </nav>

    <main>
      <section id="home" class="fade-in">
        <h1>Welcome to My Portfolio</h1>
        <p>A passionate learner and software developer</p>

        <!-- Link to the resume -->
        <a href="profile.pdf" target="_blank" download="profile.pdf">
          View Resume
        </a>
      </section>

      <section id="about">
        <h1>About Me</h1>
        <p>
          I am Jaspreet Singh Nahal, currently pursuing a B.Tech degree with a
          keen interest in software development and open-source contributions.
        </p>
      </section>

      <section id="contact">
        <h1>Contact Me</h1>
        <form>
          <div class="mb-3">
            <label for="email" class="form-label">Email Address</label>
            <input
              type="email"
              class="form-control"
              id="email"
              placeholder="name@example.com"
              required
            />
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">Message</label>
            <textarea
              class="form-control"
              id="message"
              rows="3"
              placeholder="Your message"
              required
            ></textarea>
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
