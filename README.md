<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Showcase Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Showcase Website</h1>
        <nav>
            <ul>
                <li><a href="#features">Features</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h2>Welcome to Our Showcase</h2>
        <p>Explore our amazing features and projects!</p>
        <a href="#features" class="cta-button">Get Started</a>
    </section>

    <section id="features">
        <h2>Features</h2>
        <div class="feature-card">
            <h3>Feature 1</h3>
            <p>Description of feature 1.</p>
        </div>
        <div class="feature-card">
            <h3>Feature 2</h3>
            <p>Description of feature 2.</p>
        </div>
        <div class="feature-card">
            <h3>Feature 3</h3>
            <p>Description of feature 3.</p>
        </div>
    </section>

    <section id="gallery">
        <h2>Gallery</h2>
        <div class="gallery-grid">
            <img src="image1.jpg" alt="Gallery Image 1">
            <img src="image2.jpg" alt="Gallery Image 2">
            <img src="image3.jpg" alt="Gallery Image 3">
            <img src="image4.jpg" alt="Gallery Image 4">
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form id="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Showcase Website</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
****
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

header {
    background: #333;
    color: #fff;
    padding: 10px 20px;
}

header nav ul {
    list-style: none;
    display: flex;
}

header nav ul li {
    margin-right: 20px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

.hero {
    background: url('hero.jpg') no-repeat center center/cover;
    color: #fff;
    padding: 100px 20px;
    text-align: center;
}

.cta-button {
    background: #e63946;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

section {
    padding: 20px;
}

.feature-card {
    border: 1px solid #ccc;
    margin: 10px 0;
    padding: 15px;
}

.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 10px;
}

.gallery-grid img {
    width: 100%;
    border-radius: 8px;
}

form {
    display: flex;
    flex-direction: column;
}

form input, form textarea {
    margin-bottom: 10px;
    padding: 10px;
}

footer {
    text-align: center;
    padding: 20px;
    background: #333;
    color: #fff;
}
document.getElementById('contact-form').addEventListener('submit', function(event) {
    event.preventDefault();
    alert('Thank you for your message!');
    this.reset();
});

