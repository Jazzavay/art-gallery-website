# art-gallery-website

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Art Gallery</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Your Art Gallery</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#gallery">Gallery</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to My Art</h2>
        <p>Explore my collection of unique artwork available for purchase.</p>
    </section>

    <section id="gallery">
        <h2>Gallery</h2>
        <div class="gallery-grid">
            <div class="art-item">
                <img src="https://via.placeholder.com/300x400" alt="Artwork 1">
                <h3>Piece 1</h3>
                <p>$100</p>
                <button class="buy-btn" onclick="alert('Add payment integration here!')">Buy Now</button>
            </div>
            <div class="art-item">
                <img src="https://via.placeholder.com/300x400" alt="Artwork 2">
                <h3>Piece 2</h3>
                <p>$150</p>
                <button class="buy-btn" onclick="alert('Add payment integration here!')">Buy Now</button>
            </div>
            <!-- Add more art items as needed -->
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: your.email@example.com</p>
    </section>

    <footer>
        <p>&copy; 2025 Your Name. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​
/* Reset default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

/* Header */
header {
    background: #2c3e50;
    color: white;
    padding: 1rem;
    text-align: center;
}

header h1 {
    margin-bottom: 0.5rem;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 1rem;
    font-weight: bold;
}

nav a:hover {
    color: #3498db;
}

/* Sections */
section {
    padding: 2rem;
    text-align: center;
}

#home {
    background: #ecf0f1;
}

#gallery {
    background: white;
}

/* Gallery Grid */
.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1.5rem;
    padding: 1rem;
}

.art-item {
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 5px;
    padding: 1rem;
    transition: transform 0.3s;
}

.art-item:hover {
    transform: scale(1.05);
}

.art-item img {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
}

.art-item h3 {
    margin: 0.5rem 0;
}

.buy-btn {
    background: #e74c3c;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    border-radius: 5px;
    cursor: pointer;
}

.buy-btn:hover {
    background: #c0392b;
}

/* Contact */
#contact {
    background: #ecf0f1;
}

/* Footer */
footer {
    background: #2c3e50;
    color: white;
    text-align: center;
    padding: 1rem;
    position: relative;
    bottom: 0;
    width: 100%;
}
​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​
// Add any additional interactivity here if needed
console.log("Welcome to My Gallery!");
​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​
