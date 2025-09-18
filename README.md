<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohamed - Full Stack Developer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
            padding: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .container {
            background-color: #161b22;
            border-radius: 12px;
            padding: 2.5rem;
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.2);
            border: 1px solid #30363d;
        }
        
        header {
            text-align: center;
            margin-bottom: 2.5rem;
            padding-bottom: 2rem;
            border-bottom: 1px solid #30363d;
        }
        
        h1 {
            color: #58a6ff;
            font-size: 2.8rem;
            margin-bottom: 0.5rem;
        }
        
        .tagline {
            font-size: 1.4rem;
            color: #8b949e;
            margin-bottom: 1.5rem;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            margin-top: 1.5rem;
        }
        
        .social-links a {
            color: #58a6ff;
            text-decoration: none;
            transition: color 0.3s;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .social-links a:hover {
            color: #79c0ff;
            text-decoration: underline;
        }
        
        section {
            margin-bottom: 2.5rem;
        }
        
        h2 {
            color: #58a6ff;
            font-size: 1.8rem;
            margin-bottom: 1.2rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid #30363d;
        }
        
        h3 {
            color: #f78166;
            font-size: 1.4rem;
            margin: 1.2rem 0 0.8rem 0;
        }
        
        p {
            margin-bottom: 1rem;
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }
        
        .skill-category {
            background-color: #21262d;
            padding: 1.2rem;
            border-radius: 8px;
            border: 1px solid #30363d;
        }
        
        .tech-list {
            display: flex;
            flex-wrap: wrap;
            gap: 0.8rem;
            margin-top: 0.8rem;
        }
        
        .tech-item {
            background-color: #30363d;
            color: #c9d1d9;
            padding: 0.4rem 0.8rem;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }
        
        .project-card {
            background-color: #21262d;
            border-radius: 8px;
            padding: 1.5rem;
            border: 1px solid #30363d;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
            border-color: #58a6ff;
        }
        
        .project-title {
            color: #58a6ff;
            font-size: 1.2rem;
            margin-bottom: 0.8rem;
        }
        
        .project-links {
            display: flex;
            gap: 1rem;
            margin-top: 1rem;
        }
        
        .project-links a {
            color: #8b949e;
            text-decoration: none;
            font-size: 0.9rem;
            display: flex;
            align-items: center;
            gap: 0.3rem;
        }
        
        .project-links a:hover {
            color: #58a6ff;
        }
        
        .hobbies-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }
        
        .hobby-card {
            background-color: #21262d;
            border-radius: 8px;
            padding: 1.5rem;
            text-align: center;
            border: 1px solid #30363d;
        }
        
        .hobby-icon {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        
        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }
        
        .stat-card {
            background-color: #21262d;
            border-radius: 8px;
            padding: 1.5rem;
            text-align: center;
            border: 1px solid #30363d;
        }
        
        .stat-number {
            font-size: 2.2rem;
            font-weight: bold;
            color: #58a6ff;
            margin-bottom: 0.5rem;
        }
        
        .quote {
            font-style: italic;
            text-align: center;
            margin: 2rem 0;
            padding: 1.5rem;
            background-color: #21262d;
            border-radius: 8px;
            border-left: 4px solid #f78166;
        }
        
        @media (max-width: 768px) {
            body {
                padding: 1rem;
            }
            
            .container {
                padding: 1.5rem;
            }
            
            h1 {
                font-size: 2.2rem;
            }
            
            .tagline {
                font-size: 1.2rem;
            }
            
            .skills-grid, .projects-grid, .hobbies-grid, .stats {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Mohamed</h1>
            <p class="tagline">Full Stack Web Developer | Angular & Laravel Specialist</p>
            <p>Crafting beautiful, functional, and user-centered digital experiences</p>
            <div class="social-links">
                <a href="https://github.com/mohamed-2473" target="_blank">GitHub</a>
                <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
                <a href="https://twitter.com/yourprofile" target="_blank">Twitter</a>
                <a href="mailto:your.email@example.com">Email</a>
            </div>
        </header>

        <section id="about">
            <h2>About Me</h2>
            <p>I'm a passionate full-stack developer with expertise in creating dynamic, responsive web applications. With a strong foundation in both frontend and backend technologies, I specialize in building seamless user experiences with robust functionality.</p>
            <p>My tech journey began several years ago, and I've since developed a deep appreciation for clean code, efficient architecture, and continuous learning. I enjoy solving complex problems and turning ideas into reality through code.</p>
        </section>

        <section id="skills">
            <h2>Technical Skills</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <h3>Frontend Development</h3>
                    <div class="tech-list">
                        <span class="tech-item">Angular</span>
                        <span class="tech-item">React</span>
                        <span class="tech-item">TypeScript</span>
                        <span class="tech-item">JavaScript</span>
                        <span class="tech-item">HTML5</span>
                        <span class="tech-item">CSS3</span>
                        <span class="tech-item">Tailwind CSS</span>
                        <span class="tech-item">Bootstrap</span>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3>Backend Development</h3>
                    <div class="tech-list">
                        <span class="tech-item">Laravel</span>
                        <span class="tech-item">PHP</span>
                        <span class="tech-item">Node.js</span>
                        <span class="tech-item">Express</span>
                        <span class="tech-item">MySQL</span>
                        <span class="tech-item">RESTful APIs</span>
                        <span class="tech-item">Authentication</span>
                        <span class="tech-item">API Integration</span>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3>Tools & Practices</h3>
                    <div class="tech-list">
                        <span class="tech-item">Git</span>
                        <span class="tech-item">GitHub</span>
                        <span class="tech-item">Docker</span>
                        <span class="tech-item">VS Code</span>
                        <span class="tech-item">Responsive Design</span>
                        <span class="tech-item">Agile Methodology</span>
                        <span class="tech-item">Testing & Debugging</span>
                    </div>
                </div>
            </div>
        </section>

        <section id="projects">
            <h2>Featured Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3 class="project-title">E-Commerce</h3>
                    <p>Online store with user authentication, product catalog, shopping cart, and checkout functionality.</p>
                    <div class="project-links">
                        <a href="https://github.com/mohamed-2473/e-commerce" target="_blank">View Code</a>
                        <a href="https://e-commerce-delta-two-15.vercel.app/home" target="_blank">Live Demo</a>
                    </div>
                </div>
                
                <div class="project-card">
                    <h3 class="project-title">Daily Wisdom</h3>
                    <p>A motivational quotes application that provides daily inspirational wisdom with beautiful animations and responsive design.</p>
                    <div class="project-links">
                        <a href="https://github.com/mohamed-2473/daily-wisdom" target="_blank">View Code</a>
                        <a href="https://mohamed-2473.github.io/daily-wisdom/" target="_blank">Live Demo</a>
                    </div>
                </div>
                
                <div class="project-card">
                    <h3 class="project-title">TaskFlow Productivity</h3>
                    <p>Advanced task management system with project organization and progress tracking features.</p>
                    <div class="project-links">
                        <a href="https://github.com/mohamed-2473/taskflow" target="_blank">View Code</a>
                        <a href="https://mohamed-2473.github.io/taskflow/" target="_blank">Live Demo</a>
                    </div>
                </div>
            </div>
        </section>

        <section id="hobbies">
            <h2>Hobbies & Interests</h2>
            <div class="hobbies-grid">
                <div class="hobby-card">
                    <div class="hobby-icon">📚</div>
                    <h3>Reading</h3>
                    <p>I enjoy reading tech blogs, programming books, and occasionally fiction to expand my knowledge and creativity.</p>
                </div>
                
                <div class="hobby-card">
                    <div class="hobby-icon">♟️</div>
                    <h3>Chess</h3>
                    <p>I'm an avid chess player who enjoys strategic thinking and the mental challenge the game provides.</p>
                </div>
                
                <div class="hobby-card">
                    <div class="hobby-icon">🌱</div>
                    <h3>Gardening</h3>
                    <p>Growing plants and vegetables is my way of connecting with nature and practicing patience.</p>
                </div>
                
                <div class="hobby-card">
                    <div class="hobby-icon">✈️</div>
                    <h3>Traveling</h3>
                    <p>Exploring new places and cultures helps me gain perspective and inspiration for my creative work.</p>
                </div>
            </div>
        </section>

        <section id="stats">
            <h2>GitHub Statistics</h2>
            <div class="stats">
                <div class="stat-card">
                    <div class="stat-number">20+</div>
                    <p>Projects Completed</p>
                </div>
                
                <div class="stat-card">
                    <div class="stat-number">15k+</div>
                    <p>Lines of Code</p>
                </div>
                
                <div class="stat-card">
                    <div class="stat-number">100+</div>
                    <p>Commits This Year</p>
                </div>
                
                <div class="stat-card">
                    <div class="stat-number">5</div>
                    <p>Technologies Mastered</p>
                </div>
            </div>
        </section>

        <div class="quote">
            <p>"First, solve the problem. Then, write the code." - John Johnson</p>
        </div>

        <section id="contact">
            <h2>Get In Touch</h2>
            <p>I'm always open to discussing new projects, creative ideas, or opportunities to be part of your vision. Feel free to reach out to me through any of the social links above.</p>
        </section>
    </div>
</body>
</html>
