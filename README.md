<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Jaspreet Singh Nahal</title>
    <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous"/>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
    <style>
      .tech-stack {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 1.5rem;
      }
      .tech-stack .logo {
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 120px;
        text-align: center;
      }
      .tech-stack .logo img {
        width: 80px;
        height: 80px;
      }
      .tech-stack .logo i {
        font-size: 4rem;
        margin-bottom: 0.5rem;
      }
      .tech-stack .logo span {
        margin-top: 0.5rem;
        font-size: 1rem;
        font-weight: bold;
      }
    </style>
  </head>
  <body>
    <!-- Navbar -->
    <nav class="navbar sticky-top navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Jaspreet Singh Nahal</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#home">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#about">About Me</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#skills">My Skills</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#education">Education</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#work">My work</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">Contact Me</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <main class="container mt-3">
      <section id="home" class="d-flex justify-content-sm-center align-items-center flex-column-reverse gap-3 flex-md-row">
        <div class="d-flex justify-content-sm-center justify-content-md-even align-items-center flex-column align-items-md-start">
          <h1 class="display-4">Jaspreet Singh Nahal</h1>
          <p>A learner with a keen interest in software development!</p>
          <!-- Change button to anchor tag to open PDF in new tab -->
          <a href="https://raw.githubusercontent.com/merciless-admiral-3083/Jaspreet_Nahal.github.io/0cd13e2aa59e578215076660ac4b6bd9483b3f93/Profile.pdf" class="btn btn-light btn-sm" target="_blank">My resume</a>
        </div>
        <div class="d-md-none w-50 h-50">
          <img src="WhatsApp Image 2024-05-26 at 12.50.18_72ee008f.jpg" alt="Jaspreet Singh Nahal" class="w-100 h-50 rounded-circle shadow-lg">
        </div>
        <div class="d-none d-md-block w-50 h-50">
          <img src="WhatsApp Image 2024-05-26 at 12.50.18_72ee008f.jpg" alt="Jaspreet Singh Nahal" class="w-100 h-50 rounded-circle shadow-lg">
        </div>
      </section>
      

      <section id="about" class="mt-4 mb-4">
        <!-- About me -->
        <h4 class="display-4">About me,</h4>
        <div class="row">
          <div class="col-ls-6 wrap text-left">
            <div class="about-desc">
              <div class="pt-5">
                <p>My name is Jaspreet Singh Nahal. I am currently pursuing B.Tech. I am an open-source enthusiast.</p>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section id="skills" class="mt-4 p-4">
        <!-- Tech stack -->
        <h1 class="text-center display-4">Tech-stack I am familiar with:</h1>
        <div class="tech-stack mt-4">
          <!-- HTML5 -->
          <div class="logo">
            <i class="fab fa-html5" style="color: #f4470b;"></i>
            <span>HTML5</span>
          </div>
          <!-- CSS -->
          <div class="logo">
            <i class="fab fa-css3-alt" style="color: #2965f1;"></i>
            <span>CSS</span>
          </div>
          <!-- JavaScript -->
          <div class="logo">
            <i class="fab fa-js-square" style="color: #f0db4f;"></i>
            <span>JavaScript</span>
          </div>
          <!-- Java -->
          <div class="logo">
            <i class="fab fa-java fa-3x" style="color: #000000;"></i>
            <span>Java</span>
          </div>
          <!-- SQL -->
          <div class="logo">
            <img src="https://upload.wikimedia.org/wikipedia/commons/8/87/Sql_data_base_with_logo.png" alt="SQL Logo">
            <span>SQL</span>
          </div>
          <!-- Python -->
          <div class="logo">
            <i class="fab fa-python" style="color: #306998;"></i>
            <span>Python</span>
          </div>
          <!-- MongoDB -->
          <div class="logo">
            <img src="mongodb-logo-vector-2022.png" alt="MongoDB Logo">
            <span>MongoDB</span>
          </div>
        </div>
      </section>   

      <section id="education" class="mt-4 p-4">
        <!-- Education -->
        <h1 class="display-4 mt-5">Education</h1>
        <div class="py-4">
          <h4>Bachelor's Degree in Technology</h4>
          <p>A.K.T.U.</p>
          <p>2023-2027</p>
        </div>
      </section>

      <section id="work" class="mt-4 p-4">

      <section id="contact" class="mt-4 py-4">
        <!-- Contact me -->
        <h1 class="display-4">Contact Form</h1>
        <div class="row">
          <div class="col-sm col-md-8">
            <form>
              <div class="mb-3">
                <label for="exampleFormControlInput1" class="form-label">Email address</label>
                <input type="email" required class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
              </div>
              <div class="mb-3">
                <label for="exampleFormControlTextarea1" class="form-label">Your Message</label>
                <textarea class="form-control" id="exampleFormControlTextarea1" required placeholder="Enter your message" rows="3"></textarea>
              </div>
              <button type="submit" class="btn btn-dark text-white">Submit</button>
            </form>
          </div>
          <div class="col-sm col-md-4">
            <div class="mt-3">
              <h2 class="display-4">Want to connect?</h2>
              <h4><i class="fas fa-envelope-square"></i> jaspreetnahal100@gmail.com</h4>
              <a href="https://github.com/merciless-admiral-3083" class="btn btn-link"><i class="fab fa-github text-dark"></i></a>
              
              <a href="https://www.linkedin.com/in/jaspreet-nahal/" class="btn btn-link"><i class="fab fa-linkedin text-dark"></i></a>
            </div>
          </div>
        </div>
      </section>
    </main>

    <script src="script.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>
  </body>
</html>
