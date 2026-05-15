<!DOCTYPE html><html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Stock DS Project - Interactive README</title><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"><style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background: #0f172a;
        color: #e2e8f0;
        display: flex;
    }

    /* Sidebar */
    .sidebar {
        width: 260px;
        background: #111827;
        height: 100vh;
        position: fixed;
        padding: 20px;
    }

    .sidebar h2 {
        color: #38bdf8;
        font-size: 18px;
        margin-bottom: 20px;
    }

    .sidebar a {
        display: block;
        color: #cbd5e1;
        padding: 10px;
        margin: 5px 0;
        text-decoration: none;
        border-radius: 8px;
    }

    .sidebar a:hover {
        background: #1e3a8a;
        color: white;
    }

    /* Main */
    .main {
        margin-left: 280px;
        padding: 20px;
        width: 100%;
    }

    header {
        background: linear-gradient(90deg, #1e3a8a, #0ea5e9);
        padding: 25px;
        border-radius: 12px;
        text-align: center;
    }

    .card {
        background: #1e293b;
        padding: 20px;
        margin: 15px 0;
        border-radius: 12px;
    }

    .grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 15px;
    }

    .feature {
        background: #0b1220;
        padding: 15px;
        border-radius: 10px;
        text-align: center;
    }

    .feature i {
        font-size: 28px;
        color: #38bdf8;
    }

    .badge {
        background: #2563eb;
        padding: 5px 10px;
        border-radius: 20px;
        margin: 5px;
        font-size: 12px;
        display: inline-block;
    }

    img {
        width: 100%;
        border-radius: 10px;
        margin-top: 10px;
        border: 1px solid #334155;
    }

    footer {
        text-align: center;
        padding: 20px;
        color: #94a3b8;
    }
</style></head>
<body><div class="sidebar">
    <h2>📊 Stock DS</h2>
    <a href="#overview">Overview</a>
    <a href="#modules">Modules</a>
    <a href="#screenshots">Screenshots</a>
    <a href="#run">How to Run</a>
    <a href="#links">Links</a>
</div><div class="main"><header>
    <h1><i class="fas fa-chart-line"></i> Stock Data Science Project</h1>
    <p>Interactive ML + Analytics Dashboard (Streamlit)</p>
</header><div class="card" id="overview">
    <h2><i class="fas fa-info-circle"></i> Overview</h2>
    <p>
        Full Stock Market Data Science system with prediction, analysis, sentiment detection,
        portfolio optimization and backtesting modules.
    </p>
    <span class="badge">Python</span>
    <span class="badge">Streamlit</span>
    <span class="badge">ML</span>
    <span class="badge">Data Science</span>
</div><div class="card" id="modules">
    <h2><i class="fas fa-layer-group"></i> Modules</h2>
    <div class="grid">
        <div class="feature"><i class="fas fa-search"></i><p>Stock Explorer</p></div>
        <div class="feature"><i class="fas fa-chart-area"></i><p>Technical Analysis</p></div>
        <div class="feature"><i class="fas fa-brain"></i><p>ML Prediction</p></div>
        <div class="feature"><i class="fas fa-comments"></i><p>Sentiment</p></div>
        <div class="feature"><i class="fas fa-wallet"></i><p>Portfolio</p></div>
        <div class="feature"><i class="fas fa-shield-alt"></i><p>Risk Dashboard</p></div>
        <div class="feature"><i class="fas fa-book"></i><p>Fundamental</p></div>
        <div class="feature"><i class="fas fa-globe"></i><p>Market Overview</p></div>
        <div class="feature"><i class="fas fa-undo"></i><p>Backtesting</p></div>
    </div>
</div><div class="card" id="screenshots">
    <h2><i class="fas fa-image"></i> Streamlit App Screenshots</h2><p>⚠️ Add your real screenshots inside <b>/assets</b> folder and name them properly.</p>

<h3>Stock Explorer</h3>
<img src="assets/stock_explorer.png" alt="Stock Explorer Screenshot">

<h3>Technical Analysis</h3>
<img src="assets/technical_analysis.png" alt="Technical Analysis Screenshot">

<h3>ML Prediction</h3>
<img src="assets/ml_prediction.png" alt="ML Prediction Screenshot">

<h3>Sentiment Analysis</h3>
<img src="assets/sentiment.png" alt="Sentiment Screenshot">

<h3>Portfolio Optimizer</h3>
<img src="assets/portfolio.png" alt="Portfolio Screenshot">

</div><div class="card" id="run">
    <h2><i class="fas fa-play-circle"></i> How to Run</h2>
    <pre>
1. Extract project
2. Install dependencies:
   pip install -r requirements.txt
3. Run:
   streamlit run app.py
    </pre>
</div><div class="card" id="links">
    <h2><i class="fas fa-link"></i> Links</h2>
    <p>
        <a href="#">GitHub Repo</a> |
        <a href="#">Live Demo</a>
    </p>
</div><footer>
    Made with ❤️ using Streamlit + ML
</footer></div></body>
</html>        margin-top: 10px;
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
