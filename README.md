<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kajaluxshan Thavalingam - Hacker Dashboard</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            background: linear-gradient(135deg, #0d1117 0%, #1a202c 100%);
            color: #e2e8f0;
            font-family: 'Courier New', monospace;
        }
        .terminal {
            background: #1a202c;
            border: 2px solid #38bdf8;
            border-radius: 8px;
            padding: 1rem;
            box-shadow: 0 0 20px rgba(56, 189, 248, 0.5);
            animation: pulse 2s infinite;
        }
        .project-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .project-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 0 20px rgba(99, 102, 241, 0.7);
        }
        .glow-button {
            background: #1a202c;
            border: 2px solid #6366f1;
            color: #e2e8f0;
            transition: all 0.3s ease;
        }
        .glow-button:hover {
            background: #6366f1;
            box-shadow: 0 0 15px rgba(99, 102, 241, 0.8);
        }
        @keyframes pulse {
            0% { box-shadow: 0 0 10px rgba(56, 189, 248, 0.5); }
            50% { box-shadow: 0 0 20px rgba(56, 189, 248, 0.8); }
            100% { box-shadow: 0 0 10px rgba(56, 189, 248, 0.5); }
        }
        .typewriter {
            overflow: hidden;
            white-space: nowrap;
            animation: typing 3s steps(40, end), blink-caret 0.75s step-end infinite;
        }
        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }
        @keyframes blink-caret {
            from, to { border-color: transparent; }
            50% { border-color: #38bdf8; }
        }
    </style>
</head>
<body class="min-h-screen flex flex-col items-center justify-center p-4">
    <header class="text-center mb-8">
        <h1 class="text-4xl md:text-5xl font-bold text-indigo-400 typewriter">
            Kajaluxshan Thavalingam
        </h1>
        <p class="text-lg md:text-xl text-gray-300 mt-2">
            Software Engineering Undergraduate | Developer | Tech Enthusiast
        </p>
    </header>

    <section class="terminal w-full max-w-3xl mx-auto mb-8">
        <h2 class="text-2xl text-indigo-300 mb-4">$ whoami</h2>
        <p class="text-gray-200">
            > I am currently pursuing a <span class="text-indigo-400">B.Sc. (Hons) in Software Engineering</span> at the University of Kelaniya. Passionate about <span class="text-indigo-400">full-stack development</span>, <span class="text-indigo-400">cloud computing</span>, and building scalable, user-friendly applications. I thrive on impactful projects and open-source contributions.
        </p>
        <ul class="list-disc list-inside text-gray-200 mt-4">
            <li>Resilient, collaborative, and detail-oriented</li>
            <li>Skilled in <span class="text-indigo-400">Java, Python, C#, JavaScript, Kotlin, Flutter</span></li>
            <li>Experience in <span class="text-indigo-400">cloud platforms, DevOps, and mobile backend APIs</span></li>
        </ul>
    </section>

    <section class="w-full max-w-4xl mx-auto mb-8">
        <h2 class="text-2xl text-indigo-300 mb-4">> Technologies & Tools</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
            <div class="bg-gray-800 p-4 rounded-lg">
                <h3 class="text-lg text-indigo-400">Programming Languages</h3>
                <p class="text-gray-300">C#, Python, Java, JavaScript, Kotlin, Flutter</p>
            </div>
            <div class="bg-gray-800 p-4 rounded-lg">
                <h3 class="text-lg text-indigo-400">Frameworks & Libraries</h3>
                <p class="text-gray-300">React.js, .NET, Spring Boot, Express.js</p>
            </div>
            <div class="bg-gray-800 p-4 rounded-lg">
                <h3 class="text-lg text-indigo-400">Databases</h3>
                <p class="text-gray-300">SQLite, MySQL, MongoDB, PostgreSQL</p>
            </div>
            <div class="bg-gray-800 p-4 rounded-lg">
                <h3 class="text-lg text-indigo-400">Cloud & DevOps</h3>
                <p class="text-gray-300">AWS (EC2, RDS), Docker, GitHub Actions</p>
            </div>
            <div class="bg-gray-800 p-4 rounded-lg">
                <h3 class="text-lg text-indigo-400">Tools</h3>
                <p class="text-gray-300">Visual Studio, VS Code, IntelliJ IDEA</p>
            </div>
        </div>
    </section>

    <section class="w-full max-w-4xl mx-auto mb-8">
        <h2 class="text-2xl text-indigo-300 mb-4">> Project Highlights</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
            <div class="project-card bg-gray-800 p-4 rounded-lg">
                <h3 class="text-lg text-indigo-400">Nexus - University Club Management</h3>
                <p class="text-gray-300">Full-stack web app for managing university clubs and events with real-time chat and task tracking.</p>
                <a href="https://github.com/Kajaluxshan7/Nexus" class="text-indigo-400 hover:underline">View on GitHub</a>
            </div>
            <div class="project-card bg-gray-800 p-4 rounded-lg">
                <h3 class="text-lg text-indigo-400">Personal Finance Management App</h3>
                <p class="text-gray-300">Desktop app for tracking income, expenses, and budgeting with secure authentication.</p>
                <a href="https://github.com/Kajaluxshan7/PersonalFinanceApp" class="text-indigo-400 hover:underline">View on GitHub</a>
            </div>
            <div class="project-card bg-gray-800 p-4 rounded-lg">
                <h3 class="text-lg text-indigo-400">Secure Web Application</h3>
                <p class="text-gray-300">Vehicle reservation system addressing OWASP vulnerabilities with Java and JSP.</p>
                <a href="https://github.com/Kajaluxshan7/Secure-Web-Application-Development" class="text-indigo-400 hover:underline">View on GitHub</a>
            </div>
            <div class="project-card bg-gray-800 p-4 rounded-lg">
                <h3 class="text-lg text-indigo-400">Mobile Shop Backend API</h3>
                <p class="text-gray-300">Backend API with Spring Boot for a mobile e-commerce app.</p>
                <a href="https://github.com/Kajaluxshan7/MobileShopApplication" class="text-indigo-400 hover:underline">View on GitHub</a>
            </div>
        </div>
    </section>

    <section class="w-full max-w-4xl mx-auto mb-8">
        <h2 class="text-2xl text-indigo-300 mb-4">> GitHub Stats</h2>
        <img src="https://github-readme-stats.vercel.app/api?username=Kajaluxshan7&show_icons=true&theme=radical" alt="Kajaluxshan7's GitHub stats" class="w-full">
    </section>

    <section class="w-full max-w-4xl mx-auto mb-8">
        <h2 class="text-2xl text-indigo-300 mb-4">> Connect</h2>
        <div class="flex flex-wrap gap-4">
            <a href="mailto:thavamkajan7777@gmail.com" class="glow-button px-4 py-2 rounded-lg">Email</a>
            <a href="tel:+94762676832" class="glow-button px-4 py-2 rounded-lg">Phone</a>
            <a href="https://www.linkedin.com/in/kajaluxshan-thavalingam-494964211" class="glow-button px-4 py-2 rounded-lg">LinkedIn</a>
            <a href="https://medium.com/@thavamkajan7777" class="glow-button px-4 py-2 rounded-lg">Medium</a>
            <a href="https://github.com/Kajaluxshan7" class="glow-button px-4 py-2 rounded-lg">GitHub</a>
        </div>
    </section>

    <footer class="text-center text-gray-400 mt-8">
        <p>&gt; "Continuous learning and collaboration drive success in technology and life."</p>
    </footer>

    <script>
        // Add interactivity for terminal effect
        document.addEventListener('DOMContentLoaded', () => {
            const terminal = document.querySelector('.terminal');
            terminal.addEventListener('click', () => {
                terminal.style.animation = 'pulse 2s infinite';
            });
        });
    </script>
</body>
</html>
