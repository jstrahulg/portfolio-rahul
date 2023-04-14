<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#about">About Me</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="about">
      <h1>About Me</h1>
      <p>Write about yourself and your background here.</p>
    </section>

    <section id="skills">
      <h1>Skills</h1>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>Python</li>
      </ul>
    </section>

    <section id="projects">
      <h1>Projects</h1>
      <ul>
        <li><a href="#">Project 1</a></li>
        <li><a href="#">Project 2</a></li>
        <li><a href="#">Project 3</a></li>
      </ul>
    </section>

    <section id="contact">
      <h1>Contact</h1>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>

        <button type="submit">Submit</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2023 My Portfolio</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
