<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aung Kaung Myat - GitHub Profile</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
            margin: 0;
            padding: 20px;
            line-height: 1.6;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .header {
            text-align: center;
            margin-bottom: 30px;
        }
        
        .name-container {
            display: inline-flex;
            align-items: center;
            gap: 15px;
            margin-bottom: 10px;
        }
        
        .animated-emoji {
            font-size: 2.5em;
            animation: wave 2s ease-in-out infinite;
            transform-origin: 70% 70%;
            filter: drop-shadow(0 0 10px rgba(88, 166, 255, 0.3));
        }
        
        .animated-name {
            font-size: 2.5em;
            font-weight: bold;
            background: linear-gradient(45deg, #58a6ff, #7c3aed, #ec4899, #58a6ff);
            background-size: 300% 300%;
            background-clip: text;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: gradientShift 3s ease-in-out infinite, textGlow 2s ease-in-out infinite alternate;
            text-shadow: 0 0 20px rgba(88, 166, 255, 0.5);
        }
        
        @keyframes wave {
            0%, 100% { transform: rotate(0deg); }
            25% { transform: rotate(-10deg); }
            75% { transform: rotate(10deg); }
        }
        
        @keyframes gradientShift {
            0%, 100% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
        }
        
        @keyframes textGlow {
            0% { filter: drop-shadow(0 0 5px rgba(88, 166, 255, 0.3)); }
            100% { filter: drop-shadow(0 0 15px rgba(88, 166, 255, 0.6)); }
        }
        
        .subtitle {
            color: #8b949e;
            font-size: 1.2em;
            margin-bottom: 20px;
        }
        
        .profile-stats {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-bottom: 30px;
        }
        
        .badge {
            background-color: #21262d;
            padding: 5px 10px;
            border-radius: 15px;
            font-size: 0.9em;
        }
        
        .section {
            margin: 30px 0;
        }
        
        .section h2 {
            color: #58a6ff;
            border-bottom: 2px solid #21262d;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        
        .tech-stack {
            text-align: center;
            margin: 20px 0;
        }
        
        .tech-badge {
            display: inline-block;
            margin: 5px;
            padding: 8px 16px;
            background-color: #21262d;
            border-radius: 20px;
            font-weight: bold;
            text-decoration: none;
            color: white;
            transition: transform 0.2s;
        }
        
        .tech-badge:hover {
            transform: translateY(-2px);
        }
        
        .python { background-color: #3776AB; }
        .cpp { background-color: #00599C; }
        .ros2 { background-color: #22314E; }
        .opencv { background-color: #5C3EE8; }
        .linux { background-color: #FCC624; color: black; }
        .moveit { background-color: #FF6B6B; }
        .gazebo { background-color: #4285F4; }
        
        .project {
            background-color: #21262d;
            padding: 20px;
            margin: 15px 0;
            border-radius: 10px;
            border-left: 4px solid #58a6ff;
        }
        
        .project h3 {
            color: #58a6ff;
            margin-top: 0;
        }
        
        .project-tech {
            color: #8b949e;
            font-style: italic;
            font-size: 0.9em;
        }
        
        .stats-container {
            text-align: center;
            margin: 30px 0;
        }
        
        .stats-image {
            margin: 10px;
            border-radius: 10px;
        }
        
        .what-i-do {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .skill-item {
            background-color: #21262d;
            padding: 15px;
            border-radius: 10px;
            text-align: center;
        }
        
        .connect-links {
            text-align: center;
            margin-top: 30px;
        }
        
        .connect-badge {
            display: inline-block;
            margin: 5px;
            padding: 10px 20px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            transition: transform 0.2s;
        }
        
        .connect-badge:hover {
            transform: translateY(-2px);
        }
        
        .linkedin { background-color: #0A66C2; color: white; }
        .github { background-color: #181717; color: white; }
        .email { background-color: #EA4335; color: white; }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="name-container">
                <span class="animated-emoji">🙋‍♂️</span>
                <h1 class="animated-name">Aung Kaung Myat</h1>
            </div>
            <p class="subtitle"><strong>Robotics Software Engineer | Autonomous Systems Developer</strong></p>
            <div class="profile-stats">
                <img class="badge" src="https://komarev.com/ghpvc/?username=AungKaung1928&color=blue&style=flat-square" alt="Profile views" />
                <img class="badge" src="https://img.shields.io/github/followers/AungKaung1928?style=flat-square&color=blue" alt="Followers" />
            </div>
        </div>

        <div class="section">
            <h2>💬 About Me</h2>
            <p><strong>Mechanical Engineer</strong> turned <strong>Robotics Software Developer</strong> 🔧➡️💻</p>
            <p>Building intelligent robots that navigate, perceive, and interact with the real world. Specializing in autonomous systems that actually work outside the lab.</p>
            <p><strong>Focus:</strong> Mobile Robotics • Computer Vision • SLAM • Motion Planning</p>
        </div>

        <div class="section">
            <h2>📟 Tech Stack</h2>
            <div class="tech-stack">
                <span class="tech-badge python">Python</span>
                <span class="tech-badge cpp">C++</span>
                <span class="tech-badge ros2">ROS2</span>
                <span class="tech-badge opencv">OpenCV</span>
                <span class="tech-badge linux">Linux</span>
                <span class="tech-badge moveit">MoveIt</span>
                <span class="tech-badge gazebo">Gazebo</span>
            </div>
        </div>

        <div class="section">
            <h2>📈 Active Projects</h2>
            
            <div class="project">
                <h3>🗺️ Autonomous Navigation</h3>
                <p>SLAM-based mobile robot navigation with real-time obstacle avoidance</p>
                <p class="project-tech">ROS2 • Nav2 • Python • C++ • Gazebo</p>
            </div>
            
            <div class="project">
                <h3>🦾 Smart Manipulation</h3>
                <p>AI-powered pick-and-place with computer vision integration</p>
                <p class="project-tech">MoveIt • Rviz • ROS2 • Python</p>
            </div>
            
            <div class="project">
                <h3>👁️ Object Recognition</h3>
                <p>Real-time detection and tracking for robotic perception</p>
                <p class="project-tech">OpenCV • Python • ROS2</p>
            </div>
        </div>

        <div class="section">
            <h2>📊 GitHub Stats</h2>
            <div class="stats-container">
                <img class="stats-image" height="180" src="https://github-readme-stats.vercel.app/api?username=AungKaung1928&show_icons=true&theme=github_dark&hide_border=true&title_color=58a6ff&icon_color=58a6ff" />
                <img class="stats-image" height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AungKaung1928&layout=compact&theme=github_dark&hide_border=true&title_color=58a6ff" />
            </div>
        </div>

        <div class="section">
            <h2>🧑‍🚀 What I Do</h2>
            <div class="what-i-do">
                <div class="skill-item">
                    <strong>🤖 Autonomous Systems</strong><br>
                    Making robots think and move independently
                </div>
                <div class="skill-item">
                    <strong>🔍 Computer Vision</strong><br>
                    Teaching machines to see and understand
                </div>
                <div class="skill-item">
                    <strong>🎮 Motion Planning</strong><br>
                    Smooth, collision-free robot movements
                </div>
            </div>
        </div>

        <div class="section">
            <h2>🤝 Let's Connect</h2>
            <div class="connect-links">
                <a href="https://www.linkedin.com/in/aung-kaung-myat-30943a215/" class="connect-badge linkedin">LinkedIn</a>
                <a href="https://github.com/AungKaung1928" class="connect-badge github">GitHub</a>
                <a href="mailto:aungkaungmyattt1928@gmail.com" class="connect-badge email">Email</a>
            </div>
        </div>
    </div>
</body>
</html>
