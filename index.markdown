---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

<!DOCTYPE html>
layout: home
---
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lim Jing Xiang (Ryan) - Portfolio</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1f1f1f;
            color: #fff;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            padding: 5px 10px;
            border-radius: 3px;
            transition: background-color 0.3s;
        }

        nav ul li a:hover {
            background-color: #555;
        }

        .container {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
            background-color: #333;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }

        .section {
            margin-bottom: 40px;
            padding: 20px;
            background-color: #1f1f1f;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }

        .project {
            margin-bottom: 20px;
            padding: 20px;
            background-color: #333;
            border-radius: 5px;
        }

        .project h3 {
            margin-top: 0;
            color: #fff;
        }

        .project p {
            color: #ccc;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .github-card {
            text-align: center;
            margin-top: 20px;
        }

        .github-card iframe {
            width: 200px;
            height: 100px;
            border: none;
        }

        .cv-link, .project-link {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            color: #fff;
            text-decoration: none;
            background-color: #555;
            border-radius: 3px;
            transition: background-color 0.3s;
        }

        .cv-link:hover, .project-link:hover {
            background-color: #777;
        }
    </style>
</head>

<body>
    <header>
        <h1>Lim Jing Xiang (Ryan) - Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#cv" class="cv-link">CV</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <div class="container">
        <section id="about" class="section">
            <h2>About Me</h2>
            <p>I'm a passionate student of computer science with a focus on game development. My goal is to create immersive and engaging gaming experiences by combining my technical skills with my love for gaming.</p>
        </section>

        <section id="projects" class="section">
            <h2>Projects</h2>
            <div class="project">
                <h3><a href="opengl_triangle_blog.html" class="project-link">OpenGL Triangle</a></h3>
                <p>OpenGL Triangle is a project showcasing the basics of rendering a simple triangle using OpenGL in C++. It's a fundamental step in understanding graphics programming.</p>
                <div class="github-card">
                    <a href="https://github.com/DrakZone/OpenGLTriangle">
                        <img src="https://gh-card.dev/repos/DrakZone/OpenGLTriangle.svg" alt="DrakZone/OpenGLTriangle - GitHub">
                    </a>
                </div>
            </div>
            <div class="project">
                <h3><a href="game_jam_sfml_blog.html" class="project-link">Simple 2D Game in SFML</a></h3>
                <p>This project is a simple 2D game created using SFML. It demonstrates basic game development concepts and showcases my skills in game programming.</p>
                <div class="github-card">
                    <a href="https://github.com/DrakZone/GameJamSFML">
                        <img src="https://gh-card.dev/repos/DrakZone/GameJamSFML.svg" alt="DrakZone/GameJamSFML - GitHub">
                    </a>
                </div>
            </div>
        </section>

        <section id="cv" class="section">
            <h2>Curriculum Vitae</h2>
            <p>You can download my CV below:</p>
            <p><a href="https://github.com/DrakZone/CV/raw/main/your-cv-file-name.pdf" class="cv-link" target="_blank">Download CV</a></p>
        </section>

        <section id="contact" class="section">
            <h2>Contact Me</h2>
            <p>You can reach me at jxryan3683@gmail.com</p>
        </section>
    </div>

    <footer>
        &copy; 2024 Lim Jing Xiang (Ryan) - Portfolio
    </footer>
</body>

</html>



