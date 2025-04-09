<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic HTML Web Page</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to external CSS (optional) -->
</head>

<body>
    <header>
        <h1>Welcome to My Basic Web Page</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Home Section</h2>
        <p>I am a passoionate learner in Web Development, Database Design & Programming with SQL, Python programming and Software Engineering, 
        with a keen interest in contributing to software development. </p>
        <p>I excel in working under pressure, quickly adaptto new challenges, and have strong communication skills. </p>
        <p>My goal is to continously expand my expertise, stay at the forefront of technological advancement, 
        and apply my knowledge to develop innovative solutions that drive growth ande deliver exceptional results.</p>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>Here is a bit of information about me.</p>
        <ul>
            <li>Name: Leonard Phokane</li>
            <li>Profession: Web Developer</li>
            <li>Hobbies: Coding, Reading and Traveling</li>
        </ul>
        <img src="profile.jpg" alt="John Doe" width="200">
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form action="" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br><br>

            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" cols="50" required></textarea><br><br>

            <input type="submit" value="Submit">
        </form>
    </section>

    <footer>
        <p>© 2025 Leonard Phokane</p>
    </footer>

</body>

</html>

