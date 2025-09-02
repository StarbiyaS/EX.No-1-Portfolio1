# Ex01 Portfolio
## Date: 02/09/2025

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
    <title>Starbiya S- Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- Navigation -->
    <header>
        <div class="container">
            <div class="logo">
                <h1>Starbiya S</h1>
            </div>
            <input type="checkbox" id="nav-toggle" class="nav-toggle">
            <label for="nav-toggle" class="nav-toggle-label">
                <span></span>
            </label>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <div class="hero-content">
                <div class="hero-text">
                    <h1>Hi, I'm Starbiya S</h1>
                    <p>A passionate developer creating beautiful and functional digital experiences.</p>
                    <div class="hero-buttons">
                        <a href="#contact" class="btn btn-primary">Get in touch</a>
                        <a href="#projects" class="btn btn-secondary">View my work</a>
                    </div>
                </div>
                
            </div>
        </div>
    </section>
    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <div class="section-header">
                <h2>About Me</h2>
                <p>Get to know more about my background and experience</p>
            </div>
            <div class="about-cards">
                <div class="card">
                    <div class="card-header">
                        <h3>About Me </h3>
                        <p class="subtitle">A brief introduction</p>
                    </div>
                    <div class="card-content">
                        <p>
                            I am a Computer Science student with a strong foundation in Artificial Intelligence, Machine Learning, and Data Analysis. I have gained hands-on experience through academic projects and internships, where I worked on real-world problems such as stock market prediction and health data analysis. I am passionate about building efficient, scalable solutions and continuously learning emerging technologies.
                        </p>
                        
                    </div>
                </div>
                <div class="card">
                    <div class="card-header">
                        <h3>Education & Experience</h3>
                       
                    </div>
                    <div class="card-content">
                        <div class="experience-item">
                            <h4>B.E CSE</h4>
                            <p class="date">Saveetha Engineering College 2023-2027</p>
                        </div>
                        <div class="experience-item">
                            <h4>Artificial Intelligence </h4>
                            <p class="date">Trios Technologies, 06/2024-07/2024</p>
                           
                            <p>
                                As an intern,gained knowledge of AI fundamentals and applied Machine Learning algorithms in project development.
                            </p>
                        </div>
                        <div class="experience-item">
                            <h4>Web Design Intern</h4>
                            
                            <p>
                                Assisted in designing and developing websites, learned industry best practices, 
                                and contributed to client projects.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="container">
            <div class="section-header">
                <h2>My Skills</h2>
                <p>Expertise and technologies I work with</p>
            </div>
            <div class="skills-cards">
                <div class="skill-card">
                    <div class="skill-icon">
                        <i class="fas fa-code"></i>
                    </div>
                    <h3>C Programming</h3>
                    <p>Developing efficient and optimized programs using C, focusing on problem-solving, algorithm design, and memory management for system-level and console-based applications.</p>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">
                        <i class="fas fa-database"></i>
                    </div>
                    <h3>Python Programming</h3>
                    <p> Building versatile applications using Python, including data analysis, automation scripts, and backend development with emphasis on clean, efficient, and maintainable code.</p>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">
                        <i class="fas fa-palette"></i>
                    </div>
                    <h3>Machine Learning</h3>
                    <p>Developing and deploying machine learning models to analyze data, make predictions, and solve real-world problems using Python libraries like scikit-learn, TensorFlow, and PyTorch.</p>
                </div>
                
                  
                
                <div class="skill-card">
                    <div class="skill-icon">
                        <i class="fas fa-lightbulb"></i>
                    </div>
                    <h3>Creative Problem Solving</h3>
                    <p>Finding innovative solutions to complex technical and design challenges.</p>
                </div>
            </div>
        </div>
    </section>
    <!-- Projects Section -->
    <section id="projects" class="projects">
        <div class="container">
            <div class="section-header">
                <h2>My Projects</h2>
                <p>A selection of my recent work and personal projects</p>
            </div>
            <div class="projects-grid">
                <div class="project-card">
                    
                    <div class="project-content">
                        <h3>Stock Market Prediction</h3>
                        <p>
                            This project focuses on building predictive models to forecast stock prices by analyzing historical market data. Leveraging machine learning algorithms and advanced data analysis techniques, the system aims to identify trends and patterns, helping investors make informed decisions and optimize their trading strategies
                           </p>
                        <div class="project-tags">
                            <span>Jupyter Notebook</span>
                            <span>Kaggle</span>
                            <span>Google Collab</span>
                            <span>Anaconda Navigater</span>
                        </div>
                        <div class="project-links">
                            <a href="#" class="btn btn-small btn-secondary">
                                <i class="fab fa-github"></i> Code
                            </a>
                            <a href="#" class="btn btn-small btn-primary">
                                <i class="fas fa-external-link-alt"></i> Live Demo
                            </a>
                        </div>
                    </div>
                </div>
                <div class="project-card">
                    
                    <div class="project-content">
                        <h3>Heart Disease Prediction</h3>
                        <p>
                            This project involves building a machine learning model to predict the risk of heart disease based on patient medical data. By analyzing key health indicators, the model enables early detection of potential heart issues, helping healthcare providers and patients take timely preventive measures to reduce risks and improve overall health outcomes.
                            </p>
                        <div class="project-tags">
                            <span>Jupyter Notebook</span>
                            <span>Kaggle</span>
                            <span>Google Collab</span>
                            <span>Anaconda Navigater</span>
                            
                        </div>
                        <div class="project-links">
                            <a href="#" class="btn btn-small btn-secondary">
                                <i class="fab fa-github"></i> Code
                            </a>
                            <a href="#" class="btn btn-small btn-primary">
                                <i class="fas fa-external-link-alt"></i> Live Demo
                            </a>
                        </div>
                    </div>
                </div>
                <div class="project-card">
                    
                    <div class="project-content">
                        <h3>Portfolio Website</h3>
                        <p>
                            This is a modern personal portfolio website designed to showcase my projects, technical skills, and professional experience. It provides a clear and engaging way for visitors to explore my work, learn about my expertise, and understand my contributions in various projects, all presented with a clean and contemporary design
                        </p>
                        <div class="project-tags">
                            <span>HTML/CSS</span>
                            <span>JavaScript</span>
                            <span>GSAP</span>
                            <span>Responsive Design</span>
                        </div>
                        <div class="project-links">
                            <a href="#" class="btn btn-small btn-secondary">
                                <i class="fab fa-github"></i> Code
                            </a>
                            <a href="#" class="btn btn-small btn-primary">
                                <i class="fas fa-external-link-alt"></i> Live Demo
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <div class="section-header">
                <h2>Get In Touch</h2>
                <p>Have a project in mind or want to collaborate? Feel free to reach out!</p>
            </div>
            <div class="contact-container">
                <div class="contact-info">
                    <div class="contact-card">
                        <div class="contact-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <h3>Email</h3>
                        <p><a href="mailto:starbiya@example.com">starbinstarbiya@gmail.com</a></p>
                    </div>
                    <div class="contact-card">
                        <div class="contact-icon">
                            <i class="fas fa-phone"></i>
                        </div>
                        <h3>Phone</h3>
                        <p><a href="tel:+1234567890"></a></p>
                    </div>
                    <div class="contact-card">
                        <div class="contact-icon">
                            <i class="fas fa-map-marker-alt"></i>
                        </div>
                        <h3>Location</h3>
                        <p>Chennai</p>
                    </div>
                </div>
                <div class="contact-form-container">
                    <form class="contact-form">
                        <h3>Send Me a Message</h3>
                        <p>Fill out the form below and I'll get back to you as soon as possible.</p>
                        <div class="form-group">
                            <label for="name">Name</label>
                            <input type="text" id="name" name="name" placeholder="Your name" required>
                        </div>
                        <div class="form-group">
                            <label for="email">Email</label>
                            <input type="email" id="email" name="email" placeholder="Your email" required>
                        </div>
                        <div class="form-group">
                            <label for="subject">Subject</label>
                            <input type="text" id="subject" name="subject" placeholder="Subject" required>
                        </div>
                        <div class="form-group">
                            <label for="message">Message</label>
                            <textarea id="message" name="message" placeholder="Your message" rows="4" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary btn-full">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>
    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="copyright">
                    <p>&copy; <span id="current-year">2025</span> Starbiya. All rights reserved.</p>
                </div>
                <div class="social-links">
                    <a href="#" aria-label="Github"><i class="fab fa-github"></i></a>
                    <a href="#" aria-label="LinkedIn"><i class="fab fa-linkedin"></i></a>
                    <a href="#" aria-label="Twitter"><i class="fab fa-twitter"></i></a>
                    <a href="#" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
                    <a href="#" aria-label="Facebook"><i class="fab fa-facebook"></i></a>
                </div>
            </div>
        </div>
    </footer>
    <script>
        // Simple script to update the year in the footer
        document.getElementById('current-year').textContent = new Date().getFullYear();
    </script>
