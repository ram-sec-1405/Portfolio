# Ex01 Portfolio
## Date: 14-03-2025

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
### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=0.5">
    <title>College Portfolio</title>
    <link rel="stylesheet" href="ex01.css">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            text-align: center;
        }
        header {
            background: linear-gradient(to right, #1e3c72, #2a5298);
            color: white;
            padding: 2rem;
            text-align: center;
            
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 20px;
        }
        nav ul li a {
            color: #FFD700;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.2rem;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #ff6347;
        }
        section {
            padding: 4rem;
        }
        .info-box {
            background: white;
            padding: 2rem;
            margin: 2rem auto;
            max-width: 800px;
           
            border-radius: 15px;
            transition: transform 0.3s ease-in-out;
        }
        .info-box:hover {
            transform: scale(1.02);
        }
        #contact {
            background: #2a5298;
            color: white;
            padding: 3rem;
        }
        footer {
            background-color: #1e3c72;
            color: white;
            text-align: center;
            padding: 1.5rem;
            margin-top: 2rem;
        }
        .button {
            display: inline-block;
            padding: 12px 25px;
            background: #ff6347;
            color: white;
            text-decoration: none;
            font-size: 1rem;
            border-radius: 5px;
            transition: background 0.3s;
        }
        .button:hover {
            background: #FFD700;
            color: #333;
        }
    </style>
</head>
<body>
    <header>
        <h1>Portfolio For College</h1>

        <nav>
            <ul>

                <li><a href="#about">About</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>

            </ul>
        </nav>
    </header>
    
    
    
    <section id="education">
        <h2>Education</h2>
        <div class="info-box">
            <p><strong>Degree:</strong>INFORMATION TECHNOLOGY</p>
            <p><strong>Institution:</strong> SAVEETHA ENGINEERING COLLEGE</p>
            <p><strong>Year of Study:</strong> 2nd Year</p>
        </div>
    </section>
    
    <section id="skills">
        <h2>Skills</h2>
        <div class="info-box">
            <p>✔ Programming: Python, Java, HTML, CSS, JavaScript</p>
            <p>✔ Web Development: React, Node.js</p>
            <p>✔ Databases: MySQL, MongoDB</p>
            <p>✔ webpage designing</p>
        </div>
    </section>
   
    <section id="about">
        
        <h2>About Me</h2> 
        <div class="info-box">
            <p>Hi Guys!,I'm R.RAMPRASATH and I am a college student from saveetha engineering college ,I'm interested about technology, coding, and innovation. This portfolio shows my academic achievements, projects, and skills.</p>
        </div>
    </section>
    
   
    
    <section id="contact">
        <h2>Contact:70923 46544</h2>
        <p>Email: rhramprasath@gmail.com</p>
       
    </section>
    
    
</body>
</html>

```
### style.css
```
body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
    text-align: center;
}

header {
    background: linear-gradient(to right, #1e3c72, #2a5298);
    color: white;
    padding: 1rem;
    text-align: center;
    
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

nav ul li {
    display: inline;
    margin: 0 20px;
}

nav ul li a {
    color: #FFD700;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.2rem;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #ff6347;
}

section {
    padding: 4rem;
}

.info-box {
    background: white;
    padding: 2rem;
    margin: 2rem auto;
    max-width: 800px;
   
    border-radius: 15px;
    transition: transform 0.3s ease-in-out;
}

.info-box:hover {
    transform: scale(1.02);
}

#contact {
    background: #2a5298;
    color: white;
    padding: 3rem;
}

footer {
    background-color: #1e3c72;
    color: white;
    text-align: center;
    padding: 1.5rem;
    margin-top: 2rem;
}

.button {
    display: inline-block;
    padding: 12px 25px;
    background: #ff6347;
    color: white;
    text-decoration: none;
    font-size: 1rem;
    border-radius: 5px;
    transition: background 0.3s;
}

.button:hover {
    background: #FFD700;
    color: #333;
}

```

## OUTPUT
![Screenshot 2025-03-14 222445](https://github.com/user-attachments/assets/f1c5ad72-1369-4e98-86cc-8ef2155a1f69)

![Screenshot 2025-03-14 222455](https://github.com/user-attachments/assets/93a99484-3bfe-4df2-9f05-246323d17bdc)

![Screenshot 2025-03-14 222513](https://github.com/user-attachments/assets/c4cf8b17-88c4-4f6c-9626-8bf16f765428)





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
