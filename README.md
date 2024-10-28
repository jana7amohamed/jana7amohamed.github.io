<!DOCTYPE html>
<html lang="en">
<head>
   <link rel="stylesheet" href="style.css">
   <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Corrected spelling -->
    <title>Simple Portfolio</title>
    <link rel="stylesheet" href="style.css"> <!-- Ensure this file exists in the same directory -->
    <link href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css" rel="stylesheet">
</head>
<body>
    <header class="header">
        <a href="#" class="logo"><span>Han</span>nah</a> <!-- Fixed broken tag -->
        <nav class="navbar">
            <a href="#" class="active">Portfolio</a>
            <a href="#">Service</a>
            <a href="#">Experience</a>
            <a href="#">Projects</a>
            <a href="#">Education</a>
        </nav>
        <a href="#" class="contact">Contact Me</a>
    </header>
    <section class="home">
        <div class="home-content">
            <h3>Hi</h3>
            <h1>I'm <span>Jana<br></span>a student at Alexandria STEM School</h1>
            <p>Write here something interesting!</p>
            <div class="btn-box">
                <button class="btn-1">Hire Me</button> <!-- Ensure class name matches CSS -->
                <button class="btn-2">Experience</button> <!-- Ensure class name matches CSS -->
            </div>
        </div>
        <div class="img-box"> <!-- Fixed class name from imgbox to img-box -->
            <img src="image.jpg" alt="Image Description"> <!-- Ensure this image file exists -->
        </div>
    </section>
    <section class="about">
        <div class="about-img">
            <img src="image.jpg" alt="About Me Image"> <!-- Ensure this image file exists -->
        </div>
        <div class="about-content">
            <h2 class="heading">About <span>Me</span></h2>
            <h3>Frontend <span>Developer</span></h3>
            <p>Anythinggg</p>
            <a href="#" class="btn-2">Experience</a>
        </div>
    </section>
    <section class="contact-form">
        <h2 class="contact-me">Contact <span>Me</span></h2>
    </section>
 <footer>
        <div class="social">
            <a href="#"><i class="bx bxl-facebook-circle"></i></a>
            <a href="#"><i class="bx bxl-linkedin-square"></i></a> <!-- Corrected class name -->
            <a href="#"><i class="bx bxl-instagram-alt"></i></a>
        </div>
    </footer>
</body>
</html>
