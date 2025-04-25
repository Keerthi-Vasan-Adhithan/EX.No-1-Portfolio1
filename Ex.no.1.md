# Ex01 Portfolio
## Date: 04.03.25

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

## PROGRAM:

### index.html:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Keerthi Vasan A - Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Keerthi Vasan A</h1>
    <p>B. Tech in AI & ML | Full Stack Learner | ML Enthusiast</p>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#achievements">Achievements</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <img src="AKV.jpg" alt="Keerthi Vasan A" class="profile-pic">
    <p>I’m a B. Tech student in Artificial Intelligence and Machine Learning at Saveetha Engineering College.
       My interests span Machine Learning, NLP, Image Processing, and now also Full Stack Web Development.
       I'm currently building skills in Docker, Node.js, React, and JavaScript for robust backend and frontend development.</p>
  </section>

  <section id="skills">
    <h2>Technical & Soft Skills</h2>
    <ul>
      <li><strong>Languages:</strong> Python, C, Java, SQL, JavaScript, HTML, CSS</li>
      <li><strong>Frameworks & Libraries:</strong> TensorFlow, PyTorch, Keras, OpenCV, MediaPipe, React, Node.js</li>
      <li><strong>Tools & Platforms:</strong> Docker, Git & GitHub, VS Code, AWS, MySQL, Power BI, Excel, Canva</li>
      <li><strong>Soft Skills:</strong> Leadership, Critical Thinking, Communication</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li><strong>Interactive Learning Platform:</strong> E-learning platform for Data Structures & Algorithms.</li>
      <li><strong>Number Plate Recognition:</strong> Detects plates & logs entry/exit time.</li>
      <li><strong>Medical PPE Verification:</strong> Checks for surgeon equipment using MediaPipe.</li>
    </ul>
  </section>

  <section id="achievements">
    <h2>Achievements & Certificates</h2>
    <ul>
      <li>Data Analytics Intern @ Arjun Vision Tech Solutions (2024)</li>
      <li>Top 10 in Industri AI Hackathon - IITM</li>
      <li>IBM Z Day 2023 & 2024 - Data & AI Skills</li>
      <li>Certificates in NLP, Cloud (AWS), Computer Vision, Public Speaking</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:akeerthivasan2004@gmail.com">akeerthivasan2004@gmail.com</a></p>
    <p>Phone: +91 87788 51447</p>
    <p>LinkedIn: <a href="http://www.linkedin.com/in/keerthivasan-adhithan" target="_blank">Keerthi Vasan A</a></p>
    <p>GitHub: <a href="https://github.com/Keerthi-Vasan-Adhithan" target="_blank">Keerthi-Vasan-Adhithan</a></p>
  </section>

  <footer>
    <p>© 2025 Keerthi Vasan A</p>
  </footer>
</body>
</html>

```

### style.css:

```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: 'Segoe UI', sans-serif;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
  }
  
  header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 30px 20px;
  }
  
  header h1 {
    font-size: 2.5em;
  }
  
  header p {
    margin-top: 10px;
    font-style: italic;
  }

  .profile-pic {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 20px;
    border: 3px solid #444;
  }
  
  nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 15px 0;
    background: #444;
  }
  
  nav ul li {
    margin: 0 15px;
  }
  
  nav ul li a {
    color: white;
    text-decoration: none;
    padding: 8px 12px;
    transition: background 0.3s, color 0.3s;
  }
  
  nav ul li a:hover {
    background-color: white;
    color: #444;
    border-radius: 5px;
  }
  
  section {
    padding: 40px 20px;
    max-width: 900px;
    margin: auto;
  }
  
  section h2 {
    margin-bottom: 20px;
    color: #333;
  }
  
  ul li {
    margin-bottom: 10px;
  }
  
  footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px 10px;
  }
  

```


## OUTPUT
![image](https://github.com/user-attachments/assets/347a5df7-79bb-4f51-9b3b-9ffbc594e8fa)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
