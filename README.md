# my-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* Reset CSS */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }
        
        .container {
            width: 90%;
            margin: auto;
            overflow: hidden;
        }

        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
        }

        header .logo {
            float: left;
        }

        header nav {
            float: right;
        }

        header nav a {
            color: #fff;
            text-decoration: none;
            padding: 0.5rem 1rem;
        }

        header nav a:hover {
            background: #555;
        }

        .hero {
            background: #f4f4f4;
            padding: 2rem 0;
            text-align: center;
        }

        .about,
        .portfolio,
        .contact {
            padding: 2rem 0;
        }

        .about img {
            max-width: 100%;
            height: auto;
        }

        .portfolio-item {
            float: left;
            width: 30%;
            margin: 1.66%;
            background: #f4f4f4;
            padding: 1rem;
            text-align: center;
        }

        .portfolio-item img {
            max-width: 100%;
            height: auto;
        }

        .portfolio-item h3 {
            margin-top: 1rem;
        }

        .footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            clear: both;
        }

        /* Media Queries */
        @media (max-width: 600px) {
            header .logo, header nav {
                float: none;
                text-align: center;
            }

            .portfolio-item {
                width: 100%;
                margin: 0 0 1rem 0;
            }
        }

        @media (min-width: 601px) and (max-width: 1024px) {
            .portfolio-item {
                width: 45%;
                margin: 2.5%;
            }
        }
    </style>
</head>
<body>
    <header class="container">
        <div class="logo">
            <h1>My Portfolio</h1>
        </div>
        <nav>
            <a href="#about">About</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h2>Welcome to My Portfolio</h2>
        <p>Discover my work and projects</p>
    </section>

    <section id="about" class="about container">
        <h2>About Me</h2>
        <p>Hi, I'm a web developer with a passion for creating beautiful and functional websites.</p>
    </section>

    <section id="portfolio" class="portfolio container">
        <h2>My Work</h2>
        <div class="portfolio-item">
            <img src="https://via.placeholder.com/150" alt="Portfolio Item 1">
            <h3>Project 1</h3>
            <p>Website Design</p>
        </div>
        <div class="portfolio-item">
            <img src="https://via.placeholder.com/150" alt="Portfolio Item 2">
            <h3>Project 2</h3>
            <p>Logo Design</p>
        </div>
        <div class="portfolio-item">
            <img src="https://via.placeholder.com/150" alt="Portfolio Item 3">
            <h3>Project 3</h3>
            <p>Mobile App UI</p>
        </div>
        <div class="portfolio-item">
            <img src="https://via.placeholder.com/150" alt="Portfolio Item 4">
            <h3>Project 4</h3>
            <p>Ad Banner Design</p>
        </div>
        <div class="portfolio-item">
            <img src="https://via.placeholder.com/150" alt="Portfolio Item 5">
            <h3>Project 5</h3>
            <p>Photo Editing</p>
        </div>
        <div class="portfolio-item">
            <img src="https://via.placeholder.com/150" alt="Portfolio Item 6">
            <h3>Project 6</h3>
            <p>Illustration</p>
        </div>
    </section>

    <section id="contact" class="contact container">
        <h2>Contact Me</h2>
        <p>You can reach me at <a href="mailto:example@example.com">example@example.com</a>.</p>
    </section>

    <footer class="footer">
        <p>Follow me on social media</p>
        <a href="#">Twitter</a> | <a href="#">LinkedIn</a> | <a href="#">GitHub</a>
    </footer>
</body>
</html>
