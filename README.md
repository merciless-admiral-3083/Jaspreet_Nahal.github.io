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
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      color: #333;
    }
    
    a {
      text-decoration: none;
      color: inherit;
    }

    nav {
      background-color: #000;
      padding: 10px 20px;
    }

    nav .navbar-brand {
      font-size: 1.5rem;
      color: #fff;
      font-weight: bold;
    }

    nav .nav-link {
      color: #fff;
      font-size: 1rem;
      margin-right: 15px;
    }

    nav .nav-link:hover {
      color: #00c2ff;
    }

    #home {
      height: 100vh;
      background: linear-gradient(135deg, #141e30, #243b55);
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
    }

    #home h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    #home p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }

    #home a {
      background: #00c2ff;
      color: white;
      padding: 10px 25px;
      border-radius: 30px;
      font-size: 1rem;
      transition: background 0.3s ease;
    }

    #home a:hover {
      background: #005f85;
    }

    #about {
      background: #f5f5f5;
      padding: 60px 20px;
      text-align: center;
    }

    #about h1 {
      margin-bottom: 30px;
      color: #141e30;
    }

    #about p {
      max-width: 800px;
      margin: 0 auto;
      font-size: 1.1rem;
      color: #555;
    }

    #contact {
      background: #eaf0f1;
      padding: 60px 20px;
      text-align: center;
    }

    #contact h1 {
      margin-bottom: 30px;
      color: #141e30;
    }

    #contact form {
      max-width: 600px;
      margin: 0 auto;
      text-align: left;
    }

    footer {
      background: #000;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand" href="#">Jaspreet Singh Nahal</a>
      <button 
        class="navbar-toggler" 
        type="button" 
        data-bs-toggle="collapse" 
        data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <section id="home">
    <h1>Welcome to My Portfolio</h1>
    <p>A passionate learner and software developer</p>
    <a href="Profile.pdf" target="_blank" download="Profile.pdf">View Resume</a>
  </section>

  <section id="about">
    <h1>About Me</h1>
    <p>I am Jaspreet Singh Nahal, currently pursuing a B.Tech degree with a keen interest in software development and open-source contributions.</p>
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
          required />
      </div>
      <div class="mb-3">
        <label for="message" class="form-label">Message</label>
        <textarea 
          class="form-control" 
          id="message" 
          rows="4" 
          placeholder="Your message" 
          required></textarea>
      </div>
      <button type="submit" class="btn btn-dark">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2024 Jaspreet Singh Nahal. All Rights Reserved.</p>
  </footer>

  <script 
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js">
  </script>
</body>
</html>
