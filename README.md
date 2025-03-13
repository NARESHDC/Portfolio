# Ex01 Portfolio
## Date:13-03-2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Deepika S | Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Deepika S</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#internship">Internship</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="about">
        <h2>About Me</h2>
        <p>Hi, I'm Deepika S! A 3rd-year Artificial Intelligence and Data Science student with a passion for building intelligent systems and scalable applications. My expertise lies in Full-Stack Java Development and Data Science, enabling me to craft efficient, data-driven solutions.</p>
    </section>
    
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Enhancing SAR Image Interpretation</h3>
            <p>A deep learning-based SAR image colorization project designed to improve data interpretation and analysis for better decision-making in remote sensing. Built using Python, TensorFlow, and OpenCV.</p>
        </div>
        <div class="project">
            <h3>Predictive Hiring with Data Science</h3>
            <p>An AI-driven recruitment system utilizing predictive analytics and machine learning to improve hiring decisions, reduce bias, and enhance candidate selection.</p>
        </div>
        <div class="project">
            <h3>Full-Stack Web Application for Data Analytics</h3>
            <p>Developed a full-stack web platform integrating Spring Boot and React.js for interactive data visualization and real-time analytics.</p>
        </div>
        <div class="project">
            <h3>AI-Powered Chatbot for Customer Support</h3>
            <p>Designed an NLP-based chatbot for automated customer support, built using Python, Flask, and Dialogflow.</p>
        </div>
    </section>
    
    <section id="internship">
        <h2>Internship Experience</h2>
        <p><strong>Arjun Vision Tech Solutions | 2024</strong></p>
        <p>Gained hands-on experience in data science, focusing on predictive modeling, machine learning algorithms, and SAR image colorization using deep learning.</p>
    </section>
    
    <section id="education">
        <h2>Education</h2>
        <p><strong>B.Tech in Artificial Intelligence and Data Science</strong><br>Saveetha Engineering College (2022-2026)<br>CGPA: 9.2/10</p>
        <p><strong>Higher Secondary Education</strong><br>Bharathiyar Matric. Hr. Sec. School (2021-2022)<br>Percentage: 89%</p>
    </section>
    
    <section id="skills">
        <h2>Skills</h2>
        <h3>Technical Skills</h3>
        <ul>
            <li>Programming: Java, Python, SQL, JavaScript</li>
            <li>Web Development: HTML, CSS, React.js, Spring Boot</li>
            <li>Data Science: Machine Learning, Deep Learning, Data Analysis</li>
            <li>Computer Vision: SAR Image Processing, Image Colorization</li>
        </ul>
        <h3>Soft Skills</h3>
        <ul>
            <li>Communication, Teamwork, Problem-Solving, Leadership</li>
        </ul>
    </section>
    
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: deepikas88606@gmail.com</p>
        <p>Address: Chennai, India</p>
        <p>Phone: 8248425226</p>
        <p>GitHub: <a href="#">github.com/deepikas</a></p>
        <p>LinkedIn: <a href="#">linkedin.com/in/deepikas</a></p>
    </section>
    
    <footer>
        <p>&copy; 2025 Deepika S. All Rights Reserved.</p>
    </footer>
</body>
</html>
```
## Style.css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
    color: #333;
}

header {
    background-color: #0073e6;
    color: white;
    padding: 15px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav ul li {
    display: inline;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 20px;
    margin: 20px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1, h2 {
    text-align: center;
}

.project {
    background-color: #e6f2ff;
    padding: 15px;
    border-radius: 8px;
    margin: 10px 0;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #0073e6;
    color: white;
    position: relative;
    bottom: 0;
    width: 100%;
}

```
## OUTPUT
![por1](https://github.com/user-attachments/assets/f3688b0f-9293-435a-b8ce-2171f00098f5)
![por2](https://github.com/user-attachments/assets/751c994d-15a2-44ac-86e8-a69efd28e063)
![por4](https://github.com/user-attachments/assets/113ad8fd-c669-48dd-a6b2-e16842f714c6)
![por5](https://github.com/user-attachments/assets/a9b2b975-dd1d-4fd6-b02a-81bc2923dfb7)
![por6](https://github.com/user-attachments/assets/fe5537bd-3b6f-4b1e-9797-68cf635e71f0)
![por7](https://github.com/user-attachments/assets/90005506-e51c-46cf-9975-7dfd347344e9)
![por8](https://github.com/user-attachments/assets/5a4c7d03-5e18-435c-a480-99dc3f49efbf)
![por9](https://github.com/user-attachments/assets/572eefbb-1228-4d0e-9efe-bd599391bbe3)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
