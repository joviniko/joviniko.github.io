---
title: About
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - Niko</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #e0e0e0;
            background: linear-gradient(135deg, #0f1419 0%, #1a1f2e 100%);
            min-height: 100vh;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background: rgba(15, 20, 25, 0.95);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid rgba(99, 179, 237, 0.1);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1.5rem 0;
        }
        
        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            color: #63b3ed;
            letter-spacing: -0.5px;
        }
        
        .nav-links {
            display: flex;
            gap: 2rem;
            list-style: none;
        }
        
        .nav-links a {
            color: #a0aec0;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        .nav-links a:hover {
            color: #63b3ed;
        }
        
        .content {
            padding: 150px 0 100px;
            max-width: 800px;
            margin: 0 auto;
        }
        
        h1 {
            font-size: 3rem;
            font-weight: 800;
            margin-bottom: 2rem;
            background: linear-gradient(135deg, #63b3ed 0%, #4299e1 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        h2 {
            font-size: 1.75rem;
            color: #f7fafc;
            margin: 2rem 0 1rem;
        }
        
        p {
            color: #a0aec0;
            margin-bottom: 1.5rem;
            font-size: 1.1rem;
        }
        
        .highlight {
            background: rgba(99, 179, 237, 0.1);
            border-left: 3px solid #63b3ed;
            padding: 1.5rem;
            border-radius: 4px;
            margin: 2rem 0;
        }
        
        footer {
            background: rgba(15, 20, 25, 0.95);
            border-top: 1px solid rgba(99, 179, 237, 0.1);
            padding: 2rem 0;
            text-align: center;
            color: #718096;
            margin-top: 4rem;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <div class="logo">Niko</div>
                <ul class="nav-links">
                    <li><a href="/">Home</a></li>
                    <li><a href="/about.html">About</a></li>
                    <li><a href="https://github.com/joviniko" target="_blank">GitHub</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <main>
        <div class="container">
            <div class="content">
                <h1>About</h1>
                
                <p>
                    I'm Niko, a software developer focused on building efficient, scalable solutions.
                </p>
                
                <div class="highlight">
                    <p style="margin-bottom: 0; font-weight: 500;">
                        Passionate about clean code, system architecture, and solving complex technical challenges.
                    </p>
                </div>
                
                <h2>Approach</h2>
                <p>
                    I believe in writing maintainable code, continuous learning, and delivering value through technology.
                </p>
                
                <h2>Contact</h2>
                <p>
                    Feel free to reach out via <a href="https://github.com/joviniko" style="color: #63b3ed; text-decoration: none;">GitHub</a>.
                </p>
            </div>
        </div>
    </main>
    
    <footer>
        <div class="container">
            <p>&copy; 2026 Niko. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
