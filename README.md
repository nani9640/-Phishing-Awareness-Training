# -Phishing-Awareness-Training


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio & Phishing Awareness Training</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 15px;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        section {
            padding: 20px;
            display: none; /* Hide all sections by default */
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            position: relative;
            width: 100%;
            bottom: 0;
        }

        #portfolio, #phishing {
            display: block; /* Show the portfolio section by default */
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio & Phishing Awareness Training</h1>
        <nav>
            <ul>
                <li><a href="#" onclick="showSection('portfolio')">Portfolio</a></li>
                <li><a href="#" onclick="showSection('phishing')">Phishing Awareness</a></li>
            </ul>
        </nav>
    </header>

    <section id="portfolio">
        <h2>My Portfolio</h2>
        <p>Hello! I am a passionate developer with skills in HTML, CSS, and JavaScript.</p>

        <h3>Projects</h3>
        <ul>
            <li>Project 1: <a href="#">Description and Link</a></li>
            <li>Project 2: <a href="#">Description and Link</a></li>
            <li>Project 3: <a href="#">Description and Link</a></li>
        </ul>

        <h3>Resume</h3>
        <p><a href="resume.pdf" target="_blank">Download My Resume</a></p>

        <h3>Contact Me</h3>
        <form id="contactForm">
            <label for="name">Name:</label>
            <input type="text" id="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" required>
            <label for="message">Message:</label>
            <textarea id="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <section id="phishing">
        <h2>Phishing Awareness Training</h2>
        <h3>What is Phishing?</h3>
        <p>Phishing is a fraudulent attempt to obtain sensitive information by disguising as a trustworthy entity in electronic communication.</p>

        <h3>Types of Phishing</h3>
        <ul>
            <li>Email Phishing</li>
            <li>Spear Phishing</li>
            <li>Whaling</li>
            <li>Vishing</li>
            <li>Smishing</li>
        </ul>

        <h3>How to Recognize Phishing Attempts</h3>
        <p>Look for the following signs:</p>
        <ul>
            <li>Generic greetings (e.g., "Dear Customer")</li>
            <li>Urgent language or threats</li>
            <li>Suspicious links or attachments</li>
            <li>Misspellings and poor grammar</li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2023 My Portfolio</p>
    </footer>

    <script>
        document.getElementById("contactForm").addEventListener("submit", function(event) {
            event.preventDefault();
            alert("Thank you for your message!");
            this.reset();
        });

        function showSection(sectionId) {
            // Hide all sections
            document.getElementById("portfolio").style.display = "none";
            document.getElementById("phishing").style.display = "none";

            // Show the selected section
            document.get
