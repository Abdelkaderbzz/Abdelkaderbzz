<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Abdelkader Bouzomita - Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/aos@2.3.1/dist/aos.css" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/swiper/swiper-bundle.min.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #0073e6;
      padding: 20px;
      text-align: center;
      color: white;
    }

    .container {
      width: 80%;
      margin: 0 auto;
    }

    h1, h3 {
      margin: 10px 0;
    }

    .stat {
      font-size: 2rem;
      margin: 20px;
      text-align: center;
    }

    .stat b {
      font-size: 3rem;
      color: #ff9900;
    }

    .tool-icon img {
      transition: transform 0.3s ease;
    }

    .tool-icon:hover img {
      transform: scale(1.2);
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
      margin-top: 20px;
    }

    .project-card {
      border: 1px solid #ddd;
      padding: 15px;
      border-radius: 8px;
      text-align: center;
      transition: transform 0.3s ease;
    }

    .project-card:hover {
      transform: scale(1.05);
    }

    footer {
      background-color: #333;
      color: white;
      padding: 10px;
      text-align: center;
    }

  </style>
</head>
<body>
  <header>
    <h1 data-aos="fade-up">Hi 👋, I'm Abdelkader</h1>
    <h3 data-aos="fade-up" data-aos-delay="200">I am a full-stack developer from Tunisia who loves sharing my knowledge with others and constantly learning new things. I enjoy making complex concepts simple and accessible to everyone.</h3>
  </header>

  <div class="container">
    <section>
      <h3 data-aos="fade-up">Some Stats:</h3>
      <div class="stat" data-aos="zoom-in" data-aos-delay="300" data-aos-duration="1500">
        <b>50+</b><br /> Projects Completed
      </div>
      <div class="stat" data-aos="zoom-in" data-aos-delay="400" data-aos-duration="1500">
        <b>3</b><br /> Years of Experience
      </div>
      <div class="stat" data-aos="zoom-in" data-aos-delay="500" data-aos-duration="1500">
        <b>500+</b><br /> GitHub Contributions
      </div>
    </section>

    <section>
      <h3 data-aos="fade-up">Languages and Tools:</h3>
      <p>
        <a href="https://www.w3schools.com/css/" target="_blank" class="tool-icon"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40" /></a>
        <a href="https://www.figma.com/" target="_blank" class="tool-icon"><img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40" /></a>
        <a href="https://www.w3.org/html/" target="_blank" class="tool-icon"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40" /></a>
        <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" class="tool-icon"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40" /></a>
        <a href="https://jestjs.io" target="_blank" class="tool-icon"><img src="https://www.vectorlogo.zone/logos/jestjsio/jestjsio-icon.svg" alt="jest" width="40" height="40" /></a>
        <a href="https://www.mongodb.com/" target="_blank" class="tool-icon"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40" /></a>
      </p>
    </section>

    <section>
      <h3 data-aos="fade-up">Featured Projects:</h3>
      <div class="projects">
        <div class="project-card" data-aos="fade-up" data-aos-delay="300">
          <img src="https://via.placeholder.com/300x200" alt="Project 1" />
          <h4>Project 1</h4>
          <p>Short description about the project.</p>
          <a href="https://link-to-project" target="_blank">View Project</a>
        </div>
        <div class="project-card" data-aos="fade-up" data-aos-delay="400">
          <img src="https://via.placeholder.com/300x200" alt="Project 2" />
          <h4>Project 2</h4>
          <p>Short description about the project.</p>
          <a href="https://link-to-project" target="_blank">View Project</a>
        </div>
        <div class="project-card" data-aos="fade-up" data-aos-delay="500">
          <img src="https://via.placeholder.com/300x200" alt="Project 3" />
          <h4>Project 3</h4>
          <p>Short description about the project.</p>
          <a href="https://link-to-project" target="_blank">View Project</a>
        </div>
      </div>
    </section>

    <footer>
      <p>Thanks for visiting my portfolio! 😊</p>
      <p>Feel free to reach out: <a href="mailto:abdelkader.bouzomita@gmail.com">abdelkader.bouzomita@gmail.com</a></p>
    </footer>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/aos@2.3.1/dist/aos.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/swiper/swiper-bundle.min.js"></script>
  <script>
    AOS.init();
  </script>
</body>
</html>
