<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="style.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans+Condensed:wght@300&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Amatic+SC:wght@700&family=Caladea:ital@1&family=Playfair+Display:wght@500&display=swap" rel="stylesheet">    <title>Torrey Thomas</title>
</head>
<body>
    <div class="container">
        <div class="navigation-container">
            <nav id="nav-bar">
                <ul>
                    <li><a  class="nav-link" href="#about"> About </a></li>
                    <li><a class="nav-link" href="#work"> Work </a></li>
                    <li><a class="nav-link" href="#contact"> Contact </a></li>
                </ul>
            </nav>
        </div>



        <section id="welcome-section">
            <div class="greeting">
                <h1 class="name"> Hey, I'm Torrey</h1>
                <p class="occupation"> <em> Web Developer </em></p>
            </div>
        </section>
</div>
<section id="about">
    <div class="about-container">
        <h2 class="some-of-my-projects"> <u> A little about me </u> </h2>
        <div class="about-description-container">
        <img  id="candid-photo" width="450px" height="450px" src="./IMG_3547.jpeg" alt="a candid image of myself"/>
        <div class="about-description-text">
            <p class="about-line-one">  I never <em><strong> give up </strong> </em>. </p>
            <p class="about-line"> I am a front-end web developer that appreciates the jovial feeling of hard-earned success on the front-end while also cultivating the ability to manipulate data in the back-end as well. 
                As a developer, I embody the spirit of persistence and service as I strive to create applications that provide peak functionality and value to users, companies, and clients alike. Feel free to take a look at my 
                <a class="nav-link" href="#work"> Work </a> to see what I have to offer!
            </p>

            <p class="about-line"> When I am not glued to my computer, I enjoy taking scenic runs through the Rock Creek Park, revisiting my childhood by playing Nintendo64 games, and reading.</p>
            <h3 class="about-line"> <em> I am currently seeking an amazing role as a front-end web developer in the D.C. area and I would love to chat about a new opportunity. Feel free to reach out!</em></h3>
        </div>
    </div>
    </div>
</section>
<section id="project-section">
        <h2  id="work" class="some-of-my-projects"> <u> These are some of my projects  </u> </h2>

        <section class="projects-section">
        <div class="projects-grid"> 
            <a href="https://torreythomas.github.io/product-landing-page/" target="_blank" class="project project-tile">
             <img class="project-image" width="50px" height="50px" src='./product.png' alt="responsive product page">
             <h2 class="project-title">  Responsive Product Page </h2></div>
            </a>
            </div>
            <div class="projects-grid"> 
                <a href="https://torreythomas.github.io/Hangman/" target="_blank" class="project project-tile">
                 <img class="project-image" width="50px" height="50px" src='./hangman.png' alt="responsive product page">
                 <h2 class="project-title"> Hangman </h2></div>
                </a>
                </div>
                <div class="projects-grid"> 
                    <a href="https://vast-tundra-84762.herokuapp.com/jobs" target="_blank" class="project project-tile">
                     <img class="project-image" width="50px" height="50px" src='./api.png' alt="responsive product page">
                     <h2 class="project-title">  Company API </h2></div>
                    </a>
                    </div>
            </section>
            <section id="footer">
                <div id="contact" class="about-container">
                    <div class="about-description-container">
                    <img  id="candid-photo" width="450px" height="450px" src="./IMG_2540.jpeg" alt="a candid image of myself"/>
                    <div class="about-description-text">
                        <p class="footer-line-one"> <strong> Let's Connect. </strong></p>
                        <p class="footer-line"> 
                           I want to make an impact in the world of technology.  </p>
                           <p class="footer-line"> Sound good? Let's have a chat.</p>
                           <div class="icons">
                           <a href="https://github.com/torreythomas" ><i class="fab fa-github-square"></i></a>
                           <a href="https://www.linkedin.com/in/torreyct/"> <i class="fab fa-linkedin"></i></a>
                           <a href="mailto:torreythms@gmail.com"><i class="fas fa-envelope-square"></i></a>
                          <a href="tel:7174216943"> <i class="fas fa-phone-square"></i></a>
                        </div>
                        <p class="footer-line"><em> &copy Torrey Thomas</em></p>
                                </div>
                </div>
                </div>
            </section>
    </div>
</section>
</body>
<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
<script src="https://kit.fontawesome.com/536d31ac54.js" crossorigin="anonymous"></script>
</html>