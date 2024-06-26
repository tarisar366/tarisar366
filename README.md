<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Purity Motari's Fashion Blog</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f7f7f7;
            color: #333;
        }
        header {
            background-color: #000;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #ff69b4;
            padding: 10px;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 20px;
        }
        .about, .contact, .affiliate {
            background-color: #fff;
            margin: 20px;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .blog {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .blog article {
            background-color: #fff;
            margin: 20px;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 30%;
        }
        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .movable-images img {
            width: 100%;
            height: auto;
            transition: transform 0.5s;
        }
        .movable-images img:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <header>
        <h1>Purity Motari's Fashion Blog</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Me</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contact</a>
        <a href="#affiliate">Affiliate Marketing</a>
    </nav>
    <section id="home">
        <h2>Welcome to My Fashion Blog</h2>
        <div class="movable-images">
            <img src="fashion1.jpg" alt="Fashion Image 1">
            <img src="fashion2.jpg" alt="Fashion Image 2">
            <img src="fashion3.jpg" alt="Fashion Image 3">
        </div>
    </section>
    <section id="about" class="about">
        <h2>About Me</h2>
        <p>Hello! I'm Purity Motari, a passionate fashion enthusiast and freelancer. Welcome to my blog where I share my love for fashion, style tips, and much more. Stay tuned!</p>
    </section>
    <section id="blog" class="blog">
        <h2>Blog</h2>
        <article>
            <h3>Latest Fashion Trends</h3>
            <p>Discover the latest trends in fashion this season. From bold colors to minimalist styles, find out what's hot right now!</p>
        </article>
        <article>
            <h3>Fashion Tips</h3>
            <p>Get the best fashion tips to enhance your style. Learn how to mix and match outfits, accessorize, and more.</p>
        </article>
        <article>
            <h3>Designer Spotlight</h3>
            <p>Meet the top designers in the industry and explore their latest collections. Find inspiration for your next outfit!</p>
        </article>
    </section>
    <section id="contact" class="contact">
        <h2>Contact</h2>
        <p>If you'd like to get in touch, feel free to drop me a message. You can reach me at purity@example.com or follow me on social media.</p>
    </section>
    <section id="affiliate" class="affiliate">
        <h2>Affiliate Marketing</h2>
        <p>Check out my favorite fashion products and brands. As an affiliate, I earn from qualifying purchases, so your support means a lot!</p>
    </section>
    <footer>
        <p>&copy; 2024 Purity Motari. All rights reserved.</p>
    </footer>
</body>
</html>
