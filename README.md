# Portfolio-Page
Creating a personal portfolio using CSS and HTML is a popular beginner web development project

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <h1>TASLIM KHAN</h1>
            <p class="tagline">Web Developer | Designer | Creative Thinker</p>
        </div>
    </header>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <img src="Taslim khan.jpg" alt="Taslim Khan" class="profile-img">
            <p>
                Hi, I'm Taslim Khan, a passionate web developer with experience in HTML, CSS, JavaScript, and more. 
                I love creating responsive and user-friendly websites. Here's a bit more about my skills and projects!
            </p>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <div class="container">
            <h2>Skills</h2>
            <ul>
                <li>HTML & CSS</li>
                <li>JavaScript</li>
                <li>Responsive Design</li>
                <li>UI/UX Design</li>
                <li>Version Control (Git)</li>
            </ul>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <div class="container">
            <h2>Projects</h2>
            <div class="project">
                <h3>Social Media Marketing Website </h3>
                  <p>  •  A website design for social media marketing using HTML, CSS and Javascript.</p>
            </div>
            <div class="project">
                <h3>Portfolio Website</h3>
                 <p> 	 	 	    
                    •Developed a responsive portfolio website using HTML, CSS and Javascript that highlighted excellent front-end development abilities. 
                    •The website was also equipped with interactive features to enhance user experience and maximize accessibility. 
                 </p>
            </div>
        </div>
    </section>

    <!-- Resume Section -->
    <section id="resume">
        <div class="container">
            <h2>Resume</h2>
            <p>Download my resume to learn more about my experience and qualifications.</p>
            <a href="resume.pdf" download class="btn">Download Resume</a>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <p>Email: taslimkhan06262@gmail.com</p>
            <p>Phone: +919508489651</p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2025 Taslim. All rights reserved.</p>
            <ul>
                <li><a href="#">LinkedIn</a></li>
                <li><a href="#">GitHub</a></li>
                <li><a href="#">Twitter</a></li>
            </ul>
        </div>
    </footer>
</body>
</html>

CSS CODE:-
/* General Styles */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

/* Header */
header {
    background: #333;
    color: #fff;
    padding-top: 30px;
    min-height: 70px;
    border-bottom: #5599ff 3px solid;
}

header h1 {
    text-align: center;
    margin: 0;
    font-size: 36px;
}

header .tagline {
    text-align: center;
    font-size: 18px;
    color: #5599ff;
}

/* Sections */
section {
    padding: 20px 0;
}

h2 {
    text-align: center;
    color: #333;
}

/* About Section */
#about .profile-img {
    display: block;
    margin: 20px auto;
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 3px solid #5599ff;
}

/* Skills Section */
#skills ul {
    list-style: none;
    padding: 0;
    text-align: center;
}

#skills ul li {
    background: #5599ff;
    color: #fff;
    display: inline-block;
    padding: 10px 20px;
    margin: 5px;
    border-radius: 5px;
}

/* Projects Section */
.project {
    background: #fff;
    padding: 20px;
    margin: 20px 0;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.project img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 10px 0;
}

/* Resume Section */
#resume .btn {
    display: block;
    width: 200px;
    margin: 20px auto;
    padding: 10px;
    text-align: center;
    color: #fff;
    background-color: #5599ff;
    text-decoration: none;
    border-radius: 5px;
}

#resume .btn:hover {
    background: #5599ff;
}

/* Contact Section */
#contact p {
    text-align: center;
    font-size: 18px;
}

/* Footer */
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}

footer ul {
    padding: 0;
    list-style: none;
}

footer ul li {
    display: inline;
    margin: 0 10px;
}

footer ul li a {
    color: #5599ff;
    text-decoration: none;
}
