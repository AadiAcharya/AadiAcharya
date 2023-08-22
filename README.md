<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Delicious+Handrawn&family=Poppins:wght@400;700&family=Varela+Round&display=swap"
    rel="stylesheet" />
  <title>Aadi - Web- Developer Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>

<body>
  <div class="container">
    <div class="sidebar sidebarGo">
      <nav>
        <ul>
          <li><a href="/">Home</a></li>
          <li><a href="/intro.html">My Intro</a></li>
          <li><a href="/services.html">Services</a></li>
          <li><a href="/blog.html">Blog</a></li>
          <li><a href="/contact.html">Contact Me</a></li>
        </ul>
      </nav>
    </div>
    <div class="main">
      <div class="hamburger">
        <img class="ham" src="ham.png" alt="" width="23px">
        <img class="cross" src="cross.png" alt="" width="23px">
      </div>
      <div class="infoContainer">
        <div class="devInfo">
          <div class="hello">Hi I am</div>
          <div class="name">Aaditya Acharya</div>
          <div class="about">Developer, Programmer</div>
          <div class="moreabout">
            I am a Developer and I love Programing. I live in Chitwan and I
            love travelling
          </div>
          <div class="buttons">
            <a href="/cv.txt"> <button class="btn">Download CV</button></a>
            <!-- Contact me part will open in new tab -->
            <a href="/contact.html" target="_blank"><button class="btn">Contact Me</button></a>
          </div>
        </div>
        <div class="devPic"><img src="me.jpg" alt="Aaditya Acharya" /></div>
      </div>
    </div>
  </div>

  <script src="script.js"></script>

</body>

</html>

