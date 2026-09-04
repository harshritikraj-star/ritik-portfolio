# ritik-portfolio
modern &amp; dynamic full-stock devel 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Full Stack Developer Portfolio</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        body { background-color: #0f172a; color: #f8fafc; line-height: 1.6; }
        header { display: flex; justify-content: space-between; align-items: center; padding: 2rem 5%; background-color: #1e293b; }
        .logo { font-size: 1.5rem; font-weight: bold; color: #38bdf8; }
        nav a { color: #f8fafc; text-decoration: none; margin-left: 1.5rem; transition: 0.3s; }
        nav a:hover { color: #38bdf8; }
        .hero { height: 80vh; display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; padding: 0 1rem; }
        .hero h1 { font-size: 3rem; margin-bottom: 1rem; }
        .hero span { color: #38bdf8; }
        .hero p { font-size: 1.2rem; color: #94a3b8; max-width: 600px; margin-bottom: 2rem; }
        .btn { background-color: #38bdf8; color: #0f172a; padding: 0.75rem 1.5rem; border-radius: 5px; text-decoration: none; font-weight: bold; }
        .skills { padding: 4rem 5%; background-color: #1e293b; text-align: center; }
        .skills h2 { font-size: 2rem; margin-bottom: 2rem; color: #38bdf8; }
        .skills-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 1.5rem; }
        .skill-card { background: #0f172a; padding: 1.5rem; border-radius: 8px; border: 1px solid #334155; }
        footer { text-align: center; padding: 2rem; background-color: #0f172a; color: #64748b; border-top: 1px solid #334155; }
    </style>
</head>
<body>
    <header>
        <div class="logo">&lt;Developer /&gt;</div>
        <nav>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
        </nav>
    </header>

    <section class="hero" id="about">
        <h1>Hi, I'm a <span>Full Stack Developer</span></h1>
        <p>I build end-to-end web applications with modern frontend designs and robust backend architectures.</p>
        <a href="#skills" class="btn">Explore My Work</a>
    </section>

    <section class="skills" id="skills">
        <h2>Tech Stack</h2>
        <div class="skills-grid">
            <div class="skill-card">HTML5 & CSS3</div>
            <div class="skill-card">JavaScript</div>
            <div class="skill-card">React.js</div>
            <div class="skill-card">Node.js</div>
            <div class="skill-card">Express.js</div>
            <div class="skill-card">MongoDB / SQL</div>
            <div class="skill-card">Git & GitHub</div>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 Full Stack Developer. Built with HTML & CSS.</p>
    </footer>
</body>
</html>
