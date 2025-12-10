<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ansh Tiwari</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            background: #0a0a0a;
            color: #e4e4e7;
            line-height: 1.6;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 2rem;
        }

        .container {
            max-width: 800px;
            width: 100%;
        }

        header {
            text-align: center;
            margin-bottom: 3rem;
            padding-bottom: 2rem;
            border-bottom: 1px solid #27272a;
        }

        h1 {
            font-size: 3rem;
            font-weight: 700;
            margin-bottom: 0.5rem;
            background: linear-gradient(135deg, #ffffff 0%, #a1a1aa 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .subtitle {
            font-size: 1.125rem;
            color: #a1a1aa;
            margin-bottom: 1rem;
        }

        .tagline {
            font-size: 0.95rem;
            color: #71717a;
            margin-bottom: 1.5rem;
        }

        .links {
            display: flex;
            gap: 1.5rem;
            justify-content: center;
            flex-wrap: wrap;
        }

        .links a {
            color: #a1a1aa;
            text-decoration: none;
            font-size: 0.9rem;
            transition: color 0.2s;
            display: flex;
            align-items: center;
            gap: 0.4rem;
        }

        .links a:hover {
            color: #ffffff;
        }

        .about {
            margin-bottom: 3rem;
            text-align: center;
        }

        .about p {
            color: #d4d4d8;
            font-size: 1rem;
            line-height: 1.7;
            max-width: 600px;
            margin: 0 auto;
        }

        .section {
            margin-bottom: 3rem;
        }

        h2 {
            font-size: 1.5rem;
            margin-bottom: 1.5rem;
            color: #fafafa;
            font-weight: 600;
            text-align: center;
        }

        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
            gap: 1rem;
            margin-bottom: 2rem;
        }

        .tech-item {
            background: #18181b;
            padding: 0.75rem;
            border-radius: 8px;
            text-align: center;
            font-size: 0.875rem;
            color: #d4d4d8;
            border: 1px solid #27272a;
            transition: all 0.2s;
        }

        .tech-item:hover {
            border-color: #52525b;
            transform: translateY(-2px);
        }

        .interests {
            display: flex;
            gap: 2rem;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 2rem;
            padding-top: 2rem;
            border-top: 1px solid #27272a;
        }

        .interest-item {
            text-align: center;
            color: #a1a1aa;
            font-size: 0.9rem;
        }

        .interest-item span {
            display: block;
            font-size: 1.5rem;
            margin-bottom: 0.3rem;
        }

        footer {
            text-align: center;
            padding-top: 2rem;
            border-top: 1px solid #27272a;
            color: #71717a;
            font-size: 0.85rem;
        }

        @media (max-width: 640px) {
            h1 {
                font-size: 2rem;
            }

            .tech-grid {
                grid-template-columns: repeat(auto-fit, minmax(80px, 1fr));
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Ansh Tiwari</h1>
            <p class="subtitle">CS Student @ Simon Fraser University</p>
            <p class="tagline">Full Stack Dev • Systems Programming • Esports Analytics</p>
            <div class="links">
                <a href="https://linkedin.com/in/ansh-tiwari" target="_blank">
                    <span>→</span> LinkedIn
                </a>
                <a href="mailto:ata185@sfu.ca">
                    <span>→</span> Email
                </a>
                <a href="https://github.com/CandyRagi" target="_blank">
                    <span>→</span> GitHub
                </a>
            </div>
        </header>

        <div class="about">
            <p>
                I am a 3rd-year Computing Science student passionate about <strong>AI/ML integration</strong>, 
                <strong>System Architecture</strong>, and <strong>UI/UX Design</strong>. Currently building 
                <strong>StudySage</strong> and competing in the <strong>VAL Challengers (NECC)</strong>.
            </p>
        </div>

        <section class="section">
            <h2>Technical Skills</h2>
            <div class="tech-grid">
                <div class="tech-item">C</div>
                <div class="tech-item">C++</div>
                <div class="tech-item">Java</div>
                <div class="tech-item">Python</div>
                <div class="tech-item">TypeScript</div>
                <div class="tech-item">JavaScript</div>
                <div class="tech-item">React</div>
                <div class="tech-item">Spring</div>
                <div class="tech-item">Node.js</div>
                <div class="tech-item">Express</div>
                <div class="tech-item">PostgreSQL</div>
                <div class="tech-item">MongoDB</div>
                <div class="tech-item">Docker</div>
                <div class="tech-item">Git</div>
                <div class="tech-item">Linux</div>
            </div>
        </section>

        <div class="interests">
            <div class="interest-item">
                <span>🐧</span>
                <div>Fedora KDE Plasma</div>
            </div>
            <div class="interest-item">
                <span>🔭</span>
                <div>Android & Embedded</div>
            </div>
            <div class="interest-item">
                <span>⚽</span>
                <div>Yapping & Food</div>
            </div>
        </div>

        <footer>
            <p>Burnaby, BC • Open to opportunities</p>
        </footer>
    </div>
</body>
</html>
