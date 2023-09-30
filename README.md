# learingwala
learingwala


 <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <!-- Web page CSS -->
    <link rel="stylesheet" href="assets/css/styles.css" />

    <!-- Simple lightbox CSS -->
    <link rel="stylesheet" href="assets/css/simple-lightbox.min.css" />

    <!-- Favicons -->
    <link
      rel="apple-touch-icon"
      sizes="180x180"
      href="assets/icons/apple-touch-icon.png"
    />
    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="assets/icons/favicon-32x32.png"
    />
    <link
      rel="icon"
      type="image/png"
      sizes="16x16"
      href="assets/icons/favicon-16x16.png"
    />

    <title>JabTV Landing Page</title>
  </head>
  <body>
    <!-- Navbar -->

    <!-- Dark/light theme switcher -->

    <!-- Bars -->

    <!-- Hero section -->

    <!-- About section -->

    <!-- Lightbox image gallery -->

    <!-- Jab TV Stakeholders -->

    <!-- Email subscription -->

    <!-- Social icons -->

    <!-- Scroll to top button -->

    <!-- Web page script -->
    <script src="assets/js/app.js"></script>

    <!-- Ion icons CDN -->
    <script
      type="module"
      src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"
    ></script>

    <!-- Simple lightbox -->
    <script src="assets/js/simple-lightbox.min.js"></script>
    <script>
      // Simple lightbox initializer
    </script>
  </body>
</html>

<nav>
      <a href="#" class="logo">
        <h1>
          <span class="jab">Jab</span><span class="tv">TV</span
          ><span class="fist">&#x1F44A;</span>
        </h1>
      </a>
</nav>

<ul>
        <li class="nav-item">
          <a href="#about" class="nav-link" id="nav-link">About</a>
        </li>
        <li class="nav-item">
          <a href="#stars" class="nav-link" id="nav-link">Boxing Stars</a>
        </li>
        <li class="nav-item">
          <a href="#stakeholders" class="nav-link" id="nav-link"
            >stakeholders</a
          >
        </li>
        <li class="nav-item">
          <a href="#sub" class="nav-link" id="nav-link">Subscribe</a>
        </li>
</ul>

<div class="hamburger" id="hamburger">
    <span class="bar"></span>
    <span class="bar"></span>
    <span class="bar"></span>
</div>

@import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,400;0,900;1,700&display=swap");

/* CSS Variables */
:root {
  --normal-font: 400;
  --bold-font: 600;
  --bolder-font: 900;
  --primary-color: #0652dd;
  --secondary-color: #ea2027;
  --line-height: 1.7rem;
  --transition: 0.4s ease-in;
}

/* Smooth scroll effect */
html {
  scroll-behavior: smooth;
}

/* Resets */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  transition: var(--transition);
}

 body {
  font-family: "Roboto", sans-serf;
}

ul li {
  list-style-type: none;
}

a {
  text-decoration: none;
  color: var(--primary-color);
}

a:hover {
  color: var(--secondary-color);
} 

.fist {
  color: var(--secondary-color);
}

.jab {
  color: var(--primary-color);
}

.tv {
  color: var(--secondary-color);
}

nav {
  background: #fff;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 1.5rem;
  box-shadow: 2px 3px 2px #f1f1f1;
}

 position: sticky;
  top: 0;
  left: 0;
  z-index: 1;

  .hamburger {
  display: none;
}

logo {
  font-size: 2rem;
  font-weight: 500;
}

ul {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.nav-item {
  margin-left: 2rem;
}

.nav-link {
  font-weight: var(--bold-font);
}

<section class="hero">
      <div class="intro-text">
        <h1>
          <span class="hear"> You can Hear the Jabs </span> <br />
          <span class="connecting"> Connecting</span>
        </h1>
        <p>
          An online streaming platform for boxing matches <br />
          We also dedicate some special time to throwbacks cuz old is gold
        </p>
        <a class="btn red" href="#">Learn More</a>
        <a class="btn blue" href="#">Subscribe</a>
      </div>
      <div class="i-frame">
        <iframe
          width="560"
          height="315"
          src="https://www.youtube.com/embed/sUmM_PFpsvQ"
          title="YouTube video player"
          frameborder="10"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        ></iframe>
        <div class="stand-1"></div>
        <div class="stand-2"></div>
      </div>
    </section>

    display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 1.9rem;
  max-width: 1100px;
  margin: 2rem auto -6rem;
}

.intro-text h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.intro-text h3 {
  margin-bottom: 0.5rem;
}

.hero p {
  line-height: var(--line-height);
}

.hear {
  color: var(--primary-color);
}

.connecting {
  color: var(--secondary-color);
}
