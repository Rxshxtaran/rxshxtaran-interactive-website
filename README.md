<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Explore Rishitaran's World</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* General Styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #e0eafc, #cfdef3);
            color: #333;
            overflow-x: hidden;
        }

        header {
            background: linear-gradient(90deg, #1f4037, #99f2c8);
            color: #ffffff;
            padding: 30px 0;
            text-align: center;
            text-shadow: 2px 2px 4px #000000;
        }

        header h1 {
            font-size: 2.5em;
            animation: color-change 2s infinite alternate;
        }

        @keyframes color-change {
            from { color: #ffffff; }
            to { color: #ffeb3b; }
        }

        nav {
            display: flex;
            justify-content: center;
            background: #333333;
            padding: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.3);
        }

        nav a {
            color: #ffffff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease-in-out;
        }

        nav a:hover {
            color: #ffeb3b;
        }

        .container {
            max-width: 1100px;
            margin: 40px auto;
            padding: 0 20px;
        }

        section {
            margin-bottom: 30px;
            padding: 20px;
            background: #ffffff;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }

        section:hover {
            transform: scale(1.02);
        }

        h2 {
            color: #1f4037;
            text-align: center;
            font-size: 2em;
            text-shadow: 1px 1px 3px #aaaaaa;
        }

        p, ul, ol {
            font-size: 1.1em;
            line-height: 1.6;
        }

        ul, ol {
            margin-left: 20px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #333333;
            color: #ffffff;
        }

        .login-form {
            max-width: 400px;
            margin: 20px auto;
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            animation: glow 2s infinite alternate;
        }

        @keyframes glow {
            from { box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); }
            to { box-shadow: 0 4px 12px rgba(0, 0, 0, 0.4); }
        }

        .login-form input, .login-form button {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ddd;
            outline: none;
            transition: background-color 0.3s, box-shadow 0.3s;
        }

        .login-form button {
            background: #1f4037;
            color: #ffffff;
            font-weight: bold;
            cursor: pointer;
        }

        .login-form button:hover {
            background: #28a745;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Rishitaran's Interactive World</h1>
    <p>Your one-stop space to learn more about me, my hobbies, and what I love!</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About Me</a>
    <a href="#hobbies">My Hobbies</a>
    <a href="#interests">My Interests</a>
    <a href="#contact">Contact</a>
    <a href="#login">Login</a>
</nav>

<div class="container">

    <!-- Home Section -->
    <section id="home">
        <h2>Home</h2>
        <p>Welcome to my space! My name is Rishitaran s/o Raman. I am a student with a passion for learning, exploring, and creating. Dive into my site to find out more about who I am, my hobbies, and the things that inspire me.</p>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>I'm a lifelong learner with a keen interest in technology, arts, and nature. I enjoy working on projects, learning new programming languages, and exploring creative outlets.</p>
    </section>

    <!-- Hobbies Section -->
    <section id="hobbies">
        <h2>My Hobbies</h2>
        <p>Here are some of my favorite activities:</p>
        <ul>
            <li><strong>Gaming:</strong> I love a good challenge, especially in strategy games.</li>
            <li><strong>Reading:</strong> Fantasy and science fiction books are my go-to genres.</li>
            <li><strong>Hiking:</strong> Nothing beats the peace of nature.</li>
        </ul>
    </section>

    <!-- Interests Section -->
    <section id="interests">
        <h2>My Interests</h2>
        <p>I'm also passionate about:</p>
        <ol>
            <li><strong>Tech Innovations:</strong> Exploring AI and software development trends.</li>
            <li><strong>Art:</strong> Experimenting with digital and traditional art.</li>
        </ol>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br><br>
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="5" required></textarea><br><br>
            <input type="submit" value="Submit">
        </form>
    </section>

    <!-- Login Section -->
    <section id="login">
        <h2>Login</h2>
        <div class="login-form">
            <form action="#" method="post">
                <label for="username">Username:</label>
                <input type="text" id="username" name="username" required>
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>
                <button type="submit">Login</button>
            </form>
        </div>
    </section>

</div>

<footer>
    <p>&copy; 2024 Rishitaran s/o Raman</p>
</footer>

</body>
</html>
