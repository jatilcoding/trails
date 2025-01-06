<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to Tourist World</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #ff6347;
            color: white;
            padding: 1em;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .content {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Tourist World</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#destinations">Destinations</a>
        <a href="#tours">Tours</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="content" id="home">
        <h2>Discover Amazing Places</h2>
        <p>Welcome to Tourist World! Explore the most beautiful destinations around the globe.</p>
    </div>
    <div class="content" id="destinations">
        <h2>Top Destinations</h2>
        <p>Check out our recommended destinations for an unforgettable experience.</p>
    </div>
    <div class="content" id="tours">
        <h2>Our Tours</h2>
        <p>Join our exciting tours and make the most of your travel experience.</p>
    </div>
    <div class="content" id="contact">
        <h2>Contact Us</h2>
        <p>Have any questions? Feel free to reach out to us!</p>
    </div>
    <footer>
        <p>&copy; 2025 Tourist World. All rights reserved.</p>
    </footer>
</body>
</html>
