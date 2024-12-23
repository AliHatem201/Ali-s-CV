<html lang="en" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ali Hatem Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
            text-align: right; /* Align text to the right */
        }

        a {
            text-decoration: none;
            color: #2196f3;
        }

        header {
            background: linear-gradient(135deg, #ffffff, #81d4fa);
            color: #333;
            text-align: center;
            padding: 50px 20px;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
        }

        nav {
            margin-top: 20px;
        }

        nav a {
            margin: 0 15px;
            font-size: 1.1rem;
            font-weight: bold;
            color: #333;
        }

        nav a:hover {
            color: #0288d1;
        }

        main {
            max-width: 1000px;
            margin: 30px auto;
            padding: 20px;
            background: #ffffff;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        section {
            margin-bottom: 40px;
        }

        h2 {
            font-size: 2rem;
            color: #0288d1;
            margin-bottom: 15px;
            position: relative;
        }

        h2::after {
            content: '';
            display: block;
            width: 60px;
            height: 3px;
            background: #0288d1;
            margin-top: 5px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            background: #e1f5fe;
            margin: 10px 0;
            padding: 15px;
            border-radius: 8px;
            display: flex;
            align-items: center;
            gap: 10px;
            border-left: 5px solid #2196f3;
            transition: transform 0.2s;
        }

        ul li:hover {
            transform: scale(1.05);
        }

        .btn {
            display: inline-block;
            background: #2196f3;
            color: #ffffff;
            padding: 10px 20px;
            margin-top: 10px;
            border-radius: 5px;
            font-size: 1rem;
            font-weight: bold;
            transition: background 0.3s;
        }

        .btn:hover {
            background: #0288d1;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2.2rem;
            }

            nav a {
                margin: 0 10px;
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Ali Hatem</h1>
        <p>Video Editor & Aspiring Software Developer</p>
        <nav>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
            <a href="#skills">Skills</a>
            <a href="#education">Education</a>
            <a href="#projects">Projects</a>
            <a href="#awards">Awards</a>
            <a href="#hobbies">Hobbies</a>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>
                Ali Hatem, a second-year preparatory school student from Suez, Egypt, is an accomplished individual with a strong passion for innovation and technology. He has received numerous awards, including 1st place in the Seaperch North Africa competition (2023) and 3rd place in the Talent Bil Arabi competition (2021).
                Ali is highly skilled in video editing, logo design, and social media ad creation, using professional tools such as Adobe Premiere Pro, Canva, and CapCut. He also has experience in programming and website design and development, with proficiency in JavaScript, HTML, and CSS.
                With a deep interest in artificial intelligence and programming, Ali is dedicated to enhancing his skills in project management and team leadership. Among his notable personal projects are Galaxy Wonders, Wonders of Egypt, Decode Academy, and Dino World.
            </p>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>📱 +20 1234567891</p>
            <p>📍 Suez, Egypt</p>
            <p>✉️ <a href="mailto:example@gmail.com">example@gmail.com</a></p>
        </section>

        <section id="skills">
            <h2>Technical Skills</h2>
            <ul>
                <li>Languages: JavaScript, HTML, CSS</li>
                <li>CapCut</li>
                <li>Canva</li>
                <li>Adobe Premiere Pro</li>
                <li>Notion</li>
                <li>Google Slides</li>
                <li>Microsoft PowerPoint</li>
            </ul>
        </section>

        <section id="education">
            <h2>Education</h2>
            <p>A student in the second year of middle school, still studying.</p>
            <ul>
                <li>Future School</li>
                <li>Farouk El-Baz School</li>
                <li>Ahmed Zewail School</li>
                <li>Boys of Islam Private Schools</li>
            </ul>
        </section>

        <section id="projects">
            <h2>Personal Projects</h2>
            <ul>
                <li>Galaxy Wonders</li>
                <li>Wonders of Egypt</li>
                <li>Decode Academy</li>
                <li>Dino World</li>
            </ul>
        </section>

        <section id="awards">
            <h2>Honor Awards</h2>
            <ul>
                <li>4th place - North Africa in the SeaPerch 2024 competition.</li>
                <li>1st place - Middle East in the CoSpace Autonomous competition.</li>
                <li>10th place - National level in the Small Innovator competition 2023.</li>
                <li>1st place - National level in the Creative Child competition 2020.</li>
                <li>1st place - Administrative and Directorate level in the Small Innovator competition 2022.</li>
                <li>2nd place - National level in the Maze Runner JR competition 2019.</li>
                <li>1st place - Governorate level in the "Develop and Change" competition 2024.</li>
                <li>2nd place - Governorate level in the RC EGYPT competition 2020.</li>
                <li>1st place - National level in the RC EGYPT competition 2021.</li>
                <li>1st place - Governorate level in the Young Inventor competition 2020.</li>
                <li>1st place - North Africa in the SeaPerch 2023 competition.</li>
                <li>8th place globally - SeaPerch 2023 competition.</li>
                <li>1st place - National level in the Ambition Creativity competition.</li>
                <li>3rd place - National level in the Talent Bil Arabi competition.</li>
                <li>1st place - Governorate level in the Young Inventor competition 2019.</li>
                <li>1st place - Governorate level in the Young Inventor competition 2023.</li>
                <li>1st place - National level in the Creative Child competition 2020.</li>
                <li>Among the top 10 - in the State Award for Young Creators.</li>
                <li>2nd place - National level in the Robot Academy Challenges 2019.</li>
            </ul>
        </section>

        <section id="hobbies">
            <h2>Hobbies & Interests</h2>
            <p>Artificial Intelligence | Programming | Video Games | Making Websites</p>
        </section>
    </main>
</body>
</html>
