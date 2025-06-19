<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hazel | AOV Master Player (x15 Stars)</title>
    <meta name="description" content="Professional Arena of Valor player - Master rank x15 stars">
    <style>
        :root {
            --bg-color: #0f172a;
            --text-color: #f8fafc;
            --primary-color: #f43f5e;
            --secondary-color: #94a3b8;
            --accent-color: #7c3aed;
            --border-color: #1e293b;
        }

        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            max-width: 800px;
            margin: 0 auto;
            padding: 0 2rem;
            line-height: 1.6;
            min-height: 100vh;
        }

        header {
            text-align: center;
            margin: 3rem 0 2rem;
        }

        .avatar {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid var(--primary-color);
            box-shadow: 0 4px 20px rgba(244, 63, 94, 0.3);
            margin: 0 auto;
            display: block;
            transition: all 0.3s ease;
        }

        .avatar:hover {
            transform: scale(1.05) rotate(5deg);
            box-shadow: 0 6px 25px rgba(244, 63, 94, 0.4);
        }

        h1 {
            font-size: 2.5rem;
            margin: 1.5rem 0 0.5rem;
            color: var(--primary-color);
            text-shadow: 0 2px 4px rgba(0,0,0,0.2);
        }

        .rank-badge {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            background: rgba(124, 58, 237, 0.2);
            padding: 0.5rem 1rem;
            border-radius: 50px;
            font-weight: 600;
            margin-top: 0.5rem;
        }

        .rank-badge::before {
            content: "★";
            color: gold;
        }

        nav {
            margin: 2rem 0;
        }

        nav ul {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            list-style: none;
            padding: 0;
            flex-wrap: wrap;
        }

        nav a {
            color: var(--text-color);
            text-decoration: none;
            font-weight: 600;
            padding: 0.7rem 1.5rem;
            border-radius: 50px;
            transition: all 0.3s ease;
            background: rgba(148, 163, 184, 0.1);
        }

        nav a:hover {
            background: rgba(244, 63, 94, 0.3);
            color: white;
            transform: translateY(-2px);
        }

        section {
            margin: 3rem 0;
        }

        h2 {
            font-size: 2rem;
            color: var(--primary-color);
            border-bottom: 2px solid var(--border-color);
            padding-bottom: 0.7rem;
            margin-bottom: 2rem;
            text-align: center;
        }

        .card {
            background: rgba(30, 41, 59, 0.6);
            border-radius: 16px;
            padding: 2rem;
            margin-bottom: 2rem;
            border: 1px solid var(--border-color);
            transition: all 0.4s ease;
            backdrop-filter: blur(5px);
        }

        .card:hover {
            transform: translateY(-8px);
            border-color: var(--primary-color);
            box-shadow: 0 10px 25px rgba(15, 23, 42, 0.5);
        }

        .card-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 1.2rem;
        }

        .card-title {
            font-size: 1.4rem;
            font-weight: 700;
            color: var(--accent-color);
        }

        .card-date {
            color: var(--secondary-color);
            font-size: 0.95rem;
        }

        .btn {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            background: var(--primary-color);
            color: white;
            padding: 0.8rem 1.5rem;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            margin-top: 1rem;
            transition: all 0.3s ease;
        }

        .btn:hover {
            background: #e11d48;
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(244, 63, 94, 0.4);
            gap: 12px;
        }

        footer {
            text-align: center;
            margin: 5rem 0 2rem;
            color: var(--secondary-color);
            font-size: 0.95rem;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            margin: 2rem 0;
            flex-wrap: wrap;
        }

        .social-links a {
            color: var(--text-color);
            text-decoration: none;
            padding: 0.8rem 1.2rem;
            border-radius: 50px;
            background: rgba(148, 163, 184, 0.1);
            transition: all 0.3s ease;
            display: inline-flex;
            align-items: center;
            gap: 8px;
        }

        .social-links a:hover {
            background: rgba(244, 63, 94, 0.3);
            transform: translateY(-3px);
        }

        @media (max-width: 768px) {
            body {
                padding: 0 1.2rem;
            }
            
            .avatar {
                width: 150px;
                height: 150px;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            nav ul {
                gap: 0.8rem;
            }
            
            nav a {
                padding: 0.6rem 1rem;
                font-size: 0.9rem;
            }
            
            .card {
                padding: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <img src="https://www.pinterest.com/pin/140526450868718975/" alt="Hazel Avatar" class="avatar">
        <h1>Hazel</h1>
        <div>Arena of Valor Master Player</div>
        <div class="rank-badge">Master x15 Stars</div>
        
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#highlights">Highlights</a></li>
                <li><a href="#guides">Guides</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <div class="card">
                <p>Hello! I'm Hazel (Hoang Quan), a professional Arena of Valor player from Vietnam specializing in Jungle and Mid Lane roles.</p>
                <p>Currently ranked Master x15 stars, I'm passionate about competitive gameplay and sharing advanced strategies with the AOV community through tutorials and live streams.</p>
                <a href="#contact" class="btn">Connect With Me</a>
            </div>
        </section>

        <section id="highlights">
            <h2>Recent Highlights</h2>
            
            <div class="card">
                <div class="card-header">
                    <span class="card-title">Master x15 Stars Achievement</span>
                    <span class="card-date">Current Season</span>
                </div>
                <p>Reached Master rank with 15 stars this season with an 82% win rate using my signature hero builds and strategies.</p>
                <a href="#" class="btn">Watch Highlights</a>
            </div>

        <section id="guides">
            <h2>Game Guides</h2>
            
            <div class="card">
                <div class="card-header">
                    <span class="card-title">Jungle Path Optimization</span>
                    <span class="card-date">April 2024</span>
                </div>
                <p>Complete guide to maximizing jungle efficiency with timing maps for each jungle hero and adaptation strategies against enemy team compositions.</p>
                <a href="#" class="btn">Read Guide</a>
            </div>
            
            <div class="card">
                <div class="card-header">
                    <span class="card-title">Master-Level Counter Building</span>
                    <span class="card-date">March 2024</span>
                </div>
                <p>Advanced item build adjustments to counter specific enemy team compositions and hero matchups at Master rank level.</p>
                <a href="#" class="btn">Read Guide</a>
            </div>
        </section>

        <section id="contact">
            <h2>Connect</h2>
            <div class="card">
                <p>For collaborations, coaching sessions, or just to play together:</p>
                
                <div class="social-links">
                    <a href="https://youtube.com" target="_blank">YouTube</a>
                    <a href="https://www.facebook.com/hoang.quan.580624/" target="_blank">Facebook</a>
                    <a href="https://x.com/QuanHoang920212" target="_blank">Twitch</a>
                    <a href="https://discord.com" target="_blank">Discord</a>
                </div>
                
                <p>Email: <a href="mailto:hoangmanhquan141012@gmail.com" style="color: var(--primary-color);">hoangmanhquan141012@gmail.com</a></p>
            </div>
        </section>
    </main>

    <footer>
        <p>© 2024 Hazel - Arena of Valor Master Player (x15 Stars)</p>
        <p>hazel-aov.dev</p>
    </footer>
</body>
</html>
