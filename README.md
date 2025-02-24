<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Marketing Hub</title>
    <style>
        /* Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: #f0f2f5;
            line-height: 1.6;
        }

        /* Navigation */
        .navbar {
            background: #1a73e8;
            padding: 1rem 2rem;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        .nav-links {
            display: flex;
            gap: 2rem;
            list-style: none;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: opacity 0.3s;
        }

        .nav-links a:hover {
            opacity: 0.8;
        }

        /* Main Content Sections */
        .section {
            padding: 6rem 2rem 2rem;
            min-height: 100vh;
        }

        /* Hero Section */
        #hero {
            background: linear-gradient(135deg, #1a73e8, #0d47a1);
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            text-align: center;
        }

        .hero-title {
            font-size: 3.5rem;
            margin-bottom: 1.5rem;
        }

        /* Strategies Grid */
        .strategies-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .strategy-card {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .strategy-card h3 {
            color: #1a73e8;
            margin-bottom: 1rem;
        }

        .strategy-list {
            list-style: none;
            margin-bottom: 1.5rem;
        }

        .strategy-list li {
            padding: 0.5rem 0;
            border-bottom: 1px solid #eee;
        }

        /* Timeline Section */
        .timeline {
            position: relative;
            max-width: 800px;
            margin: 4rem auto;
        }

        .timeline-item {
            position: relative;
            padding-left: 120px;
            margin-bottom: 3rem;
        }

        .timeline-year {
            position: absolute;
            left: 0;
            top: 0;
            font-weight: bold;
            color: #1a73e8;
        }

        .timeline-content {
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
        }

        /* Interactive Elements */
        .view-more {
            display: inline-block;
            padding: 0.5rem 1rem;
            background: #1a73e8;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: transform 0.2s;
        }

        .view-more:hover {
            transform: translateY(-2px);
        }

        /* Footer */
        footer {
            background: #1a73e8;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <ul class="nav-links">
            <li><a href="#hero">Home</a></li>
            <li><a href="#strategies">Strategies</a></li>
            <li><a href="#history">History</a></li>
        </ul>
    </nav>

    <section id="hero" class="section">
        <h1 class="hero-title">Digital Marketing !!</h1>
        <p>Using online channels to promote products, engage consumers, and optimize campaigns for better performance.</p>
        <a href="#strategies" class="view-more" style="margin-top: 2rem;">View more >></a>
    </section>

    <section id="strategies" class="section">
        <div class="strategies-grid">
            <div class="strategy-card">
                <h3>SEO</h3>
                <ul class="strategy-list">
                    <li>Optimize website</li>
                    <li>Increase organic traffic</li>
                    <li>Improve UI/UX</li>
                    <li>Competitive analysis</li>
                    <li>Qualified leads</li>
                    <li>Targeted keywords</li>
                </ul>
                <a href="#" class="view-more">View more >></a>
            </div>

            <div class="strategy-card">
                <h3>Landing Page</h3>
                <ul class="strategy-list">
                    <li>Engaging content</li>
                    <li>Optimized layout</li>
                    <li>Clear message</li>
                    <li>Personalized experience</li>
                    <li>In-depth structure</li>
                </ul>
                <a href="#" class="view-more">View more >></a>
            </div>

            <div class="strategy-card">
                <h3>SM Management</h3>
                <ul class="strategy-list">
                    <li>Content Creation</li>
                    <li>Scheduling and Posting</li>
                    <li>Audience Engagement</li>
                    <li>Analytics and Reporting</li>
                    <li>Strategy Development</li>
                </ul>
                <a href="#" class="view-more">View more >></a>
            </div>
        </div>
    </section>

    <section id="history" class="section">
        <div class="timeline">
            <div class="timeline-item">
                <span class="timeline-year">1980</span>
                <div class="timeline-content">
                    <p>Ettore Sottsass coins Memphis design style</p>
                </div>
            </div>
            
            <div class="timeline-item">
                <span class="timeline-year">2015</span>
                <div class="timeline-content">
                    <p>Revival of Memphis designs influences digital aesthetics</p>
                </div>
            </div>

            <div class="timeline-item">
                <span class="timeline-year">2016</span>
                <div class="timeline-content">
                    <p>Largest collection auction inspires modern UI trends</p>
                </div>
            </div>

            <div class="timeline-item">
                <span class="timeline-year">Present</span>
                <div class="timeline-content">
                    <p>Memphis-inspired elements in contemporary web design</p>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 Digital Marketing Hub. All rights reserved.</p>
    </footer>
</body>
</html>
