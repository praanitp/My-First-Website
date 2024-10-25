<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Website</title>
    <style>
        /* General Styles */
        html {
    scroll-behavior: smooth;
}

body {
    font-family: 'Times New Roman', sans-serif;
    margin: 0;
    padding: 5;
    background-color: #e7aaaa;
    color: #000000;
}

/* Header Styles */
header {
    background-color: #5f7ee5;
    color: white;
    padding: 20px 0;
    text-align: center;
    box-shadow: 0 7px 4px rgba(0, 0, 0, 0.1);
}

header h1 {
    margin: 0;
    font-size: 2.5em;
}

/* Navigation Styles */
nav {
    background-color: #ad8585;
    padding: 20px 0;
    text-align: center;
    border-radius: 5000px;
    box-shadow: 0 8px 10px rgba(0, 0, 0, 0.1);
}

nav a {
    color: rgb(255, 255, 255);
    text-decoration: none;
    font-size: 1.1em;
    margin: 0 15px;
    padding: 8px 12px;
    display: inline-block;
    transition: background-color 0.3s ease;
}

nav a:hover {
    background-color: #0d1527;
    border-radius: 500px;   
}

/* Section Styles */
section {
    margin: 40px 20px;
    padding: 20px;
    background-color: rgb(218, 206, 206);
    border-radius: 20px;
    box-shadow: 0 8px 10px rgba(0, 0, 0, 0.1);
}

section h2 {
    font-size: 2em;
    color: #000000;
    border-bottom: 2px solid #1c49da;
    padding-bottom: 10px;
}

section p {
    font-size: 1.em;
    line-height: 1.6;
    color: #000000;
}

/* Footer Styles */
footer {
    background-color: #5f7ee5;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
    font-size: 0.9em;
}

footer p {
    margin: 0;
}

/* Responsive Media Queries */
@media (max-width: 768px) {
    header h1 {
        font-size: 2em;
    }
    
    nav a {
        font-size: 1em;
        margin: 0 10px;
    }
    
    section {
        margin: 20px 10px;
    }

    section h2 {
        font-size: 1.8em;
    }
}

@media (max-width: 480px) {
    nav a {
        font-size: 0.9em;
    }

    section h2 {
        font-size: 1.5em;
    }
}

    </style>
</head>
<body>

<header>
    <h1>Welcome to My Personal Website</h1>
</header>

<center><h1> Home </h1></center>

<h6>

<nav>
    <a href="#about">|About Me|</a> 
    <a href="#education">|Educational Background|</a>
    <a href="#experience">|Experience|</a>
    <a href="#awards">|Awards and Achievements|</a>
    <a href="#projects">|Projects|</a>
    <a href="#membership">|Membership|</a>
    <a href="#events">|List of Events (Organised/Attended)|</a>
    <a href="#courses">|Courses Completed|</a>
    <a href="#contact">|Contact Address|</a>
</nav>
</h6>

<section id="about">
    <h2>About Me</h2>
    <p><b>Name</b> - Praanit Chakraborty</p>
    <p><b>Date of Birth</b> - 5 September 2005</p>
    <p><b>Age</b> - 19 yrs</p>
    <p><b>Gender</b> - Male</p>
    <p><b>Mother's Name</b> - Soma Chakraborty</p>
    <p><b>Father's Name</b> - Late Asis Chakrabarty</p>
    <p><b>Blood Group</b> - AB+</p>
</section>

<section id="education">
    <h2>Educational Background</h2>
    <p><b>School</b> - <b>Khalsa Model Senior Secondary School</b>, Dunlop, Kolkata (2012 - 2024)</p>
    <p><b>Current</b> - Pursuing <b>B.Tech</b> in <b>CSE (AIML)</b> from <b>Institute of Engineering and Management, Newtown, Kolkata (2024)</b></p>
</section>
</section>

<section id="experience">
    <h2>Experience</h2>
    <p>Has experience of <b>2 years</b> as a <b>Private Tutor</b> for teaching <b>Physics</b>.</p>
    <p>Successfully started a company named <b>Trend Troves</b> which sold Jewelleries and earned a profit of <b>5000 INR</b> in just 1 week.</p>
</section>

<section id="awards">
    <h2>Awards and Achievements</h2>
    <p>Won the <b>All India Chess Tournament</b> in 2022.</p>
    <p>Won the <b>National Level Chess Tournament</b> in 2023</p>
</section>

<section id="projects">
    <h2>Projects</h2>
    <p>Successfully started a company named <b>Trend Troves</b> in 2024 as <b>Economics Project</b> and earned a profit of <b>5000 INR</b> in just 1 Week.</p>
</section>

<section id="membership">
    <h2>Membership</h2>
    <p>Member of <b>Panihati Sporting Club.</b></p>
    <p>Member of <b>Pragya UEMK.</b></p>
</section>

<section id="events">
    <h2>List of Events (Organised/Attended)</h2>
    <p>Organised an <b>Inter School Debate Competition</b> on the behalf of <b>Khalsa Model Senior Secondary School</b> in 2022.</p>
    <p>Attended <b>UEMKCON</b> in 2024.</p>
    <p>Attended <b>IEEE Elevate</b> in 2024.</p>
    <p>Attended <b>Pragya UEMK "Hit-the-Homerun" Sports Quiz </b> in 2024.</p>
    
</section>

<section id="courses">
    <h2>Courses Completed</h2>
    <p><b>Completed Soft Skill and Personality Development Course</b> organised by NPTEL in 2024. </p>
</section>

<section id="contact">
    <h2>Contact Address</h2>
    <p><b>Mobile no.</b> - 9330162435, 9073582385</p>
    <p><b>Email</b> - praanitchakraborty0509@gmail.com</p>
</section>

<footer>
    <p>Developed by Praanit Chakraborty, Section - M, Roll no. - 41.</p>
</footer>

</body>
</html>
