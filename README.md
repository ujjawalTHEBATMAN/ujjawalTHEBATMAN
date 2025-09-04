<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ujjawal Vishwakarma - Backend Developer</title>
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
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .container {
            background: linear-gradient(135deg, #161b22 0%, #0d1117 100%);
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            overflow: hidden;
            border: 1px solid #30363d;
        }
        
        header {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(135deg, #8A2BE2 0%, #4B0082 100%);
            color: white;
            position: relative;
        }
        
        .header-content {
            max-width: 800px;
            margin: 0 auto;
        }
        
        h1 {
            font-size: 3.5rem;
            margin-bottom: 15px;
            background: linear-gradient(45deg, #ffffff, #e0e0ff);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 2px 10px rgba(255, 255, 255, 0.2);
        }
        
        .title {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: #d0bcff;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
            margin: 30px 0;
        }
        
        .social-btn {
            display: inline-flex;
            align-items: center;
            padding: 12px 25px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 50px;
            color: white;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        .social-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(138, 43, 226, 0.4);
            background: rgba(138, 43, 226, 0.2);
        }
        
        .stats {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 20px 0;
        }
        
        .stat-item {
            background: rgba(255, 255, 255, 0.05);
            padding: 10px 20px;
            border-radius: 8px;
            font-size: 0.9rem;
        }
        
        section {
            padding: 40px;
            border-bottom: 1px solid #21262d;
        }
        
        h2 {
            font-size: 2.2rem;
            margin-bottom: 25px;
            color: #8A2BE2;
            display: flex;
            align-items: center;
        }
        
        h2::after {
            content: "";
            flex: 1;
            height: 2px;
            margin-left: 15px;
            background: linear-gradient(90deg, #8A2BE2, transparent);
        }
        
        h3 {
            font-size: 1.5rem;
            margin: 25px 0 15px;
            color: #d0bcff;
        }
        
        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
        }
        
        @media (max-width: 768px) {
            .about-content {
                grid-template-columns: 1fr;
            }
        }
        
        .competency-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .competency-item {
            background: linear-gradient(145deg, #161b22, #1a202a);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            border: 1px solid #30363d;
            transition: transform 0.3s ease;
        }
        
        .competency-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(138, 43, 226, 0.3);
        }
        
        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(120px, 1fr));
            gap: 15px;
            margin: 20px 0;
        }
        
        .tech-item {
            background: rgba(138, 43, 226, 0.1);
            padding: 15px 10px;
            border-radius: 8px;
            text-align: center;
            font-weight: 600;
            border: 1px solid rgba(138, 43, 226, 0.3);
        }
        
        .exploring-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .exploring-item {
            background: linear-gradient(145deg, #1c2129, #171c24);
            padding: 20px;
            border-radius: 10px;
            border-left: 4px solid #8A2BE2;
        }
        
        footer {
            text-align: center;
            padding: 40px;
            background: linear-gradient(135deg, #4B0082 0%, #8A2BE2 100%);
            color: white;
        }
        
        .quote {
            font-style: italic;
            margin: 20px 0;
            color: #d0bcff;
            text-align: center;
            font-size: 1.2rem;
        }
        
        .badge {
            display: inline-block;
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 600;
            margin: 5px;
            background: rgba(138, 43, 226, 0.2);
            border: 1px solid rgba(138, 43, 226, 0.4);
        }
        
        .icon {
            margin-right: 10px;
            font-size: 1.2rem;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="header-content">
                <h1>Ujjawal Vishwakarma</h1>
                <div class="title">Backend Developer | Java & Spring Specialist</div>
                <div class="social-links">
                    <a href="https://www.linkedin.com/in/ujjawal-vishwakarma-aba5b6303/" class="social-btn">
                        <span class="icon">📱</span> LinkedIn
                    </a>
                    <a href="https://github.com/ujjawalTHEBATMAN" class="social-btn">
                        <span class="icon">🐙</span> GitHub
                    </a>
                    <a href="https://leetcode.com/ujjawalMvishwakarma/" class="social-btn">
                        <span class="icon">⚡</span> LeetCode
                    </a>
                    <a href="mailto:ujjawal.vishwakarma.dev@gmail.com" class="social-btn">
                        <span class="icon">✉️</span> Email
                    </a>
                </div>
                <div class="stats">
                    <div class="stat-item">📊 Profile Views: 1,240</div>
                    <div class="stat-item">👥 Followers: 86</div>
                </div>
            </div>
        </header>
        
        <section id="about">
            <h2>About Me</h2>
            <div class="about-content">
                <div>
                    <p>I'm a passionate backend developer from India specializing in Java and the Spring ecosystem. My expertise lies in architecting robust, scalable, and resilient distributed systems with a focus on microservices architecture and high-performance applications.</p>
                    <p class="quote">"The best code is the code that is never written - but when written, it should be elegant, efficient, and maintainable."</p>
                </div>
                <div>
                    <h3>Core Competencies</h3>
                    <div class="competency-grid">
                        <div class="competency-item">
                            <strong>Backend Development</strong>
                            <div>Java, Spring Boot, Spring Cloud, Microservices</div>
                        </div>
                        <div class="competency-item">
                            <strong>Message Brokers</strong>
                            <div>Kafka, RabbitMQ</div>
                        </div>
                        <div class="competency-item">
                            <strong>Databases & Caching</strong>
                            <div>PostgreSQL, MySQL, MongoDB, Redis</div>
                        </div>
                        <div class="competency-item">
                            <strong>DevOps & Cloud</strong>
                            <div>Docker, Kubernetes, Jenkins, AWS</div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="technologies">
            <h2>Technical Arsenal</h2>
            
            <h3>Languages & Core Technologies</h3>
            <div class="tech-grid">
                <div class="tech-item">Java</div>
                <div class="tech-item">Spring</div>
                <div class="tech-item">Kafka</div>
                <div class="tech-item">Maven</div>
                <div class="tech-item">Git</div>
            </div>
            
            <h3>Frontend & Web Technologies</h3>
            <div class="tech-grid">
                <div class="tech-item">JavaScript</div>
                <div class="tech-item">HTML5</div>
                <div class="tech-item">CSS3</div>
                <div class="tech-item">React</div>
                <div class="tech-item">Bootstrap</div>
            </div>
            
            <h3>Databases & Caching</h3>
            <div class="tech-grid">
                <div class="tech-item">PostgreSQL</div>
                <div class="tech-item">MySQL</div>
                <div class="tech-item">Redis</div>
                <div class="tech-item">MongoDB</div>
            </div>
            
            <h3>DevOps & Tools</h3>
            <div class="tech-grid">
                <div class="tech-item">Docker</div>
                <div class="tech-item">Kubernetes</div>
                <div class="tech-item">Jenkins</div>
                <div class="tech-item">Postman</div>
                <div class="tech-item">IntelliJ</div>
                <div class="tech-item">Linux</div>
            </div>
        </section>
        
        <section id="exploring">
            <h2>Currently Exploring</h2>
            <div class="exploring-grid">
                <div class="exploring-item">
                    <h3>Advanced Cloud-Native Technologies</h3>
                    <p>Deep diving into Kubernetes & Istio for container orchestration and service mesh implementations.</p>
                </div>
                <div class="exploring-item">
                    <h3>Event-Driven Architecture</h3>
                    <p>Exploring patterns for building scalable and resilient event-driven systems.</p>
                </div>
                <div class="exploring-item">
                    <h3>Performance Optimization</h3>
                    <p>Advanced techniques for optimizing application performance and resource utilization.</p>
                </div>
                <div class="exploring-item">
                    <h3>System Design Principles</h3>
                    <p>Mastering advanced system design concepts for large-scale distributed systems.</p>
                </div>
            </div>
        </section>
        
        <section id="contact">
            <h2>Let's Connect</h2>
            <p>I'm always interested in discussing backend development, system architecture, and new opportunities.</p>
            <div class="social-links">
                <a href="https://www.linkedin.com/in/ujjawal-vishwakarma-aba5b6303/" class="social-btn">
                    <span class="icon">💼</span> LinkedIn
                </a>
                <a href="mailto:ujjawal.vishwakarma.dev@gmail.com" class="social-btn">
                    <span class="icon">📧</span> Email
                </a>
                <a href="https://github.com/ujjawalTHEBATMAN" class="social-btn">
                    <span class="icon">🐱</span> GitHub
                </a>
            </div>
        </section>
        
        <footer>
            <p>Thanks for visiting my profile!</p>
            <p>© 2025 Ujjawal Vishwakarma | Backend Developer</p>
        </footer>
    </div>
</body>
</html>
