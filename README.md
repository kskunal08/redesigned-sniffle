<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Kunal K</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #0a192f;
            color: #ffffff;
            overflow-x: hidden;
        }
        header {
            background: linear-gradient(135deg, #ff7eb3, #8b5cf6, #3b82f6);
            color: #fff;
            text-align: center;
            padding: 4rem 0;
            animation: slideIn 1.5s ease-in-out;
        }
        @keyframes slideIn {
            from { opacity: 0; transform: translateY(-50px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 2rem 1rem;
            box-shadow: 0 0 50px #3b82f6;
            border-radius: 20px;
            background-color: #112240;
            transition: box-shadow 0.5s ease-in-out;
        }
        .container:hover {
            box-shadow: 0 0 80px #60a5fa;
        }
        .profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid #3b82f6;
            margin: 0 auto 2rem;
            display: block;
            box-shadow: 0 0 25px #60a5fa;
        }
        .card {
            background-color: #112240;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.9);
            border-radius: 20px;
            padding: 2rem;
            margin: 1.5rem 0;
            transition: transform 0.4s ease-in-out, box-shadow 0.4s ease-in-out;
            border-left: 6px solid #3b82f6;
        }
        .card:hover {
            transform: scale(1.1) rotate(-1deg);
            box-shadow: 0 15px 50px rgba(0, 0, 0, 1);
        }
        .projects img {
            width: 100%;
            border-radius: 12px;
            transition: transform 0.5s ease-in-out;
        }
        .projects img:hover {
            transform: scale(1.2) rotate(-5deg);
        }
        footer {
            background: linear-gradient(135deg, #ff7eb3, #8b5cf6, #3b82f6);
            color: #fff;
            text-align: center;
            padding: 1rem 0;
        }
        a {
            color: #60a5fa;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease-in-out;
        }
        a:hover {
            color: #93c5fd;
        }
        .nav-links {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-top: 1rem;
        }
        .nav-links a {
            color: #fff;
            background-color: #3b82f6;
            padding: 0.5rem 1.5rem;
            border-radius: 30px;
            transition: background 0.3s ease-in-out, transform 0.3s;
        }
        .nav-links a:hover {
            background-color: #60a5fa;
            transform: scale(1.2) rotate(5deg);
        }
        .animated-button {
            display: inline-block;
            padding: 0.7rem 2rem;
            background: #3b82f6;
            color: #0a192f;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s ease-in-out, transform 0.3s;
            animation: pulse 1.5s infinite alternate;
        }
        .animated-button:hover {
            background: #60a5fa;
            transform: translateY(-5px) scale(1.1);
        }
        @keyframes pulse {
            from { transform: scale(1); }
            to { transform: scale(1.15); }
        }
    </style>
</head>
<body>
    <header>
        <h1>Kunal K</h1>
        <p>Web Developer | App Developer | Arduino IDE Expert | EV Innovator</p>
        <div class="nav-links">
            <a href="#about">About Me</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </div>
    </header>

    <div class="container">
        <img src="IMG-20241128-WA0017.JPG" alt="Profile Picture" class="profile-pic">
        <div id="about" class="card">
            <h2>About Me</h2>
            <p>I'm a passionate developer skilled in Web Development, App Development, Arduino IDE, and EV Development.</p>
            <a href="#projects" class="animated-button">See My Projects</a>
        </div>

        <div id="projects" class="card projects">
            <h2>Projects</h2>
            <ul>
                <li>Alumni Portal Web Project</li>
                <li>Maintenance App for College Project</li>
                <li>Arduino IDE Automation Project</li>
                <li>Electric Vehicle Development from Scratch</li>
                <li>Responsive Web Portfolio Design</li>
            </ul>
        </div>

        <div id="contact" class="card">
            <h2>Contact</h2>
            <p>Connect with me on <a href="https://www.linkedin.com/in/krishna-kunal-68656b341">LinkedIn</a> or view my code on <a href="https://github.com/kskunal08">GitHub</a>.</p>
        </div>
    </div>

    <footer>
        &copy; 2027 Kunal K - All Rights Reserved
    </footer>
</body>
</html>
