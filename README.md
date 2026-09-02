<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Python Mini Projects | Sameer</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #0d1117;
            color: #ffffff;
            line-height: 1.6;
        }

        .container {
            width: 90%;
            max-width: 1100px;
            margin: auto;
        }

        /* HEADER */

        header {
            text-align: center;
            padding: 60px 20px 35px;
        }

        header h1 {
            font-size: 42px;
            margin-bottom: 10px;
        }

        header h1 span {
            color: #58a6ff;
        }

        header p {
            color: #8b949e;
            font-size: 17px;
        }

        /* STATS */

        .stats {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 15px;
            margin: 25px 0;
        }

        .stat {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 12px;
            padding: 22px;
            text-align: center;
        }

        .stat h2 {
            color: #58a6ff;
            font-size: 30px;
        }

        .stat p {
            color: #8b949e;
        }

        /* SECTION */

        section {
            margin: 45px 0;
        }

        .title {
            font-size: 26px;
            margin-bottom: 18px;
        }

        .title span {
            color: #58a6ff;
        }

        /* PROJECT PROGRESS */

        .progress-box {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 14px;
            padding: 25px;
        }

        .progress-info {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
        }

        .progress-info span:last-child {
            color: #58a6ff;
            font-weight: bold;
        }

        .progress-bar {
            width: 100%;
            height: 14px;
            background: #21262d;
            border-radius: 20px;
            overflow: hidden;
        }

        .progress-fill {
            width: 65%;
            height: 100%;
            background: #58a6ff;
            border-radius: 20px;
        }

        /* PROJECT GRID */

        .projects {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 18px;
        }

        .project {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 14px;
            padding: 22px;
            transition: 0.3s;
        }

        .project:hover {
            transform: translateY(-5px);
            border-color: #58a6ff;
        }

        .project h3 {
            margin-bottom: 8px;
        }

        .project p {
            color: #8b949e;
            font-size: 14px;
        }

        .tag {
            display: inline-block;
            margin-top: 12px;
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 12px;
        }

        .done {
            background: #1f6f43;
        }

        .working {
            background: #9e6a03;
        }

        .planned {
            background: #30363d;
        }

        /* CHART */

        .chart {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 14px;
            padding: 25px;
        }

        .bar {
            margin: 20px 0;
        }

        .bar-name {
            display: flex;
            justify-content: space-between;
            margin-bottom: 7px;
        }

        .bar-name span:last-child {
            color: #58a6ff;
        }

        .bar-line {
            height: 10px;
            background: #21262d;
            border-radius: 20px;
            overflow: hidden;
        }

        .bar-value {
            height: 100%;
            border-radius: 20px;
            background: #58a6ff;
        }

        /* ROADMAP */

        .roadmap {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 15px;
        }

        .roadmap div {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 12px;
            padding: 20px;
            text-align: center;
        }

        .roadmap h3 {
            margin-bottom: 7px;
        }

        .roadmap p {
            color: #8b949e;
            font-size: 13px;
        }

        /* FOOTER */

        footer {
            text-align: center;
            padding: 35px 20px;
            border-top: 1px solid #30363d;
            color: #8b949e;
            margin-top: 50px;
        }

        footer strong {
            color: #58a6ff;
        }

        /* RESPONSIVE */

        @media (max-width: 800px) {

            .stats {
                grid-template-columns: repeat(2, 1fr);
            }

            .projects {
                grid-template-columns: 1fr;
            }

            .roadmap {
                grid-template-columns: repeat(2, 1fr);
            }

            header h1 {
                font-size: 32px;
            }
        }

        @media (max-width: 500px) {

            .stats {
                grid-template-columns: 1fr;
            }

            .roadmap {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>

<body>

<div class="container">

    <!-- HEADER -->

    <header>
        <h1>🐍 Python <span>Mini Projects</span></h1>

        <p>
            A collection of small Python projects built while learning
            programming step by step.
        </p>
    </header>


    <!-- STATS -->

    <div class="stats">

        <div class="stat">
            <h2>08</h2>
            <p>Total Projects</p>
        </div>

        <div class="stat">
            <h2>05</h2>
            <p>Completed</p>
        </div>

        <div class="stat">
            <h2>02</h2>
            <p>In Progress</p>
        </div>

        <div class="stat">
            <h2>01</h2>
            <p>Planned</p>
        </div>

    </div>


    <!-- PROJECT PROGRESS -->

    <section>

        <h2 class="title">📊 Project <span>Progress</span></h2>

        <div class="progress-box">

            <div class="progress-info">
                <span>Overall Repository Progress</span>
                <span>65%</span>
            </div>

            <div class="progress-bar">
                <div class="progress-fill"></div>
            </div>

            <p style="color:#8b949e; margin-top:12px;">
                Projects are growing as I learn and explore more Python concepts.
            </p>

        </div>

    </section>


    <!-- PROJECTS -->

    <section>

        <h2 class="title">🚀 <span>Projects</span></h2>

        <div class="projects">

            <div class="project">
                <h3>🔐 Username & Password Generator</h3>
                <p>
                    Generates simple username and memorable password suggestions
                    based on user input.
                </p>
                <span class="tag done">✓ Completed</span>
            </div>


            <div class="project">
                <h3>📱 Product Price Comparator</h3>
                <p>
                    A project idea for comparing product prices and learning
                    Python-based data handling.
                </p>
                <span class="tag working">↻ In Progress</span>
            </div>


            <div class="project">
                <h3>🔳 QR Code Generator</h3>
                <p>
                    Creates QR codes from text or URLs and saves them as images.
                </p>
                <span class="tag done">✓ Completed</span>
            </div>


            <div class="project">
                <h3>🤖 Mini AI Assistant</h3>
                <p>
                    Exploring the basics of AI assistants, APIs and
                    Python automation.
                </p>
                <span class="tag working">↻ In Progress</span>
            </div>


            <div class="project">
                <h3>🧮 Calculator</h3>
                <p>
                    Beginner calculator project created to practice Python
                    operators and functions.
                </p>
                <span class="tag done">✓ Completed</span>
            </div>


            <div class="project">
                <h3>🎲 Mini Games</h3>
                <p>
                    Small Python games created to practice conditions,
                    loops and user input.
                </p>
                <span class="tag done">✓ Completed</span>
            </div>


            <div class="project">
                <h3>📁 File Organizer</h3>
                <p>
                    A planned project for learning Python file handling
                    and automation.
                </p>
                <span class="tag planned">📌 Planned</span>
            </div>


            <div class="project">
                <h3>🌐 Web Project</h3>
                <p>
                    Future project combining Python with HTML and CSS
                    basics.
                </p>
                <span class="tag done">✓ Completed</span>
            </div>

        </div>

    </section>


    <!-- LEARNING GRAPH -->

    <section>

        <h2 class="title">📈 Project <span>Growth</span></h2>

        <div class="chart">

            <div class="bar">

                <div class="bar-name">
                    <span>Python Basics</span>
                    <span>85%</span>
                </div>

                <div class="bar-line">
                    <div class="bar-value" style="width:85%;"></div>
                </div>

            </div>


            <div class="bar">

                <div class="bar-name">
                    <span>Problem Solving</span>
                    <span>70%</span>
                </div>

                <div class="bar-line">
                    <div class="bar-value" style="width:70%;"></div>
                </div>

            </div>


            <div class="bar">

                <div class="bar-name">
                    <span>Python Projects</span>
                    <span>65%</span>
                </div>

                <div class="bar-line">
                    <div class="bar-value" style="width:65%;"></div>
                </div>

            </div>


            <div class="bar">

                <div class="bar-name">
                    <span>Web Development</span>
                    <span>35%</span>
                </div>

                <div class="bar-line">
                    <div class="bar-value" style="width:35%;"></div>
                </div>

            </div>


            <div class="bar">

                <div class="bar-name">
                    <span>AI & AI Agents</span>
                    <span>25%</span>
                </div>

                <div class="bar-line">
                    <div class="bar-value" style="width:25%;"></div>
                </div>

            </div>

        </div>

    </section>


    <!-- ROADMAP -->

    <section>

        <h2 class="title">🗺️ <span>What's Coming Next?</span></h2>

        <div class="roadmap">

            <div>
                <h3>🌐 Web</h3>
                <p>HTML, CSS & small websites</p>
            </div>

            <div>
                <h3>🤖 AI</h3>
                <p>Basic AI agents & APIs</p>
            </div>

            <div>
                <h3>🗄️ Database</h3>
                <p>SQL & database projects</p>
            </div>

            <div>
                <h3>🚀 More</h3>
                <p>Bigger and better projects</p>
            </div>

        </div>

    </section>


</div>


<!-- FOOTER -->

<footer>

    <p>
        🐍 Building projects while learning Python.
    </p>

    <p>
        <strong>Learning → Building → Improving 🚀</strong>
    </p>

</footer>


</body>
</html>
