# Portfolio
<br>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- HEADER STARTS HERE -->
    <header>
        <h1 class="logo">MyPortfolio</h1>

        <nav>
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Skills</a>
            <a href="#">Projects</a>
            <a href="#">Contact</a>
        </nav>
    </header>
    <!-- HEADER ENDS HERE -->

    <!-- OTHER SECTIONS COME BELOW -->
    <section class="hero">
        <h2>Hi, I'm Swastik👋</h2>
        <p>CSE Student | Web Developer | Tech Enthusiast</p>
        <button>Look at My Work</button>
    </section>
<section class="skills">
    <h2>My Skills</h2>

    <div class="skill-container">
        <div class="skill-card">HTML</div>
        <div class="skill-card">CSS</div>
        <div class="skill-card">JavaScript</div>
        <div class="skill-card">Git & GitHub</div>
    </div>
</section>
<section class="projects">
    <h2>Projects</h2>

    <div class="project-card">
        <h3>Garbage Management App</h3>
        <p>AI powered waste management system.</p>
    </div>

    <div class="project-card">
        <h3>College Event Management System</h3>
        <p>Web platform to manage college events.</p>
    </div>
</section>
<section class="Contact">
    <h2>Contact</h2>
    <p>Email ID : pswastik248@gmail.com</p>
</section>
<footer>
    <p>© 2026 RED Phoenix. All Rights Reserved.</p>
</footer>

</body>
</html>
<br>
body {
    margin: 0;
    font-family: Arial, sans-serif;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 50px;
    background-color: #0f172a;
}

.logo {
    color: white;
}

nav a {
    color: white;
    margin-left: 20px;
    text-decoration: none;
}

nav a:hover {
    color: #38bdf8;
}
.hero {
    height: 90vh;
    background: linear-gradient(to right, #0f172a, #020617);
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.hero h2 {
    font-size: 48px;
}

.hero p {
    font-size: 20px;
    margin: 10px 0;
}

.hero button {
    padding: 12px 25px;
    font-size: 16px;
    border: none;
    background-color: #38bdf8;
    color: black;
    border-radius: 25px;
    cursor: pointer;
}

.hero button:hover {
    background-color: white;
}
.about {
    padding: 60px 100px;
    text-align: center;
}

.about h2 {
    font-size: 32px;
}

.about p {
    font-size: 18px;
    max-width: 700px;
    margin: auto;
}
.skills {
    padding: 60px;
    background-color: #f1f5f9;
    text-align: center;
}

.skill-container {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 30px;
}

.skill-card {
    padding: 25px 40px;
    background: white;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    transition: transform 0.3s;
}

.skill-card:hover {
    transform: scale(1.1);
}
.projects {
    padding: 60px;
    text-align: center;
}

.project-card {
    background: #0f172a;
    color: white;
    margin: 20px auto;
    padding: 25px;
    max-width: 600px;
    border-radius: 10px;
}
.Contact {
    background: #0f172a;
    color: white;
    margin: 20px auto;
    padding: 25px;
    max-width: 600px;
    border-radius: 10px;
    text-align : center;
}
footer {
    background: #020617;
    color: white;
    text-align: center;
    padding: 15px;
}
