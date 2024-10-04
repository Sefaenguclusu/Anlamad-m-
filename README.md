<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Home Section</h2>
        <p>This is the home section where you introduce your website.</p>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Information about you or your company.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <p>Details about the services you offer.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: contact@example.com</p>
        <p>Phone: +123 456 7890</p>
    </section>

    <footer>
        <p>&copy; 2024 My Website. All rights reserved.</p>
    </footer>

    <script>
        // Simple JS functionality to display an alert when a section is clicked
        document.addEventListener('DOMContentLoaded', () => {
            document.querySelectorAll('section').forEach(section => {
                section.addEventListener('click', () => {
                    alert(`You clicked on the ${section.id} section!`);
                });
            });
        });
    </script>
</body>
</html>
