<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Website</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f5f5f5;
        }

        header {
            background: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }

        nav {
            background: #555;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        .container {
            padding: 20px;
        }

        button {
            padding: 10px 15px;
            background: #333;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }

        button:hover {
            background: #555;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
    </style>
</head>

<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>

    <div class="container">
        <h2>Hello!</h2>
        <p>This is a simple example of a normal website layout.</p>
        <button onclick="sayHello()">Click Me</button>
    </div>

    <footer>
        © 2025 My Website
    </footer>

    <script>
        function sayHello() {
            alert("Hello from your website!");
        }
    </script>
</body>
</html>
