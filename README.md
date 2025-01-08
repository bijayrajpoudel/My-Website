<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Personal website of Bijay Raj Poudel, an IT student and beginner in web development with an interest in digital marketing.">
    <title>Bijay Raj Poudel - IT Student & Beginner Developer</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            line-height: 1.6;
            background: #f9f9f9;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #ff6b6b, #ffd56b);
            color: white;
            padding: 40px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 3rem;
            margin: 0;
        }

        header p {
            font-size: 1.5rem;
            margin: 10px 0;
        }

        nav {
            background: #222;
            color: #fff;
            padding: 15px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav a {
            color: #ffd56b;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.2rem;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 40px 20px;
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }

        h2 {
            text-align: center;
            color: #ff6b6b;
            margin-bottom: 20px;
        }

        .skills ul {
            list-style-type: none;
            padding: 0;
        }

        .skills li {
            background: #ffd56b;
            margin: 10px 0;
            padding: 10px;
            border-radius: 5px;
            color: #222;
        }

        .portfolio {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .portfolio-item {
            background: #fff;
            border: 1px solid #ddd;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }

        .portfolio-item:hover {
            transform: translateY(-5px);
        }

        footer {
            background: #222;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        footer a {
            color: #ffd56b;
            text-decoration: none;
            font-weight: bold;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bijay Raj Poudel</h1>
        <p>IT Student | Beginner Developer & Digital Marketing Enthusiast</p>
    </header>

    <nav>
        <a href="#about">About Me</a>
        <a href="#skills">Skills</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about" class="about">
        <h2>About Me</h2>
        <p>Hi, I'm Bijay Raj Poudel, an IT student from Nepal with a strong enthusiasm for learning and exploring web development and digital marketing. As a beginner, I am focused on building foundational skills and working on small projects to enhance my understanding of the field. I'm excited to grow and contribute to meaningful projects in the future.</p>
    </section>

    <section id="skills" class="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML & CSS - Building responsive and visually appealing web pages</li>
            <li>JavaScript (Beginner) - Interactive web functionality</li>
            <li>Digital Marketing - Basic knowledge of SEO and social media strategies</li>
        </ul>
    </section>

    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="portfolio">
            <div class="portfolio-item">
                <h3>Simple Portfolio Website</h3>
                <p>A basic personal portfolio website designed to showcase my projects and skills.</p>
            </div>
            <div class="portfolio-item">
                <h3>Basic Landing Page</h3>
                <p>A responsive landing page created for a fictional business using HTML and CSS.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contact</h2>
        <p>Feel free to reach out to me for collaboration or inquiries:</p>
        <p><strong>WhatsApp:</strong> <a href="https://wa.me/9824182346">9824182346</a></p>
        <p><strong>Email:</strong> <a href="mailto:poudelbijayraj500@gmail.com">poudelbijayraj500@gmail.com</a></p>
    </section>

    <footer>
        <p>&copy; 2025 Bijay Raj Poudel. All rights reserved. | Designed by Bijay</p>
    </footer>
</body>
</html>
