<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Portfolio</title>
    <style type="text/css">
      body,h1,h2,p,a,ul,li{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }
      body {
        font-family: Montserrat,sans-serif;
        background-color: #0d1a26;
        color: #fff;
        line-height: 1.6;
      }
      .topnav{
        background-color: #060d13;
        overflow: hidden;
      }
      .topnav a{
        float: left;
        color: #f2f2f2;
        text-align: center;
        padding: 22px 64px;
        text-decoration: none;
        font-size: 17px;
      }
      .topnav a:hover{
        background-color: #ddd;
        color: black;
      }
      .container{
        width: 80%;
        margin: 0 auto;
      }
      header{
      background-color:#060d13;
      text-align: center;
      padding: 2rem 0;
    }
    header h1{
      margin-bottom: 0.5rem;
    }
    header p{
      font-size: 1.2rem;
    }
    .section{
      padding: 2rem 0;
      text-align: center;
    }
    .section h2{
      margin-bottom: 1rem;
    }
    .section h2{
      margin-bottom: 1rem;
    }
    .about-content{
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .about-content img{
      width: 150px;
      height: 150px;
      border-radius: 50%;
      margin-bottom: 1rem;
    }
    .skills-list{
      list-style: none;
      padding: 0;
    }
    .skills-list li{
      background-color: #ecf2f9;
      color: black;
      margin: 0.5rem 0;
      padding: 0.5rem;
      border-radius: 5px;
    }
    .gallery{
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    .gallery-item{
      background-color: #ecf2f9;
      color: black;
      margin: 1rem;
      padding: 1rem;
      border-radius: 5px;
      width: calc(33% - 2rem);
      transition: transform 0.3s;
    }
    .gallery-item img{
      max-width: 100%;
      height: auto;
      border-radius: 5px;
    }
    .gallery-item:hover{
      transform: scale(1.05);
    }
    .gallery-item p{
      margin-top: 1rem;
    }
    #resume p{
      margin-top: 1rem;
      display: inline-block;
      background: whitesmoke;
      padding: 0.5rem 1rem;
      text-decoration: none;
      border-radius: 5px;
    }
    #resume a{
      color: black;
      text-decoration: none;
      transition: color 0.3s;
    }
    #resume a:hover{
      color: darkgreen;
    }
    #contact p{
      margin-bottom: 1rem;
    }
    footer{
      background-color: #060d13;
      text-align: center;
      padding: 1rem 0;
      margin-top: 2rem;
    }
    </style>
</head>
<body>
<!-- Header Section -->
<header>
    <div class="topnav">

  <a href="#home">HOME</a>
  <a href="#about">ABOUT ME</a>
  <a href="#skills">SKILLS</a>
  <a href="#projects">PROJECTS</a>
  <a href="#resume">RESUME</a>
  <a href="#contact">CONTACT</a>
</div>
  <div class="container">
    <h1>Aparna Tikkoo</h1>
    <p>Welcome to my Portfolio</p>
  </div>
</header>

<!-- About Section -->
<section id="about" class="section">
  <div class="container">
    <h2>About Me</h2>
    <hr><br>
    <div class="about-content">
      <img src="images01/myself.jpg" alt="Your Image">
      <p>Hi, I'm Aparna, a passionate front-end web developer with a keen eye for design and user experience. I specialize in creating <br>responsive, user-friendly websites using the latest web technologies. With a solid foundation in HTML, CSS and JavaScript, I <br>enjoy bringing designs to life and ensuring they work seamlessly across all devices. Lorem ipsum dolor sit amet, consectetur <br> adipisicing elit, sed do eiusmod
            tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
            quis nostrud <br> exercitation ullamco laboris nisi ut aliquip ex ea commodo
            consequat. Duis aute irure dolor in reprehenderit in voluptate velit <br>esse
            cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
            proident, sunt in culpa qui officia deserunt <br> mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
            tempor incididunt ut <br>grg labore et dolore magna aliqua. Ut enim ad minim veniam,
            quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodohreriuiurghjj
            consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
            cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
            proident, sunt in culpa qui officia deserunt mollit anim id est laborum..</p>
    </div>
  </div>
</section>

<!-- Skills Section -->
<section id="skills" class="section">
  <div class="container">
    <h2>Skills</h2>
    <hr><br>
    <ul class="skills-list">
                <li>Photography</li>
                <li>Photo Editing</li>
                <li>HTML</li>               
                <li>CSS</li>
                <li>JavaScript</li>
                <li>MySql</li>
                <li>Responsive Design</li>
    </ul>
  </div>
</section>

<!-- Projects Section -->
<section id="projects" class="section">
  <div class="container">
    <h2>Projects</h2>
    <hr><br>
    <div class="gallery">
      <div class="gallery-item">
        <img src="images01/photo1.jpg" alt="Project 1">
        <p>Project 1 </p>
      </div>
      <div class="gallery-item">
        <img src="images01/photo2.jpg" alt="Project 2">
        <p>Project 2 </p>
      </div>
      <div class="gallery-item">
        <img src="images01/photo3.jpg" alt="Project 3">
        <p>Project 3 </p>
      </div>
      <div class="gallery-item">
        <img src="images01/photo4.jpg" alt="Project 3">
        <p>Project 3 </p>
      </div>
      
    </div>
  </div>
</section>

<!-- Resume Section -->
<section id="resume" class="section">
  <div class="container">
    <h2>Resume</h2>
    <hr><br>
    <p><a href="ATresume.pdf" download>Download my resume</a></p>
  </div>
</section>
<!-- Contact section -->
<section id="contact" class="section">
  <div class="container">
    <h2>Contact Me</h2>
    <hr><br>
    <p>Email : aparnatikkoo127@gmail.com</p>
    <p>Phone : (91) 456-7890</p>
  </div>
</section>

<!-- footer -->
<footer>
  <div class="container">
    <p>&copy; 2024 Aparna Tikkoo. All Rights Reserved.</p>
  </div>
</footer>
</body>
</html>