</body>
</html>
```

## style.css:
```
/* Variables */
:root {
    --primary-color: #7c3aed;
    --primary-color-light: #8b5cf6;
    --secondary-color: #f3f4f6;
    --text-color: #1f2937;
    --text-color-light: #6b7280;
    --background-color: #ffffff;
    --background-alt: #f9fafb;
    --card-bg-color: #ffffff;
    --border-color: #e5e7eb;
    --shadow-sm: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
    --shadow-md: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
    --shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
    --border-radius: 0.5rem;
    --border-radius-sm: 0.25rem;
    --transition: all 0.3s ease;
    --max-width: 1200px;
    --header-height: 64px;
  }
  
  /* Reset & Base Styles */
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  html {
    scroll-behavior: smooth;
  }
  
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: var(--text-color);
    line-height: 1.6;
    background-color: var(--background-color);
    min-height: 100vh;
  }
  
  img {
    max-width: 100%;
    height: auto;
    display: block;
  }
  
  a {
    text-decoration: none;
    color: inherit;
    transition: var(--transition);
  }
  
  ul {
    list-style: none;
  }
  
  .container {
    max-width: var(--max-width);
    margin: 0 auto;
    padding: 0 1.5rem;
    width: 100%;
  }
  
  section {
    padding: 5rem 0;
  }
  
  .section-header {
    text-align: center;
    margin-bottom: 3rem;
  }
  
  .section-header h2 {
    font-size: 2.5rem;
    margin-bottom: 0.5rem;
    position: relative;
    display: inline-block;
  }
  
  .section-header p {
    color: var(--text-color-light);
    max-width: 600px;
    margin: 0 auto;
  }
  
  /* Buttons */
  .btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: 0.75rem 1.5rem;
    border-radius: var(--border-radius);
    font-weight: 600;
    transition: var(--transition);
    cursor: pointer;
    border: none;
    outline: none;
  }
  
  .btn-small {
    padding: 0.5rem 1rem;
    font-size: 0.875rem;
  }
  
  .btn-primary {
    background-color: var(--primary-color);
    color: white;
  }
  
  .btn-primary:hover {
    background-color: var(--primary-color-light);
  }
  
  .btn-secondary {
    background-color: var(--secondary-color);
    color: var(--text-color);
  }
  
  .btn-secondary:hover {
    background-color: #e5e7eb;
  }
  
  .btn-full {
    width: 100%;
  }
  
  /* Card Styles */
  .card {
    background-color: var(--card-bg-color);
    border-radius: var(--border-radius);
    box-shadow: var(--shadow-md);
    padding: 1.5rem;
    transition: var(--transition);
  }
  
  .card:hover {
    box-shadow: var(--shadow-lg);
    transform: translateY(-5px);
  }
  
  .card-header {
    margin-bottom: 1rem;
  }
  
  .card-header h3 {
    margin-bottom: 0.5rem;
    font-size: 1.25rem;
  }
  
  .subtitle {
    color: var(--text-color-light);
    font-size: 0.875rem;
  }
  
  /* Header / Navigation */
  header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: rgba(255, 255, 255, 0.95);
    backdrop-filter: blur(10px);
    z-index: 1000;
    box-shadow: var(--shadow-sm);
    height: var(--header-height);
  }
  
  header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 100%;
  }
  
  .logo h1 {
    font-size: 1.5rem;
    font-weight: 700;
    color: var(--text-color);
  }
  
  nav ul {
    display: flex;
    gap: 1.5rem;
  }
  
  nav a {
    font-weight: 500;
    padding: 0.5rem 0;
    position: relative;
  }
  
  nav a:hover {
    color: var(--primary-color);
  }
  
  nav a::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 0;
    height: 2px;
    background-color: var(--primary-color);
    transition: var(--transition);
  }
  
  nav a:hover::after {
    width: 100%;
  }
  
  .nav-toggle {
    display: none;
  }
  
  .nav-toggle-label {
    display: none;
    cursor: pointer;
  }
  
  /* Hero Section */
  .hero {
    padding: calc(5rem + var(--header-height)) 0 5rem;
    background-color: var(--background-color);
  }
  
  .hero-content {
    display: flex;
    align-items: center;
    gap: 3rem;
  }
  
  .hero-text {
    flex: 1;
  }
  
  .hero-text h1 {
    font-size: 3rem;
    line-height: 1.2;
    margin-bottom: 1rem;
  }
  
  .hero-text p {
    font-size: 1.125rem;
    color: var(--text-color-light);
    margin-bottom: 2rem;
    max-width: 600px;
  }
  
  .hero-buttons {
    display: flex;
    gap: 1rem;
  }
  
  .hero-image {
    flex: 1;
    display: flex;
    justify-content: center;
  }
  
  .profile-image {
    width: 280px;
    height: 280px;
    border-radius: 50%;
    overflow: hidden;
    border: 4px solid var(--background-color);
    box-shadow: var(--shadow-lg);
  }
  
  /* About Section */
  .about {
    background-color: var(--background-alt);
  }
  
  .about-cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
  }
  
  .experience-item {
    margin-bottom: 1.5rem;
  }
  
  .experience-item h4 {
    font-size: 1.125rem;
    margin-bottom: 0.25rem;
  }
  
  .date {
    font-size: 0.875rem;
    color: var(--text-color-light);
    margin-bottom: 0.5rem;
  }
  
  /* Skills Section */
  .skills-cards {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 1.5rem;
  }
  
  .skill-card {
    background-color: var(--card-bg-color);
    border-radius: var(--border-radius);
    padding: 1.5rem;
    text-align: center;
    box-shadow: var(--shadow-md);
    transition: var(--transition);
  }
  
  .skill-card:hover {
    box-shadow: var(--shadow-lg);
    transform: translateY(-5px);
  }
  
  .skill-icon {
    font-size: 2.5rem;
    color: var(--primary-color);
    margin-bottom: 1rem;
  }
  
  .skill-card h3 {
    margin-bottom: 0.75rem;
    font-size: 1.25rem;
  }
  
  .skill-card p {
    color: var(--text-color-light);
    font-size: 0.95rem;
  }
  
  /* Projects Section */
  .projects {
    background-color: var(--background-alt);
  }
  
  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 1rem;
  }
  
  .project-card {
    background-color: var(--card-bg-color);
    border-radius: var(--border-radius);
    overflow: hidden;
    box-shadow: var(--shadow-md);
    transition: var(--transition);
  }
  
  .project-card:hover {
    box-shadow: var(--shadow-lg);
    transform: translateY(-5px);
  }
  
  .project-image {
    height: 200px;
    overflow: hidden;
  }
  
  .project-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.5s ease;
  }
  
  .project-card:hover .project-image img {
    transform: scale(1.05);
  }
  
  .project-content {
    padding: 1.5rem;
  }
  
  .project-content h3 {
    margin-bottom: 0.75rem;
    font-size: 1.25rem;
  }
  
  .project-content p {
    color: var(--text-color-light);
    margin-bottom: 1rem;
    font-size: 0.95rem;
  }
  
  .project-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin-bottom: 1.5rem;
  }
  
  .project-tags span {
    background-color: rgba(124, 58, 237, 0.1);
    color: var(--primary-color);
    padding: 0.25rem 0.75rem;
    border-radius: 999px;
    font-size: 0.75rem;
    font-weight: 500;
  }
  
  .project-links {
    display: flex;
    justify-content: space-between;
  }
  
  /* Contact Section */
  .contact-container {
    display: grid;
    grid-template-columns: 1fr 2fr;
    gap: 2rem;
  }
  
  .contact-info {
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
  }
  
  .contact-card {
    background-color: var(--card-bg-color);
    border-radius: var(--border-radius);
    padding: 1.5rem;
    box-shadow: var(--shadow-md);
    transition: var(--transition);
  }
  
  .contact-card:hover {
    box-shadow: var(--shadow-lg);
    transform: translateY(-5px);
  }
  
  .contact-icon {
    font-size: 1.5rem;
    color: var(--primary-color);
    margin-bottom: 0.75rem;
  }
  
  .contact-card h3 {
    margin-bottom: 0.5rem;
    font-size: 1.125rem;
  }
  
  .contact-card a:hover {
    color: var(--primary-color);
  }
  
  .contact-form-container {
    background-color: var(--card-bg-color);
    border-radius: var(--border-radius);
    box-shadow: var(--shadow-md);
    padding: 2rem;
  }
  
  .contact-form h3 {
    margin-bottom: 0.5rem;
    font-size: 1.25rem;
  }
  
  .contact-form > p {
    color: var(--text-color-light);
    margin-bottom: 1.5rem;
    font-size: 0.95rem;
  }
  
  .form-group {
    margin-bottom: 1.25rem;
  }
  
  .form-group label {
    display: block;
    margin-bottom: 0.5rem;
    font-weight: 500;
  }
  
  .form-group input,
  .form-group textarea {
    width: 100%;
    padding: 0.75rem;
    border: 1px solid var(--border-color);
    border-radius: var(--border-radius-sm);
    font-family: inherit;
    font-size: 1rem;
    transition: var(--transition);
  }
  
  .form-group input:focus,
  .form-group textarea:focus {
    outline: none;
    border-color: var(--primary-color);
    box-shadow: 0 0 0 2px rgba(124, 58, 237, 0.2);
  }
  
  /* Footer */
  footer {
    background-color: var(--background-color);
    border-top: 1px solid var(--border-color);
    padding: 2rem 0;
  }
  
  .footer-content {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  
  .copyright {
    font-size: 0.875rem;
    color: var(--text-color-light);
  }
  
  .social-links {
    display: flex;
    gap: 1rem;
  }
  
  .social-links a {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 36px;
    height: 36px;
    border-radius: 50%;
    background-color: var(--secondary-color);
    color: var(--text-color);
    transition: var(--transition);
  }
  
  .social-links a:hover {
    background-color: var(--primary-color);
    color: white;
    transform: translateY(-3px);
  }
  
  /* Mobile Menu */
  @media (max-width: 768px) {
    .nav-toggle-label {
      display: block;
      position: relative;
      height: 24px;
      width: 30px;
    }
  
    .nav-toggle-label span,
    .nav-toggle-label span::before,
    .nav-toggle-label span::after {
      display: block;
      position: absolute;
      height: 3px;
      width: 100%;
      border-radius: 3px;
      background-color: var(--text-color);
      transition: all 0.3s ease;
    }
  
    .nav-toggle-label span {
      top: 50%;
      transform: translateY(-50%);
    }
  
    .nav-toggle-label span::before {
      content: '';
      top: -8px;
    }
  
    .nav-toggle-label span::after {
      content: '';
      bottom: -8px;
    }
  
    nav {
      position: absolute;
      top: var(--header-height);
      left: 0;
      width: 100%;
      background-color: var(--background-color);
      box-shadow: var(--shadow-md);
      padding: 1.5rem;
      transform: translateY(-100%);
      opacity: 0;
      transition: all 0.3s ease;
      pointer-events: none;
    }
  
    .nav-toggle:checked ~ nav {
      transform: translateY(0);
      opacity: 1;
      pointer-events: auto;
    }
  
    .nav-toggle:checked ~ .nav-toggle-label span {
      background-color: transparent;
    }
  
    .nav-toggle:checked ~ .nav-toggle-label span::before {
      transform: rotate(45deg) translate(5px, 5px);
    }
  
    .nav-toggle:checked ~ .nav-toggle-label span::after {
      transform: rotate(-45deg) translate(6px, -5px);
    }
  
    nav ul {
      flex-direction: column;
      gap: 1rem;
    }
  
    nav a {
      display: block;
      padding: 0.5rem 0;
    }
  }
  
  /* Responsive Styles */
  @media (max-width: 992px) {
    .contact-container {
      grid-template-columns: 1fr;
    }
  
    .contact-info {
      flex-direction: row;
      flex-wrap: wrap;
    }
  
    .contact-card {
      flex: 1;
      min-width: 200px;
    }
  }
  
  @media (max-width: 768px) {
    .hero-content {
      flex-direction: column-reverse;
      text-align: center;
      gap: 2rem;
    }
  
    .hero-text h1 {
      font-size: 2.5rem;
    }
  
    .hero-buttons {
      justify-content: center;
    }
  
    .section-header h2 {
      font-size: 2rem;
    }
    
    .profile-image {
      width: 220px;
      height: 220px;
    }
  }
  
  @media (max-width: 576px) {
    .about-cards, 
    .skills-cards, 
    .projects-grid {
      grid-template-columns: 1fr;
    }
  
    .contact-info {
      flex-direction: column;
    }
  
    .footer-content {
      flex-direction: column;
      gap: 1rem;
    }
  
    .hero-text h1 {
      font-size: 2rem;
    }
  
    .section-header h2 {
      font-size: 1.75rem;
    }
  }
  
  /* Utility Classes */
  .text-center {
    text-align: center;
  }
  
  .mb-1 {
    margin-bottom: 0.5rem;
  }
  
  .mb-2 {
    margin-bottom: 1rem;
  }
  
  .mb-3 {
    margin-bottom: 1.5rem;
  }
  
  .mb-4 {
    margin-bottom: 2rem;
  }
```

## OUTPUT:
<img width="1839" height="663" alt="Screenshot 2025-09-01 205211" src="https://github.com/user-attachments/assets/dc756972-ff95-40f9-9a77-a681db828a36" />

<img width="1851" height="972" alt="Screenshot 2025-09-01 205228" src="https://github.com/user-attachments/assets/0e4126e6-0475-423b-a64c-9f9e6eb19d7f" />

<img width="1848" height="975" alt="Screenshot 2025-09-01 205250" src="https://github.com/user-attachments/assets/9f83b4b6-0d77-40dc-8003-f5b317bdea50" />

<img width="1848" height="976" alt="Screenshot 2025-09-01 205315" src="https://github.com/user-attachments/assets/10cff9cb-5ea8-4602-b0a6-7e2aeea1d0fd" />


<img width="1847" height="974" alt="Screenshot 2025-09-01 205402" src="https://github.com/user-attachments/assets/57a90848-0055-4fd8-9727-6716694bf9f1" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
