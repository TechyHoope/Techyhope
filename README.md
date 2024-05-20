```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Techy Hope's Blog</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f0f0f0;
            color: #333;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        nav {
            display: flex;
            justify-content: space-between;
            background: #333;
            color: white;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 7px 20px;
            background: #555;
            border-radius: 5px;
        }
        nav a:hover {
            background: #4CAF50;
        }
        main {
            background: white;
            padding: 20px;
            margin-top: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
        .social {
            text-align: center;
            margin-top: 20px;
        }
        .social a {
            margin: 0 10px;
            color: #333;
            font-size: 20px;
        }
        .social a.youtube {
            color: #FF0000;
        }
        .post {
            margin-bottom: 20px;
        }
        .post h2 {
            color: #4CAF50;
        }
    </style>
</head>
<body>
    <header>
        <h1>Techy Hope's Blog</h1>
    </header>
    <nav class="container">
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>
    <main class="container">
        <section class="blog">
            <article class="post">
                <h2>Welcome to My Blog</h2>
                <p>Hello, and welcome to my blog! Here, I'll be sharing my thoughts on the latest in technology, tips and tricks, and much more. Stay tuned!</p>
            </article>
            <article class="post">
                <h2>Latest Tech Trends in 2024</h2>
                <p>2024 has been an exciting year for tech enthusiasts. From advancements in AI to the latest gadgets, let's explore what's new and trending in the tech world.</p>
            </article>
            <!-- Add more blog posts here -->
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Techy Hope</p>
        <div class="social">
            <a href="https://www.youtube.com/channel/TechyHope" target="_blank" class="youtube">YouTube</a>
            <!-- Add more social media links here if needed -->
        </div>
    </footer>
</body>
</html>
```
