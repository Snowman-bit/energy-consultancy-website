<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Energy Consultancy Services</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background: #0b8457;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            background: #034732;
            color: white;
            padding: 0.5rem 0;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 2rem;
        }
        footer {
            background: #034732;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1rem;
        }
        .service {
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 1rem;
            text-align: center;
            background: #f9f9f9;
        }
        .contact-form {
            max-width: 500px;
            margin: 0 auto;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            margin-bottom: 1rem;
            padding: 0.5rem;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .contact-form button {
            background: #0b8457;
            color: white;
            border: none;
            padding: 0.7rem 1rem;
            cursor: pointer;
            border-radius: 5px;
        }
        .contact-form button:hover {
            background: #034732;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Your Energy Consultancy</h1>
        <p>Recharge Metering | Carbon Net Zero | Energy Reduction | Renewable Solutions</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="home">
        <h2>Empowering Your Sustainable Future</h2>
        <p>We provide tailored energy solutions to help businesses achieve efficiency, reduce costs, and move towards a carbon-neutral future.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <div class="services">
            <div class="service">
                <h3>Recharge Metering Surveys</h3>
                <p>Monitor and allocate energy costs effectively with precision metering solutions.</p>
            </div>
            <div class="service">
                <h3>Carbon Net Zero Surveys</h3>
                <p>Comprehensive assessments to help you achieve carbon neutrality goals.</p>
            </div>
            <div class="service">
                <h3>Energy Reduction Surveys</h3>
                <p>Identify opportunities to reduce energy consumption and operational costs.</p>
            </div>
            <div class="service">
                <h3>Renewable Solutions for the Built Environment</h3>
                <p>Tailored strategies for integrating renewable energy in sustainable buildings.</p>
            </div>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>With over 3 years of expertise in energy and carbon surveys, we specialise in providing actionable insights for sustainable development. Our mission is to empower businesses to thrive in a sustainable, low-carbon economy.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form class="contact-form">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Your Energy Consultancy. All Rights Reserved.</p>
    </footer>
</body>
</html>
