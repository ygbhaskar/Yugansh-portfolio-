<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Yugansh Bhaskar</title>

<link rel="stylesheet" href="styles.css">

<!-- Icons -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">

</head>
<body>

<header>
    <nav class="navbar glass">
        <div class="logo">Yugansh</div>

        <ul class="nav-links" id="navLinks">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>

        <div class="hamburger" onclick="toggleMenu()">
            <i class="fas fa-bars"></i>
        </div>
    </nav>
</header>

<section id="home" class="hero">
    <h1>Hi, I'm <span class="highlight">Yugansh</span></h1>
    <h2><span class="typing"></span></h2>
    <a href="#contact" class="btn">Hire Me</a>
</section>

<section id="about" class="glass reveal">
    <h2>About Me</h2>
    <p>
        Electronics & Communication Engineer passionate about AI, Cloud, Embedded Systems, 
        and creating visually stunning user experiences.
    </p>
</section>

<section id="skills">
    <h2>Skills</h2>
    <div class="skills-grid">

        <div class="card"><i class="fas fa-microchip"></i><p>Embedded Systems</p></div>
        <div class="card"><i class="fab fa-python"></i><p>Python</p></div>
        <div class="card"><i class="fas fa-code"></i><p>C/C++</p></div>
        <div class="card"><i class="fas fa-cloud"></i><p>Cloud</p></div>
        <div class="card"><i class="fas fa-brain"></i><p>AI/ML</p></div>
        <div class="card"><i class="fab fa-git-alt"></i><p>Git</p></div>

    </div>
</section>

<section id="projects">
    <h2>Projects</h2>

    <div class="project-card glass">
        <h3>IoT Automation</h3>
        <p>Arduino + Raspberry Pi system</p>
    </div>

    <div class="project-card glass">
        <h3>ML Prediction</h3>
        <p>AI model for analytics</p>
    </div>

</section>

<section id="contact" class="glass">
    <h2>Contact</h2>
    <p>Email: Ygbhaskar3367@gmail.com</p>
</section>

<footer>
    <p>© 2026 Yugansh Bhaskar</p>
</footer>

<script src="script.js"></script>
</body>
</html>
