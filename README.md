<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Stock Sense Ai Assistant README</title>

<!-- Font Awesome Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        background: #0f172a;
        color: #e2e8f0;
    }

    header {
        background: linear-gradient(90deg, #1e3a8a, #0ea5e9);
        padding: 30px;
        text-align: center;
    }

    header h1 {
        margin: 0;
        font-size: 32px;
    }

    header p {
        margin-top: 10px;
        color: #cbd5e1;
    }

    .container {
        padding: 20px;
        max-width: 1100px;
        margin: auto;
    }

    .card {
        background: #1e293b;
        padding: 20px;
        margin: 15px 0;
        border-radius: 12px;
        box-shadow: 0 4px 10px rgba(0,0,0,0.3);
        transition: 0.3s;
    }

    .card:hover {
        transform: scale(1.02);
    }

    .grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
        gap: 15px;
    }

    .feature {
        text-align: center;
        padding: 15px;
        background: #0b1220;
        border-radius: 10px;
    }

    .feature i {
        font-size: 30px;
        color: #38bdf8;
        margin-bottom: 10px;
    }

    .badge {
        display: inline-block;
        padding: 5px 10px;
        border-radius: 20px;
        background: #2563eb;
        margin: 5px;
        font-size: 12px;
    }

    footer {
        text-align: center;
        padding: 20px;
        color: #94a3b8;
    }

    a {
        color: #38bdf8;
        text-decoration: none;
    }

</style>
</head>
<body>

<header>
    <h1><i class="fas fa-chart-line"></i> Stock DS Project</h1>
    <p>Interactive Data Science & Machine Learning Dashboard (Streamlit)</p>
</header>

<div class="container">

    <div class="card">
        <h2><i class="fas fa-info-circle"></i> Project Overview</h2>
        <p>
            This project is a complete Stock Market Data Science Dashboard built using Streamlit.
            It includes technical analysis, ML prediction, sentiment analysis, risk management,
            and portfolio optimization tools.
        </p>
        <span class="badge">Python</span>
        <span class="badge">Streamlit</span>
        <span class="badge">Machine Learning</span>
        <span class="badge">Data Analysis</span>
    </div>

    <div class="card">
        <h2><i class="fas fa-layer-group"></i> Modules</h2>
        <div class="grid">
            <div class="feature">
                <i class="fas fa-search"></i>
                <h3>Stock Explorer</h3>
            </div>
            <div class="feature">
                <i class="fas fa-chart-area"></i>
                <h3>Technical Analysis</h3>
            </div>
            <div class="feature">
                <i class="fas fa-brain"></i>
                <h3>ML Prediction</h3>
            </div>
            <div class="feature">
                <i class="fas fa-comments"></i>
                <h3>Sentiment Analysis</h3>
            </div>
            <div class="feature">
                <i class="fas fa-shield-alt"></i>
                <h3>Risk Dashboard</h3>
            </div>
            <div class="feature">
                <i class="fas fa-wallet"></i>
                <h3>Portfolio Optimizer</h3>
            </div>
            <div class="feature">
                <i class="fas fa-book"></i>
                <h3>Fundamental Analysis</h3>
            </div>
            <div class="feature">
                <i class="fas fa-globe"></i>
                <h3>Market Overview</h3>
            </div>
            <div class="feature">
                <i class="fas fa-undo"></i>
                <h3>Backtesting</h3>
            </div>
        </div>
    </div>

    <div class="card">
        <h2><i class="fas fa-play-circle"></i> How to Run</h2>
        <pre>
1. Clone the repository
2. Install requirements:
   pip install -r requirements.txt
3. Run Streamlit app:
   streamlit run app.py
        </pre>
    </div>

    <div class="card">
        <h2><i class="fas fa-link"></i> Quick Links</h2>
        <p>
            <a href="#">GitHub Repo</a> |
            <a href="#">Live Demo</a> |
            <a href="#">Documentation</a>
        </p>
    </div>

</div>

<footer>
    <p>Made with ❤️ using Streamlit + Python</p>
</footer>

</body>
</html>
