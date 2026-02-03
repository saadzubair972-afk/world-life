# world-life
This wb help you in various purposes like world tension or predictions also help you for education system
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sky Themed Front Page</title>
    <style>
        /* Body with sky blue gradient */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom, #87CEEB, #ffffff);
            color: #333;
            overflow-x: hidden;
        }

        /* Clouds using pseudo-elements */
        .cloud {
            position: absolute;
            background: white;
            border-radius: 50%;
            opacity: 0.8;
        }
        .cloud::before, .cloud::after {
            content: '';
            position: absolute;
            background: white;
            border-radius: 50%;
        }

        /* Example cloud positions and sizes */
        #cloud1 {
            width: 120px;
            height: 60px;
            top: 50px;
            left: 50px;
        }
        #cloud1::before {
            width: 60px;
            height: 60px;
            top: -20px;
            left: 10px;
        }
        #cloud1::after {
            width: 70px;
            height: 70px;
            top: -15px;
            left: 50px;
        }

        #cloud2 {
            width: 150px;
            height: 80px;
            top: 150px;
            right: 50px;
        }
        #cloud2::before {
            width: 80px;
            height: 80px;
            top: -25px;
            left: 20px;
        }
        #cloud2::after {
            width: 90px;
            height: 90px;
            top: -20px;
            left: 60px;
        }

        header {
            background-color: rgba(0, 123, 255, 0.8);
            color: white;
            padding: 40px 0;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
        }

        nav {
            background-color: rgba(0, 0, 255, 0.8);
            overflow: hidden;
        }

        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            background-color: #fff;
            color: #007BFF;
        }

        main {
            padding: 60px 20px;
            text-align: center;
        }

        main h2 {
            color: #007BFF;
        }

        footer {
            background-color: rgba(0, 0, 255, 0.8);
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
        }
    </style>
</head>
<body>

    <!-- Clouds -->
    <div id="cloud1" class="cloud"></div>
    <div id="cloud2" class="cloud"></div>

    <header>
        <h1>Welcome to My Sky-Themed Website</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </nav>

    <main>
        <h2>About This Page</h2>
        <p>Enjoy this sky-themed design with clouds floating around. Customize it with your content and images!</p>
    </main>

    <footer>
        &copy; 2026 My Sky Website. All Rights Reserved.
    </footer>

</body>
</html>
