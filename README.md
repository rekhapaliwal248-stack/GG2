/* --- NEW FEATURE STYLING --- */

/* HERO Image Section Styling */
#hero-image {
    position: relative;
    padding: 0;
    overflow: hidden; /* Ensure image doesn't bleed */
    margin-bottom: 30px;
    background-color: #000;
    border-radius: 10px;
}

.game-hero {
    width: 100%;
    height: auto;
    display: block;
    /* Image ko thoda dim (dark) karne ke liye */
    filter: brightness(60%); 
}

.hero-content {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
    z-index: 10; /* Image ke upar dikhe */
}

.hero-content h2 {
    font-size: 3.5em;
    margin-bottom: 10px;
    color: white;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.8);
    border-bottom: none;
}

.hero-content p {
    font-size: 1.2em;
    color: #ffd700; /* Gold color */
    margin-bottom: 25px;
}

/* Primary Button Styling */
.btn-primary {
    display: inline-block;
    padding: 12px 30px;
    background-color: #ff4500; /* Orange/Red */
    color: white;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.btn-primary:hover {
    background-color: #e63900;
}


/* GAME FEATURES Section Styling */
#features {
    text-align: center;
}

.feature-grid {
    display: grid;
    /* Teen columns banata hai */
    grid-template-columns: repeat(3, 1fr); 
    gap: 20px;
    margin-top: 20px;
}

.feature-item {
    background-color: #2a2a2a;
    padding: 20px;
    border-radius: 8px;
    border-top: 3px solid #ff4500;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.5);
    transition: transform 0.3s;
}

.feature-item:hover {
    transform: translateY(-5px); /* Hover effect */
    background-color: #333333;
}

.feature-item h3 {
    color: #90ee90; /* Light Green */
    margin-top: 0;
}



 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GG2 - The Ultimate Gaming Experience</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>GG2</h1>
        <p>The Ultimate Gaming Experience</p>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#features">Features</a></li> <li><a href="#news">Latest News</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <main>
        
        <section id="hero-image">
            <div class="hero-content">
                <h2>The Battle Awaits!</h2>
                <p>Pre-order now and get exclusive in-game items.</p>
                <a href="#" class="btn-primary">BUY NOW</a>
            </div>
            <img src="gg2_hero_image.jpg" alt="Epic GG2 Game Scene" class="game-hero">
        </section>
        

        <section id="features">
            <h2>✨ Key Features of GG2</h2>
            <div class="feature-grid">
                
                <div class="feature-item">
                    <h3>Ultra Graphics</h3>
                    <p>Experience stunning 4K visuals powered by the next-gen engine.</p>
                </div>

                <div class="feature-item">
                    <h3>Massive Multiplayer</h3>
                    <p>Join 100-player battles in real-time across huge maps.</p>
                </div>

                <div class="feature-item">
                    <h3>Dynamic Maps</h3>
                    <p>Maps that change with the weather and player destruction!</p>
                </div>
                
            </div>
        </section>

        <section id="news">
            <h2>🔥 Latest Updates</h2>
            </section>
        
    </main>

    <footer>
        <p>&copy; 2025 GG2 Gaming. All rights reserved.</p>
        </footer>

</body>
</html>
