<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width">
    <title>Diogo Ferreira</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"/>
    <link rel="stylesheet" href="style.css">
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.11/typed.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/waypoints/4.0.1/jquery.waypoints.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css"/>

</head>
<body>
      <div class="scroll-up-btn">
        <i class="fas fa-angle-up"></i>
    </div>
    <nav class="navbar">
      <div class="max-width">
        <div class="logo">
          <a href="#">Lab<span>5.</span></a>
        </div>
        <ul class="menu">
          <li><a href="#">Home</a></li>
          <li>
            <a href="#about">About</a>
            <ul class="dropdown" id="about">
              <li><a href="#resumeNav">Resume</a></li>
              <li><a href="#studiesNav">Studies</a></li>
              <li><a href="#skillsNav">Skills</a></li>
            </ul>
          </li>
          <li>
            <a href="#">Projects</a>
            <ul class="dropdown" id="project">
              <li><a href="#">UCs</a></li>
              <li><a href="#">Independent</a></li>
              <li><a href="#">TFC</a></li>
            </ul>
          </li>
          <li>
            <a href="#">Web</a>
            <ul class="dropdown" id="web">
              <li><a href="#">Option 1</a></li>
              <li><a href="#">Option 2</a></li>
              <li><a href="#">Option 3</a></li>
            </ul>
          </li>
          <li><a href="#">Contact</a></li>
        </ul>
        <div class="menu-btn">
          <i class="fas fa-bars"></i>
        </div>
      </div>
    </nav>
      

    <!-- home section start -->
    <section class="home" id="home">
        <div class="max-width">
            <div class="home-content">
                <div class="text-1">Hello, my name is</div>
                <div class="text-2">Diogo Ferreira</div>
                <div class="text-3">And I'm a <span class="typing"></span></div>
                <a href="#contact">Talk with me</a>
            </div>
        </div>
    </section>

    
    <div class="border-btw-content" id="resumeNav"></div>

    <!-- about section start -->
    <section class="about" id="about">
        <div class="max-width">
          <div class="container">
            <h2 class="title">About me</h2>
            <div class="about-content" id="abouNav">
                <div class="left-col">
                    <img src="images/profile-1.jpeg" alt="" width="300px" height="300px">
                </div>
                <div class="right-col">
                    <div class="text">I'm Diogo and I'm a <span class="typing-2"></span></div>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum</p>
                    
                    <a href="#">Download CV</a>
                </div>
            </div>
          </div>
        </div>
       
        <div class="border-btw-content" id="studiesNav"></div>

        <div class="max-width">
          <div class="container">
          <h2 class="title">My Studies</h2>
          <div class="studies-content">
            <div class="left-col">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum</p>
            </div>
            <div class="right-col">
              <img src="images/profile-2.jpeg" alt="" width="300px" height="300px">
            </div>
          </div>
          </div>
       </div>

        <div class="border-btw-content" id="skillsNav"></div>

        <div class="max-width">
          <div class="container">
          <h2 class="title">Personal skills and competences</h2>
          <div class="skills-content">
            <div class="left-col">
              <img src="images/profile-3.jpeg" alt="" width="300px" height="300px">
            </div>
            <div class="right-col">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum</p>
            </div>
          </div>
          </div>
        </div>
    </section>

    <div class="border-btw-content"></div>

    <!-- projects section start -->
    <section class="projects" id="projects">
        <div class="max-width">
          <div class="container">
            <h2 class="title">My Projects</h2>
            <div class="carousel owl-carousel">
                <div class="card">
                    <div class="box">
                        <img src="/images/charmander.png" alt="">
                        <div class="text">Project 1</div>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                        <a href="#" class="read-more-btn">Read More</a>
                      </div>
                </div>
                <div class="card">
                    <div class="box">
                        <img src="images/cyndaquil.png" alt="">
                        <div class="text">Project 2</div>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                        <a href="#" class="read-more-btn">Read More</a>
                      </div>
                </div>
                <div class="card">
                    <div class="box">
                        <img src="images/torchic.png" alt="">
                        <div class="text">Project 3</div>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                        <a href="#" class="read-more-btn">Read More</a>
                      </div>
                </div>
                <div class="card">
                    <div class="box">
                        <img src="images/chimchar.png" alt="">
                        <div class="text">Project 4</div>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                        <a href="#" class="read-more-btn">Read More</a>
                      </div>
                  </div>
                <div class="card">
                    <div class="box">
                        <img src="images/tepig.png" alt="">
                        <div class="text">Project 5</div>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                        <a href="#" class="read-more-btn">Read More</a>
                      </div>
                </div>
                <div class="card">
                    <div class="box">
                        <img src="images/fennekin.png" alt="">
                        <div class="text">Project 6</div>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                        <a href="#" class="read-more-btn">Read More</a>
                      </div>
                </div>
            </div>
          </div>
        </div>

        <div class="border-btw-content"></div>

        <div class="max-width">
          <div class="container">
            <h2 class="title">Projects From UCs</h2>
            <div class="container-flex">
            <div class="grid">
              <div class="card">
                <img src="/images/charmeleon.png" alt="" width="300px" height="300px">
                <div class="overlay">
                  <div class="text">Project 1</div>
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                  <a href="#" class="read-more-btn">Learn More</a>
                </div>
              </div>
              <div class="card">
                <img src="images/quilava.png" alt="" width="300px" height="300px">
                <div class="overlay">
                  <div class="text">Project 2</div>
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                  <a href="#" class="read-more-btn">Learn More</a>
                </div>
              </div>
              <div class="card">
                <img src="images/combusken.png" alt="" width="300px" height="300px">
                <div class="overlay">
                  <div class="text">Project 3</div>
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                  <a href="#" class="read-more-btn">Learn More</a>
                </div>
              </div>
              <div class="card">
                <img src="images/monferno.png" alt="" width="300px" height="300px">
                <div class="overlay">
                  <div class="text">Project 4</div>
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                  <a href="#" class="read-more-btn">Learn More</a>
                </div>
              </div>
              <div class="card">
                <img src="images/pignite.png" alt="" width="300px" height="300px">
                <div class="overlay">
                  <div class="text">Project 5</div>
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                  <a href="#" class="read-more-btn">Learn More</a>
                </div>
              </div>
              <div class="card">
                <img src="images/braixen.png" alt="" width="300px" height="300px">
                <div class="overlay">
                  <div class="text">Project 6</div>
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                  <a href="#" class="read-more-btn">Learn More</a>
                </div>
              </div>
            </div>
          </div>
          </div>
        </div>

        <div class="border-btw-content"></div>

        <!-- Projects That I Take Part of outside of school -->
    </section>
            
    <!-- footer section start -->
    <footer>
        <span>Created By <a href="">Diogo Ferreira</a> | <span class="far fa-copyright"></span> 2023 All rights reserved.</span>
    </footer>

    <script src="script.js"></script>
</body>
</html>
