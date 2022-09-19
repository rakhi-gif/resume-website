# resume-website
using html,css
http://127.0.0.1:5500/index.html
<html>

<head>
  <title>Resume Website template</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
  <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js"></script>
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css"
    integrity="sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ" crossorigin="anonymous">
</head>
<body>
  <!-------------------------Header  Section------------------------->
  <section id="header">
    <div class="container text-center">
      <div class="user-box">
        <img src="img/0_sunita2.jpg">
        <h1><b>Sunita Rajput</b></h1>
        <p><b><i> Web Developer,Python Developer,Wordpress Developer</i></b></p>
      </div>
    </div>
    <div class="scroll-btn">
      <div class="scroll-bar"><a href="#about"><span></span></a></div>
    </div>
  </section>
  <!------------------User-Info Section------------------------------------------>
  <section id="user-info">
    <div class="nav-bar">
      <nav class="navbar navbar-expand-lg">
        <a class="navbar-brand" href="#"><img src="img/sunita.png"></a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <i class="fas fa-bars"></i>
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link " href="#top"><i>HOME</i></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#about"><i>ABOUT ME</i></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#resume"><i>RESUME</i></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#services"><i>SERVICES</i></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contacts"><i>CONTACTS</i></a>
            </li>
          </ul>
        </div>
      </nav>
    </div>
    <!-------------------About-------------------------------->
    <div class="about container" id="about">
      <div class="row">
        <div class="col-nd-6 text-center">
          <img src="img/0_sunita2_11zon-min-min.jpg" class="profile-img">
        </div>
        <div class="col-md-6">
          <h3><b><i>WHO AM I ?</i></b></h3>
          <p>
            <i>Myself SUNITA RAJPUT.I am from BHOPAL.As per my education i had done PGDCA from MAKHANLAL CHATURVEDI
              VISHWAVIDHALAYA bhopal in 2018 and score 65%.
              I had done B-TECH from E.C.E branch from TECHNOCRATS INSTITUTE OF TECHNOLOGY bhopal in 2016 and score 7.1
              CGPA.In my schooling i would score 65% in 12TH STANDARD
              and 72% in 10TH STANDARD.I am married in 2013.I am very much interested in coding and programming.</i>
          </p>
          <div class="skills-bar">
            <p><b><i> Python</i></b></p>
            <div class="progress">
              <div class="progress-bar" style="width:80%;">80%</div>
            </div>
            <p><b><i>HTML</i></b></p>
            <div class="progress">
              <div class="progress-bar" style="width:90%;">90%</div>
            </div>
            <p><b><i>CSS</i></b></p>
            <div class="progress">
              <div class="progress-bar" style="width:90%;">90%</div>
            </div>
            <p><b><i>Javascript</i></b></p>
            <div class="progress">
              <div class="progress-bar" style="width:70%;">70%</div>
            </div>
            <p><b><i>Wordpress</i></b></p>
            <div class="progress">
              <div class="progress-bar" style="width:60%;">60%</div>
            </div>
            <p><b><i>PHP</i></b></p>
            <div class="progress">
              <div class="progress-bar" style="width:60%;">60%</div>
            </div>
            <p><b><i>Embedded System</i></b></p>
            <div class="progress">
              <div class="progress-bar" style="width:40%;">40%</div>
            </div>
            <p><b><i>Matlab</i></b></p>
            <div class="progress">
              <div class="progress-bar" style="width:50%;">50%</div>
            </div>
          </div>
        </div>
      </div>
    </div>
    </div>
    <!-------------------------------Social Icons--------------------------->
    <div class="social-icons">
      <ul>
        <a href="#">
          <li>
            <i class="fab fa-linkedin"></i>
          </li>
        </a>
        <a href="#">
          <li>
            <i class="fab fa-twitter"></i>
          </li>
        </a>
        <a href="#">
          <li>
            <i class="fab fa-medium"></i>
          </li>
        </a>
        <a href="#">
          <li>
            <i class="fab fa-github"></i>
          </li>
        </a>
        <a href="#">
          <li>
            <i class="fab fa-behance"></i>
          </li>
        </a>
      </ul>
    </div>

    <!-------------------------------Resume--------------------------------->
    <div class="resume" id="resume">
      <div class="container">
        <div class="row">
          <div class="col-nd-6">
            <h4 class="text-center"><b><i>Profile</i></b></h4>
            <ul class="timeline">
              <p><i>I am a full stack enthusiast.<br>I have great abilities and aptitude in web development and web
                  designing.<br>I do
                  programming utilizing Python.<br> I am good at Web Designing as well as using HTML5 and CSS3.<br> I
                  have
                  also a knowledge
                  of some software Matlab, Embedded System ,PHP.<br> I have made a working model based on embedded
                  systems
                  and matlab in college days.<br>
                  I am eagerly waiting to work on new ideas and projects in web designing and would love to upgrade my
                  skills and technology both at the same time.<br> I Know Hindi and English both languages.<br>Strong
                  Interpersonal
                  and Communication skills, M.S-Offic, Execellent Organizational Skills ,Problem Solving
                  ,Python(Programming and
                  Coding),HTML,CSS,Javascript,Social-Media ,Web-Design,Wordpress.</i>
              </p>
            </ul>
          </div>

          <div class="col-nd-6">
            <h3 class="text-center"><b><i>My Education</i></b></h3>
            <ul class="timeline">

              <li>
                <h4><span>2016</span>-<b><i>Bachelor of Engineering from Electronics And Communication</i></b></h4><br>
                <p>
                  <b>University</b>- <i>Rajiv Gandhi Prodhyogiki Vishwavidhalaya,Bhopal(m.p)</i><br>
                  <b>Institute</b> - <i>Technocrats Institute of technology,Bhopal(m.p)</i><br>
                  <b>Session</b>- <i>4yr [2011 to 2015]</i><br>
                  <b>Aggregate</b>-<i> 7.07</i>
                </p>
              </li>

              <li>
                <h4><span>2011</span> -<b><i>Intermediate School(HSC)</i></b></h4>
                <p>
                  <b>Institute</b> -<i> Ideal Higher Secondary School,Bhopal(m.p)</i><br>
                  <b>Session</b>- <i>1yr [2010 to 2011]</i><br>
                  <b>Aggregate</b>- <i>65%</i>
                </p>
              </li>

              <li>
                <h4><span>2009</span>-<b><i> High School(SSC)</i></b></h4>
                <p>
                  <b>Institute</b> -<i>Ideal Higher Secondary School,Bhopal(m.p)</i><br>
                  <b>Session</b>- <i>1yr [2009 to 2010]</i><br>
                  <b> Aggregate</b>- <i>72%</i>

                </p>

              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <!-----------------------------Services----------------------------->
    <div class="services" id="services">
      <div class="container">
        <h3 class="text-center"><b><i>My Offered Services</i></b></h3>
        <p class="text-center"><i>I am a fresher and searching a job as a Web Developer<br>.I made this resume website as a demo website 
            </i></p>

        <div class="row">
          <div class="col-md-20">
            <div class="services-box">
              <i class="fas fa-rocket"></i><span><i> Graphics </i></span>
              <p><i>Subscribe Easy Tutorials<br>Youtube Channel to<br>watch more videos on<br>Website Development
                  and<br>Digital Marketing.Press the<br> bell icon to get<br>updates of new videos</i></p>
            </div>
          </div>
          <div class="row">
            <div class="col-md-35">
              <div class="services-box">
                <i class="fas fa-chart-line"></i><span><i> Marketing </i></span>
                <p><i>I Know Python,Javascript,<br>HTML,CSS ,Basics of PHP<br>as a WEB DEVELOPER.My<br>Communication Skill is also good <br>and I am very much interested in<br> coding and website development<br>.I always want to grasp aur learn new <br>things related to software. </i></p>
              </div>
            </div>
            <div class="row">
              <div class="col-md-35">
                <div class="services-box">
                  <i class="fas fa-laptop"></i><span><i>Development</i></span>
                  <p><i>I made this website by using HTML codes<br>,CSS styles,bootstrap documentation</i></p>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!---------------------------Contact--------------------------->
        <div class="contacts" id="contacts">
          <div class="container text-center">
            <h3><b><i>Contact Me</i></b></h3>
            <p class="text-center"><i>Subscribe Easy Tutorials Youtube Channel to<br> watch more videos on Website
                Development and Digital Marketing</i></p>
            <div class="row">
              <div class="col-md-3">
                <i class="fas fa-phone"></i>
                <p>+91 8319680718</p>
              </div>
              <div class="row">
                <div class="col-md-16">
                  <i class="fas fa-envelope"></i>
                  <p>imsunitarajput@gmail.com</p>
                </div>
              </div>
            </div>
            <button type="button" class="btn btn-primary"><i class="fas fa-download"></i>Resume</button>
            <button type="button" class="btn btn-primary"><i class="fas fa-rocket"></i>Hire Me</button>
          </div>
          <div class=" footer text-center">
            <p>Made with <i class="fas fa-heart"></i>by Easy Tutorials</p>
          </div>
        </div>


  </section>

  <!----------------------------Smooth Scroll----------------------------->
  <script src="smooth-scroll.js"></script>
  <script>var scroll = new SmoothScroll('a [href*="#"]');</script>






</body>

</html>
