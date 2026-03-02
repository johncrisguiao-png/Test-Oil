<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Test Oil ($OIL) | Solana Meme Coin</title>
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500;700;900&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Orbitron', sans-serif;
}

body{
    background:linear-gradient(to bottom,#1a0f05,#3b230b,#000);
    color:#f5d27a;
    scroll-behavior:smooth;
}

/* Navigation */
nav{
    position:fixed;
    width:100%;
    padding:20px 0;
    display:flex;
    justify-content:center;
    background:rgba(0,0,0,0.85);
    z-index:1000;
}

nav .nav-container{
    width:100%;
    max-width:1100px;
    display:flex;
    justify-content:space-between;
    padding:0 20px;
}

nav a{
    color:#f5d27a;
    text-decoration:none;
    margin-left:20px;
    font-weight:bold;
}

/* Hero Section */
.hero{
    height:100vh;
    background:url("https://images.unsplash.com/photo-1501594907352-04cda38ebc29?auto=format&fit=crop&w=1950&q=80") center/cover no-repeat;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    position:relative;
    padding:0 20px;
}

.hero::after{
    content:"";
    position:absolute;
    width:100%;
    height:100%;
    background:rgba(0,0,0,0.65);
}

.hero-content{
    position:relative;
    z-index:1;
    max-width:800px;
}

.hero h1{
    font-size:4rem;
    margin-bottom:20px;
}

.hero p{
    font-size:1.2rem;
    color:#fff3c4;
    margin-bottom:30px;
}

/* Buttons */
.btn{
    padding:15px 30px;
    border-radius:30px;
    background:linear-gradient(90deg,#c89b3c,#000);
    border:2px solid #f5d27a;
    color:#f5d27a;
    font-weight:bold;
    cursor:pointer;
    margin:10px;
    transition:0.3s;
}

.btn:hover{
    background:#f5d27a;
    color:#000;
}

/* Sections */
section{
    padding:120px 20px;
    display:flex;
    justify-content:center;
}

.section-container{
    width:100%;
    max-width:800px;
    text-align:center;
}

h2{
    font-size:2.5rem;
    margin-bottom:40px;
}

.card{
    background:rgba(0,0,0,0.7);
    padding:40px;
    border-radius:15px;
    border:1px solid #c89b3c;
}

/* Contract Box */
.contract{
    margin-top:30px;
    padding:15px;
    background:rgba(255,255,255,0.1);
    border-radius:10px;
    display:inline-block;
    word-break:break-all;
}

/* Footer */
footer{
    padding:40px 20px;
    text-align:center;
    background:#000;
    opacity:0.6;
}
</style>
</head>

<body>

<nav>
    <div class="nav-container">
        <div><strong>$OIL</strong></div>
        <div>
            <a href="#about">About</a>
            <a href="#tokenomics">Tokenomics</a>
            <a href="#roadmap">Roadmap</a>
            <a href="#buy">Buy</a>
        </div>
    </div>
</nav>

<div class="hero">
    <div class="hero-content">
        <h1>TEST OIL 🛢️</h1>
        <p>Drilling liquidity. Pumping profits. Built on Solana.</p>
        <button class="btn" onclick="document.getElementById('buy').scrollIntoView()">Start Drilling</button>

        <div class="contract">
            Solana Contract:
            <span id="contract">PASTE_YOUR_SOLANA_TOKEN_ADDRESS_HERE</span>
            <br><br>
            <button class="btn" style="padding:8px 20px;" onclick="copyContract()">Copy</button>
        </div>
    </div>
</div>

<section id="about">
    <div class="section-container">
        <h2>About Test Oil</h2>
        <div class="card">
            In the middle of the digital desert, we struck gold.<br><br>
            Test Oil is a Solana-based meme coin for those who believe in one thing — drill until it pumps.
            No fluff. Just fuel.
        </div>
    </div>
</section>

<section id="tokenomics">
    <div class="section-container">
        <h2>Tokenomics</h2>
        <div class="card">
            🛢️ Total Supply: 1,000,000,000 $OIL<br><br>
            🔥 60% Liquidity<br>
            🏜️ 30% Community<br>
            📢 10% Marketing<br><br>
            0% Tax — Pure Crude.
        </div>
    </div>
</section>

<section id="roadmap">
    <div class="section-container">
        <h2>Roadmap</h2>
        <div class="card">
            Phase 1: Strike Oil (Launch)<br><br>
            Phase 2: Desert Expansion (Community Growth)<br><br>
            Phase 3: Black Gold Boom (Listings)<br><br>
            Phase 4: Global Refinery (Moon Mission 🚀)
        </div>
    </div>
</section>

<section id="buy">
    <div class="section-container">
        <h2>How to Buy</h2>
        <div class="card">
            1. Install Phantom Wallet<br><br>
            2. Fund with SOL<br><br>
            3. Swap on Jupiter or Raydium<br><br>
            4. Hold $OIL and ride the pump 🛢️
        </div>
    </div>
</section>

<footer>
    © 2026 Test Oil. Built on Solana. Drill responsibly.
</footer>

<script>
function copyContract(){
    const text = document.getElementById("contract").innerText;
    navigator.clipboard.writeText(text);
    alert("Contract copied!");
}
</script>

</body>
</html>
