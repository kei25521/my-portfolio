<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* CSS styles here */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #333;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }
        nav ul li {
            display: inline-block;
            margin-right: 10px;
        }
        nav ul li a {
            text-decoration: none;
            color: #555;
        }
        nav ul li a:hover {
            color: #000;
        }
        .hero {
            background-image: url('hero-bg.jpg');
            background-size: cover;
            padding: 100px 0;
            text-align: center;
            color: #fff;
        }
        .about {
            background-color: #fff;
            padding: 50px 0;
            text-align: center;
            color: #333;
        }
        .about img {
            width: 200px;
            border-radius: 50%;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <!-- HTML content here -->
    <header>
        <div class="container">
            <div class="logo">
                <h1>My Portfolio</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="container">
            <h2>Welcome to My Portfolio</h2>
            <p>Discover my work and projects</p>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>About Me</h2>
            <img src="profile.jpg" alt="Profile Picture">
            <p>Hi, I'm a web developer with a passion for creating beautiful and functional websites.</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 My Portfolio. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
