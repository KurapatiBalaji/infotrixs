# infotrixs I completed the task-1, hosting a portfolio using S3.

https://infotrixs32.s3.ap-south-1.amazonaws.com/balaji.html

here the view of portfolio 
![image](https://github.com/KurapatiBalaji/infotrixs/assets/109504895/41a35946-9871-406d-85c7-7e2a59b49d1c)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem 0;
    position: fixed;
    width: 100%;
    top: 0;
}

/* Styling for navigation links */
nav ul li {
    display: inline;
    margin: 0 15px;
    transition: all 0.3s ease-in-out;
}

nav ul li:hover {
    transform: scale(1.1);
}

/* Styling for sections */
section {
    padding: 50px;
    background-color: white;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    margin: 20px auto;
    border-radius: 8px;
}

/* Styling for headings */
h1 {
    font-size: 36px;
    margin-bottom: 20px;
}

/* Styling for project items */
.project {
    margin-bottom: 30px;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 8px;
    background-color: #f7f7f7;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease-in-out;
}

.project:hover {
    transform: translateY(-5px);
}

/* Styling for contact details */
#contact a {
    color: #007bff;
}

/* Responsive styles */
@media (max-width: 768px) {
    /* ... (same as before) */
}

    </style>
    <title>Balaji Kurapati - Portfolio</title>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="about">
        <h1>About Me</h1>
        <p>Hello! I'm Balaji Kurapati, a passionate web developer with a keen interest in creating user-friendly and visually appealing websites.</p>
    </section>
    
    <section id="skills">
        <h1>Skills</h1>
        <ul>
            <li>AWS (Amazon Web Services)</li>
            <li>HTML and CSS</li>
            <li>Data Analysis</li>
            <!-- Add more skills as needed -->
        </ul>
    </section>
    
    <section id="projects">
        <h1>Projects</h1>
        <div class="project">
            <h2>Income Classification</h2>
            <p>Implemented a machine learning model to classify income levels based on demographic features.</p>
        </div>
        <div class="project">
            <h2>ETL Architecture</h2>
            <p>Designed an ETL (Extract, Transform, Load) architecture for processing and analyzing large datasets.</p>
        </div>
        <!-- Add more projects as needed -->
    </section>
    
    <section id="contact">
        <h1>Contact Me</h1>
        <p>Feel free to reach out to me at: <a href="mailto:balaji@example.com">balaji@example.com</a></p>
    </section>
</body>
</html>



