# Web.Dev.Professional
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Scroll Website</title>
    <link rel="stylesheet" href="style.css" />
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.14.0/css/all.css"
      integrity="sha384-HzLeBuhoNPvSl5KYnjx0BT+WB0QEEqLprO+NBkkk5gbc67FTaL7XIGa2w1L0Xbgc"
      crossorigin="anonymous"
    />
    <link rel="icon" type="image/png" sizes="32x32" href="standard (2).gif">
  </head>
  <body>
    <!-- Navbar Section -->
    <nav class="navbar">
      <div class="navbar__container">
        <a href="#home" id="navbar__logo">Developer Professional</a>
        <div class="navbar__toggle" id="mobile-menu">
          <span class="bar"></span> <span class="bar"></span>
          <span class="bar"></span>
        </div>
        <ul class="navbar__menu">
          <li class="navbar__item">
            <a href="#home" class="navbar__links" id="home-page">Home</a>
          </li>
          <li class="navbar__item">
            <a href="#about" class="navbar__links" id="about-page">About</a>
          </li>
          <li class="navbar__item">
            <a href="#services" class="navbar__links" id="services-page"
              >Services</a
            >
          </li>
          <li class="navbar__btn">
            <a href="#sign-up" class="button" id="signup">Sign Up</a>
          </li>
        </ul>
      </div>
    </nav>

    <!-- Hero Section -->
    <div class="hero" id="home">
      <div class="hero__container">
        <h1 class="hero__heading">100 Days <span>Of</span></h1>
        <p class="hero__description">Java Script</p>
        <button class="main__btn"><a href="https://en.wikipedia.org/wiki/CSS">CSS</a></button>
      </div>
    </div>

    <!-- About Section -->
    <div class="main" id="about">
      <div class="main__container">
        <div class="main__img--container">
          <div class="main__img--card"><i class="fas fa-layer-group"></i></div>
        </div>
        <div class="main__content">
          <h1>What do we do?</h1>
          <h2>We help businesses scale</h2>
          <p>Schedule a call to learn more about our services</p>
          <button class="main__btn"><a href="#">Schedule Call</a></button>
        </div>
      </div>
    </div>

    <!-- Services Section -->
    <div class="services" id="services">
      <h1>Our Services</h1>
      <div class="services__wrapper">
        <div class="services__card">
          <h2>Custom Colorways</h2>
          <p>AI Powered technology</p>
          <div class="services__btn"><button>Java Script</button></div>
        </div>
        <div class="services__card">
          <h2>Are you Ready?</h2>
          <p>Take the lepa</p>
          <div class="services__btn"><button>HTML 5</button></div>
        </div>
        <div class="services__card">
          <h2>Full Gradients</h2>
          <p>100 Combinations</p>
          <div class="services__btn"><button>CSS</button></div>
        </div>
        <div class="services__card">
          <h2>Infinite Choices</h2>
          <p>1000's of colors</p>
          <div class="services__btn"><button>php</button></div>
        </div>
      </div>
    </div>

    <!-- Features Section -->
    <div class="main" id="sign-up">
      <div class="main__container">
        <div class="main__content">
          <h1>Join Our Team</h1>
          <h2>Sign Up Today</h2>
          <p>See what makes us different</p>
          <button class="main__btn"><a href="#">Sign Up</a></button>
        </div>
        <div class="main__img--container">
          <div class="main__img--card" id="card-2">
            <i class="fas fa-users"></i>
          </div>
        </div>
      </div>
    </div>

    <!-- Footer Section -->
    <div class="footer__container">
      <div class="footer__links">
        <div class="footer__link--wrapper">
          <div class="footer__link--items">
            <h2>About Us</h2>
            <a href="/sign__up">How it works</a> <a href="/">Testimonials</a>
            <a href="/">Careers</a> <a href="/">Terms of Service</a>
          </div>
          <div class="footer__link--items">
            <h2>Contact Us</h2>
            <a href="/">Contact</a> <a href="/">Support</a>
            <a href="/">Destinations</a>
          </div>
        </div>
        <div class="footer__link--wrapper">
          <div class="footer__link--items">
            <h2>Videos</h2>
            <a href="https://youtu.be/2_LqWxASzNk">ProTanki Video</a> <a href="/">Ambassadors</a>
            <a href="/">Agency</a>
          </div>
          <div class="footer__link--items">
            <h2>Social Media</h2>
            <a href="https://www.instagram.com/professional_oficial/">Instagram</a> <a href="https://vk.com/id785725619">Vkontakt</a>
            <a href="https://www.youtube.com/@Professional1297/videos">Youtube</a>
            <a href="https://discord.gg/vGUmrUbr">Discord</a>
          </div>
        </div>
      </div>
      <section class="social__media">
        <div class="social__media--wrap">
          <div class="footer__logo">
            <a href="/" id="footer__logo">Developer</a>
          </div>
          <p class="website__rights">© Web Developer Professonal 2023. All rights reserved</p>
          <div class="social__icons">
            <a href="/" class="social__icon--link" target="_blank"
              ><i class="fab fa-Vkontakt"></i
            ></a>
            <a href="https://www.instagram.com/professional_oficial/" class="social__icon--link"
              ><i class="fab fa-instagram"></i
            ></a>
            <a href="https://www.youtube.com/@Professional1297/videos" class="social__icon--link"
              ><i class="fab fa-youtube"></i
            ></a>
            </a>
           </a>
            <a href="https://discord.gg/vGUmrUbr" class="social__icon--link"
              ><i class="fab fa-discord"></i>
             
          </div>
        </div>
      </section>
    </div>

    <script src="app.js"></script>
  </body>
</html>
