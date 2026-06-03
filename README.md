# Ex01 Portfolio
## Date:

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
<title>Portfolio</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:#f4f4f4;
    color:#333;
}

header{
    background:#222;
    color:white;
    padding:15px 0;
}

nav{
    width:90%;
    margin:auto;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

nav ul{
    list-style:none;
    display:flex;
}

nav ul li{
    margin-left:20px;
}

nav ul li a{
    color:white;
    text-decoration:none;
}

nav ul li a:hover{
    color:#00bcd4;
}

.hero{
    height:100vh;
    background:linear-gradient(135deg,#00bcd4,#3f51b5);
    color:white;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
}

.hero h2{
    font-size:3rem;
}

.hero p{
    margin:15px 0;
    font-size:1.2rem;
}

.btn{
    background:white;
    color:#333;
    padding:12px 25px;
    text-decoration:none;
    border-radius:5px;
    font-weight:bold;
}

.section{
    padding:60px 10%;
    text-align:center;
}

.section h2{
    margin-bottom:20px;
    color:#00bcd4;
}

.skills,
.projects{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:20px;
}

.card{
    background:white;
    width:220px;
    padding:20px;
    border-radius:10px;
    box-shadow:0 2px 10px rgba(0,0,0,0.1);
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
}
</style>
</head>

<body>

<header>
    <nav>
        <h1>THARUN</h1>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section class="hero">
    <h2>Hello, I'm Tharun</h2>
    <p>Web Developer | AI Enthusiast | Student</p>
    <a href="#contact" class="btn">Contact Me</a>
</section>

<section id="about" class="section">
    <h2>About Me</h2>
    <p>
        I am a passionate web developer who enjoys creating responsive
        websites and learning new technologies.
    </p>
</section>

<section id="skills" class="section">
    <h2>Skills</h2>
    <div class="skills">
        <div class="card">HTML</div>
        <div class="card">CSS</div>
        <div class="card">JavaScript</div>
        <div class="card">React</div>
        <div class="card">Python</div>
    </div>
</section>

<section id="projects" class="section">
    <h2>Projects</h2>
    <div class="projects">
        <div class="card">
            <h3>Portfolio Website</h3>
            <p>Responsive personal portfolio.</p>
        </div>

        <div class="card">
            <h3>AI Image Generator</h3>
            <p>Generated realistic AI images.</p>
        </div>

        <div class="card">
            <h3>React App</h3>
            <p>Modern UI application using React.</p>
        </div>
    </div>
</section>

<section id="contact" class="section">
    <h2>Contact</h2>
    <p>Email: tharun@example.com</p>
    <p>Phone: +91 9876543210</p>
</section>

<footer>
    <p>© 2026 Tharun. All Rights Reserved.</p>
</footer>

</body>
</html>
```

## OUTPUT
<img width="1910" height="978" alt="image" src="https://github.com/user-attachments/assets/55c34955-b88b-4fb4-9f03-ba642102e0c5" />
<img width="1903" height="972" alt="image-1" src="https://github.com/user-attachments/assets/e42c7df2-9f57-4450-a2c9-ad102a2bd104" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
