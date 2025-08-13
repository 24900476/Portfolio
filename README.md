# Ex01 Portfolio
# Name : Kabira  A
# Reg N0 : 212224040146
## Date:13/08/2025

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
# index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About Me</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="section"><br>
    <br>
    <h1>Welcome to My Portfolio</h1>
    <h1>Kabira A</h1>
    <h3>B.E. CSE,II Year</h3><br>
    <img src="c:\Users\Akbar\Downloads\butterfly.jpg" alt="My Photo" style="width: 160px;" class="profile-photo"><br><br><br>
    <h4>
        
    <p>I am Kabira, a second-year Computer Science and Engineering student pursuing a BE degree.</p>
    <p>I am passionate about web development and have an interest in Data Science .</p>
    <p>I enjoy building innovative projects and enhancing my skills in technology.</p>
    <p>I am enthusiastic about collaborating on projects, solving problems,<br><br> and contributing to open-source communities as I develop as a software professional.</p>
    </h4>
    
  </section>

  <section id="about" class="section">
    <br><br>
    <h2>About Me</h2><br>
    <p>I am a Computer Science and Engineering student passionate about web development and Data science.</p>
    <p>I have professional experience and strong skills in Excel and Microsoft Word, which help me handle data analysis, reporting, and documentation efficiently.</p>
    <p>I am a beginner in programming languages like Python and C, passionate about strengthening my coding fundamentals and problem-solving abilities.</p>
    <p>I am committed to continuous learning, and I actively explore new technologies and programming languages to expand my expertise.</p>
    <p>My goal is to become a proficient full-stack developer and leverage technology to solve real-world problems.</p>
    <p>My interests include full-stack development, AI integration in web apps, and developing user-centric designs.</p>
    
  </section>

  <section id="education" class="section">
    <br><br>
    <h2>Education</h2>
    <center>
      <table style="padding: 30px; border: #333;">
        <tr>
            <th>Batch</th>
            <th>Institution</th>
            <th>Course</th>
            <th>Percentage</th>
        </tr>
        <tr>
            <td>2024-2028</td>
            <td>Saveetha Engineering College</td>
            <td>BE Computer Science and Engineering</td>
            <td>80%</td>
        </tr>
        <tr>
            <td>2023-2024</td>
            <td>JaiGopal Garodia Girls Govt Higher Sec School</td>
            <td>12th - Higher Secondary Education</td>
            <td>84.83%</td>
        </tr>
        <tr>
            <td>2021-2022</td>
            <td>JaiGopal Garodia Girls Govt Higher Sec School</td>
            <td>10th</td>
            <td>86%</td>
        </tr>
    </table>
    </center>
  </section>

  <section id="skills" class="section">
    <br><br>
    <h2>Skills</h2><br>
    <h2>Technical Skills</h2><br>
<h4>
  I) Programming:   C, Python,c++
</h4>
<h4>
 II) Web Development:   HTML, CSS, JavaScript
</h4>
<h4>
 III) Machine Learning:   Data Science, Algorithms
</h4>
<br>
    
    <h2>Soft Skills</h2><br>
    <h4>I) Communication</h4>
    <h4>II)Team collaborater</h4>
    <h4>III)Probelm-Solving</h4>
    
</section>

  

  <section id="contact" class="section">
    <br><br>
    <h2>Contact Me</h2><br><br>
    <p>Email: kabira200703@gmail.com</p>
    <p>LinkedIn: <a href="#">https://www.linkedin.com/in/kabira-a-4867a832a</a></p>
    <p>GitHub: <a href="#">https://github.com/24900476</a></p><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
  

  <footer>
    <p>&copy; 2025 My Portfolio. All rights reserved.</p>
  </footer>
</section>
  
</body>
</html>
```
# style.css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    scroll-behavior: smooth;
    color: white; /* Text color, adjust if needed */
}

/* Table styling */
table {
    width: 70%;
    margin: auto;
    border-collapse: collapse;
    background: rgba(0, 0, 0, 0.5); /* Slight translucent background for table readability */
    box-shadow: 0 4px 15px rgba(0,0,0,0.3);
    border-radius: 8px;
    overflow: hidden;
    color: white;
}
th, td {
    border: 1px solid #ddd;
    padding: 10px;
    text-align: center;
}
th {
    background-color: rgba(255, 221, 153, 0.7);
    color: black;
}

/* Navbar */
nav {
    background: linear-gradient(90deg, #333, #555);
    padding: 10px 0;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 100;
    box-shadow: 0 2px 8px rgba(0,0,0,0.7);
}
nav ul {
    list-style-type: none;
    text-align: center;
}
nav ul li {
    display: inline;
    margin: 0 20px;
}
nav a {
    text-decoration: none;
    color: white;
    font-weight: bold;
    transition: 0.3s;
}
nav a:hover {
    color: #ffcc00;
    text-shadow: 0 0 5px #fff;
}

/* Sections */
.section {
    padding: 80px 20px;
    min-height: 100vh;
    text-align: center;
    position: relative;
    color: white; /* Adjust text color if needed based on images */
}

/* Background images without overlays or colors */

#home {
    background: url('port.jpg') no-repeat center center/cover;
}

#about {
    background: url('port.jpg') no-repeat center center/cover;
}

#education {
    background: url('port.jpg') no-repeat center center/cover;
}

#skills {
    background: url('port.jpg') no-repeat center center/cover;
}

#contact {
    background: url('port.jpg') no-repeat center center/cover;
}

/* Footer */
footer {
    background: linear-gradient(90deg, #333, #555);
    color: white;
    text-align: center;
    padding: 10px 0;
}

/* Profile image */
.profile-photo {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-top: 20px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.5);
    object-fit: cover;
    transition: transform 0.3s ease-in-out;
}
.profile-photo:hover {
    transform: scale(1.05);
}
```


## OUTPUT
<img width="1920" height="1080" alt="page1" src="https://github.com/user-attachments/assets/3cf95322-4940-422f-a993-6e756d9a3641" />

<img width="1920" height="1080" alt="page 2" src="https://github.com/user-attachments/assets/9529070c-fda1-44fa-8084-ca32f072dec8" />

<img width="1920" height="1080" alt="page 3" src="https://github.com/user-attachments/assets/c0d745f4-67cf-4192-8686-5f67e1f333e4" />

<img width="1920" height="1080" alt="page 4" src="https://github.com/user-attachments/assets/10d6d80a-1866-441e-9926-39b8bce3f92c" />

<img width="1920" height="1080" alt="page5" src="https://github.com/user-attachments/assets/db87f18c-d071-4bca-964b-0498d3fcd9a0" />





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
