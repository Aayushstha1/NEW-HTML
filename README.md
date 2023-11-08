<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OUR OFFICAL SITE </title>
    <style>
        /* Reset some default styles */
        body, h1, h2, h3, p, ul, li {
            margin: 0;
            padding: 0;
        }

        /* Apply basic styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            font-size: 36px;
        }

        nav ul {
            list-style: none;
        }

        nav li {
            display: inline;
            margin-right: 20px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
        }

        .hero {
            background-image: url('your-hero-image.jpg');
            background-size: cover;
            background-position: center;
            text-align: center;
            padding: 100px 0;
            color: #fff;
        }

        .hero h2 {
            font-size: 36px;
        }

        .cta-button {
            display: inline-block;
            background-color: #333;
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
        }

        .cta-button:hover {
            background-color: #555;
        }

        .content {
            padding: 40px;
        }

        .content h2 {
            margin-bottom: 20px;
        }

        .services {
            padding: 40px;
            background-color: #fff;
        }

        .services h2 {
            margin-bottom: 20px;
        }

        .service {
            margin-bottom: 30px;
            border: 1px solid #ccc;
            padding: 20px;
            border-radius: 5px;
        }

        .contact {
            padding: 40px;
            background-color: #fff;
        }

        .contact h2 {
            margin-bottom: 20px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <h1>OUR OFFICAL SITE</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h2>Welcome Our Website</h2>
        <p>Discover amazing content and services.</p>
        <a href="#services" class="cta-button">Learn More</a>
    </section>

    <section class="content" id="about">
        <h2>About Us</h2>
        <p> It is just for Pratice </p>
    </section>

    <section class="services" id="services">
        <h2>Our Services</h2>
        <div class="service">
            <h3>Service 1</h3>
            <p>Description of Service 1.</p>
        </div>
        <div class="service">
            <h3>Service 2</h3>
            <p>Description of Service 2.</p>
        </div>
        <div class="service">
            <h3>Service 3</h3>
            <p>Description of Service 3.</p>
        </div>
    </section>

    <section class="contact" id="contact">
        <h2>Contact Us</h2>
        <p>If u have any problem then Contact us.</p>
        <a href="mailto:contact@example.com" class="cta-button">Contact Now</a>
    </section>

    <footer>
        <p>&copy; 2023 our offical site.</p>
    </footer>
</body>
</html>
