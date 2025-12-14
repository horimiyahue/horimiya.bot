<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Navbar -->
    <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <header>
        <div class="hero-content">
            <h1>Hello, I'm [Your Name]</h1>
            <p>Welcome to my portfolio! I am a [Your Role], and I love creating awesome things.</p>
            <a href="#contact" class="cta-button">Get in Touch</a>
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="section">
        <h2>About Me</h2>
        <p>I am a passionate [Your Role] with a strong background in [Technologies you work with].</p>
        <p>I'm constantly learning and improving my skills, and I love collaborating on projects that solve real-world problems.</p>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="section">
        <h2>Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>React</li>
            <li>Node.js</li>
            <!-- Add more skills here -->
        </ul>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="section">
        <h2>My Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>A brief description of the project.</p>
            <a href="#">View Project</a>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>A brief description of the project.</p>
            <a href="#">View Project</a>
        </div>
        <!-- Add more projects here -->
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section">
        <h2>Contact Me</h2>
        <form action="mailto:your.email@example.com" method="post" enctype="text/plain">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Your Name. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>


