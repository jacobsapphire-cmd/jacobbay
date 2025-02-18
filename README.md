# jacobbay
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JacobBay - Music Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>JacobBay</h1>
        <p>Your destination for premium music</p>
    </header>
    
    <section class="music-catalog">
        <div class="music-item">
            <img src="album1.jpg" alt="Album Cover">
            <h2>Song Title</h2>
            <p>Artist Name</p>
            <audio controls>
                <source src="preview1.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
            <a href="https://paypal.com/buy-link" class="buy-button">Buy Now</a>
        </div>
        
        <div class="music-item">
            <img src="album2.jpg" alt="Album Cover">
            <h2>Song Title 2</h2>
            <p>Artist Name</p>
            <audio controls>
                <source src="preview2.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
            <a href="https://paypal.com/buy-link" class="buy-button">Buy Now</a>
        </div>
    </section>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    text-align: center;
}

header {
    background: #222;
    color: white;
    padding: 20px 0;
}

.music-catalog {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 20px;
}

.music-item {
    background: white;
    margin: 15px;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    width: 250px;
}

.music-item img {
    width: 100%;
    border-radius: 5px;
}

.buy-button {
    display: inline-block;
    margin-top: 10px;
    padding: 10px;
    background: #28a745;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

.buy-button:hover {
    background: #218838;
}
