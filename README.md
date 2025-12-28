<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rahima Mohamoud | Portfolio</title>
    <style>
        /* Modern reset to prevent "cut" edges */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            line-height: 1.8;
            color: #333;
            background-color: #fff;
            scroll-behavior: smooth;
        }

        /* Navigation - Floating style */
        nav {
            background: rgba(255, 255, 255, 0.95);
            padding: 20px 10%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #f0f0f0;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav .logo {
            font-size: 1.2rem;
            font-weight: bold;
            letter-spacing: 3px;
        }

        nav a {
            text-decoration: none;
            color: #777;
            margin-left: 25px;
            font-size: 0.75rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            transition: 0.3s;
        }

        nav a:hover { color: #000; }

        /* Hero Section - Taller for better scale */
        header {
            height: 75vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background: #1a1a1a;
            color: white;
            text-align: center;
            padding: 20px;
        }

        header h1 {
            font-size: 3rem;
            font-weight: 200;
            letter-spacing: 8px;
            margin-bottom: 15px;
        }

        header p {
            font-size: 1rem;
            letter-spacing: 3px;
            text-transform: uppercase;
            opacity: 0.6;
        }

        /* Section Layout */
        section {
            padding: 100px 10%; /* Lots of space to prevent feeling "cut" */
            max-width: 1400px;
            margin: 0 auto;
        }

        h2 {
            font-size: 1.8rem;
            font-weight: 300;
            margin-bottom: 40px;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        /* Bio */
        .bio-text {
            font-size: 1.2rem;
            color: #555;
            max-width: 700px;
        }

        /* Skills */
        .skills-container {
            margin-top: 40px;
        }

        .skill-tag {
            display: inline-block;
            background: #f7f7f7;
            padding: 8px 20px;
            margin: 5px;
            font-size: 0.8rem;
            border-radius: 50px;
            border: 1px solid #eee;
        }

        .cv-btn {
            display: inline-block;
            margin-top: 30px;
            padding: 12px 30px;
            background: #000;
            color: #fff;
            text-decoration: none;
            font-size: 0.8rem;
            letter-spacing: 1px;
            transition: 0.3s;
        }

        .cv-btn:hover { background: #444; }

        /* Gallery Grid */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 40px;
        }

        .card {
            background: #fcfcfc;
            border: 1px solid #f0f0f0;
            height: 350px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            transition: 0.4s ease;
            cursor: pointer;
        }

        .card:hover {
            background: #fff;
            box-shadow: 0 20px 40px rgba(0,0,0,0.05);
            transform: translateY(-10px);
        }

        /* Contact */
        .contact-info a {
            color: #000;
            font-weight: bold;
            text-decoration: none;
            border-bottom: 1px solid #ccc;
        }

        footer {
            text-align: center;
            padding: 60px;
            font-size: 0.7rem;
            letter-spacing: 1px;
            color: #bbb;
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">RAHIMA.M</div>
        <div>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#gallery">Gallery</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <header id="home">
        <h1>RAHIMA MOHAMOUD</h1>
        <p>Architecture Student</p>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <div class="bio-text">
            Hi, I'm Rahima! I'm an architecture student who loves turning complex ideas into structural realities. 
            From hand-sketched concepts to digital models, I am passionate about every step of the design process. 
            Welcome to my portfolio!
        </div>
        
        <div class="skills-container">
            <span class="skill-tag">Hand Sketching</span>
            <span class="skill-tag">AutoCAD</span>
            <span class="skill-tag">SketchUp</span>
            <span class="skill-tag">3D Modeling</span>
            <span class="skill-tag">Photoshop</span>
        </div>

        <a href="#" class="cv-btn">DOWNLOAD CV</a>
    </section>

    <section id="gallery">
        <h2>Selected Work</h2>
        <div class="gallery">
            <div class="card">
                <strong>Project 01</strong>
                <p style="font-size: 0.8rem; color: #999;">Residential Design</p>
            </div>
            <div class="card">
                <strong>Project 02</strong>
                <p style="font-size: 0.8rem; color: #999;">Public Space Concept</p>
            </div>
            <div class="card">
                <strong>Project 03</strong>
                <p style="font-size: 0.8rem; color: #999;">Sustainable Pavilion</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <div class="contact-info">
            <p>Email: <a href="mailto:rahimamohamoud4@email.com">rahimamohamoud4@email.com</a></p>
            <p style="margin-top: 10px; color: #888;">Feel free to reach out for collaborations!</p>
        </div>
    </section>

    <footer>
        &copy; 2025 RAHIMA MOHAMOUD PORTFOLIO
    </footer>

</body>
</html>

