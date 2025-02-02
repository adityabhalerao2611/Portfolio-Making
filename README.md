<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aditya Bhalerao - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="container">
            <h1 class="name">Aditya Bhalerao</h1>
            <p class="tagline">Crafting impactful digital experiences with code</p>
        </div>
    </header>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <img src="passport.jpg" alt="Aditya Bhalerao" class="profile-img">
            <p class="bio">
                Hello! I'm Aditya, a passionate web developer with a love for building elegant, efficient, and user-friendly websites. With a strong foundation in HTML, CSS, and JavaScript, I specialize in front-end development but also enjoy tackling back-end challenges. My goal is to create seamless web experiences that combine functionality with creativity. I’m constantly learning and growing as I work on new projects and explore emerging technologies.
            </p>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <div class="container">
            <h2>My Skills</h2>
            <ul class="skills-list">
                <li class="skill-item html">HTML & CSS</li>
                <li class="skill-item javascript">JavaScript</li>
                <li class="skill-item react">React JS</li>
                <li class="skill-item node">Node.js</li>
                <li class="skill-item backend">Back-end Development</li>
            </ul>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <div class="container">
            <h2>My Projects</h2>
            <div class="project">
                <img src="Html webpage.png" alt="HTML Webpage" class="project-img">
                <h3>HTML Webpage</h3>
                <p>Description of the HTML webpage project, what was done, technologies used, etc.</p>
            </div>
            <div class="project">
                <img src="Amazon-clone.jpg" alt="Website Clone" class="project-img">
                <h3>Website Clone</h3>
                <p>Description of the website clone project, what was done, technologies used, etc.</p>
            </div>
        </div>
    </section>

    <!-- Resume Section -->
    <section id="resume">
        <div class="container">
            <h2>Resume</h2>
            <p>Click <a href="C:\Users\Aditya Bhalerao\OneDrive\Documents\resume pdf.pdf" download>here</a> to download my resume.</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <p>Email: your.email@example.com</p>
            <p>Phone: +1234567890</p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2025 Aditya Bhalerao. All Rights Reserved.</p>
        </div>
    </footer>

</body>
</html>

.css{
/* General Styles */
body {
    font-family: 'Roboto', sans-serif;
    line-height: 1.8;
    margin: 0;
    padding: 0;
    background-color: #f4f4f9;
    color: #333;
}

header {
    background-color: #2c3e50;
    color: #fff;
    padding: 30px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 3rem;
    font-family: 'Pacifico', cursive;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 10px 0 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.1rem;
}

/* Sections */
section {
    padding: 30px;
    margin: 20px auto;
    max-width: 800px;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
}

section h2 {
    color: #2c3e50;
    border-bottom: 2px solid #2c3e50;
    padding-bottom: 10px;
    font-size: 2rem;
    font-family: 'Pacifico', cursive;
}

.profile-img {
    display: block;
    margin: 20px auto;
    border-radius: 50%;
    width: 200px;
    height: 200px;
    object-fit: cover;
    border: 5px solid #2c3e50;
}

p {
    font-size: 1.1rem;
    text-align: justify;
}

ul {
    list-style-type: square;
    padding-left: 20px;
}

ul li {
    margin-bottom: 10px;
    font-size: 1.1rem;
}

/* Gallery */
.gallery-container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.gallery-container img {
    width: 30%;
    margin: 10px 0;
    border-radius: 10px;
    transition: transform 0.3s ease;
}

.gallery-container img:hover {
    transform: scale(1.05);
}

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    background-color: #2c3e50;
    color: #fff;
    margin-top: 20px;
    font-size: 1rem;
}
}
