<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tourism Guide</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
        }

        header h1 {
            margin: 0;
        }

        nav ul {
            list-style: none;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        .hero {
            background-image: url('sstz.jpeg');
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #0e0101;
        }

        .hero-content {
            max-width: 600px;
        }

        .search-section {
            background-color: #f4f4f4;
            padding: 50px 20px;
            text-align: center;
        }

        .search-section h2 {
            margin-bottom: 20px;
        }

        .search-section input[type="text"] {
            padding: 10px;
            width: 60%;
            margin-bottom: 20px;
        }

        .search-section button {
            padding: 10px 20px;
            background-color: #333;
            color: #fff;
            border: none;
            cursor: pointer;
        }

        .destination-section {
            padding: 50px 20px;
            text-align: center;
        }

        .destination-section h2 {
            margin-bottom: 20px;
        }

        .footer-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
        }

        .footer-content ul {
            list-style: none;
        }

        .footer-content ul li {
            display: inline;
            margin-right: 10px;
        }

        .footer-content ul li a {
            color: #fff;
            text-decoration: none;
        }
        .btn {
            padding: 10px 20px;
            background-color: #333;
            color: #fff;
            border: none;
            cursor: pointer;
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Tourism Guide</h1>
        <nav>
            <ul>
                <li><a href="#search">Search</a></li>
                <li><a href="#destinations">Destinations</a></li>
                <li><a href="#login">Login</a></li>
                <li><a href="#register">Register</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <div class="hero-content">
            <h2>Discover Your Next Adventure</h2>
            <p>Find your perfect destination with us</p>
            <a href="#search" class="btn">Start Exploring</a>
        </div>
    </section>
    <section id="search" class="search-section">
        <h2>Search for Your Next Destination</h2>
        <input type="text" name="destination" placeholder="Enter a destination...">
        <button type="submit">Search</button>
    </section>
    <section id="destinations" class="destination-section">
        <h2>Featured Destinations</h2>
    </section>
    <footer>
        <div class="footer-content">
            <p>&copy; 2024 Tourism Guide. All rights reserved.</p>
            <ul>
                <li><a href="#">Terms of Service</a></li>
                <li><a href="#">Privacy Policy</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </div>
    </footer>
</body>
</html>
