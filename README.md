<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Orthodoxe Christelijke Gemeente</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Roboto:wght@400&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #f8e1d4, #ffcc80);
            color: #333;
            transition: background 0.5s;
        }
        header {
            background: linear-gradient(to right, #800000, #d19a00);
            color: #fff;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }
        h1 {
            margin: 0;
            font-size: 2.5em;
            font-family: 'Playfair Display', serif;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            color: #FFD700;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #ffcc00;
        }
        .content {
            padding: 20px;
            max-width: 800px;
            margin: auto;
            display: flex;
            flex-direction: column;
            gap: 20px;
        }
        .section {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        .section:hover {
            transform: translateY(-5px);
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #800000;
            color: #FFD700;
            position: relative;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -2px 10px rgba(0, 0, 0, 0.3);
        }
        .download-btn {
            display: inline-block;
            padding: 10px 20px;
            background: #FFD700;
            color: #800000;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
            transition: background 0.3s;
        }
        .download-btn:hover {
            background: #ffcc00;
        }
        .blog-link {
            display: block;
            margin: 10px 0;
            color: #800000;
            text-decoration: underline;
            transition: color 0.3s;
        }
        .blog-link:hover {
            color: #d19a00;
        }
    </style>
</head>
<body>

<header>
    <h1>Orthodoxe Christelijke Gemeente</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">Over Ons</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<div class="content">
    <div class="section" id="home">
        <h2>Welkom</h2>
        <p>Welkom bij onze orthodoxe christelijke gemeenschap. Wij zijn een plek van gebed, gemeenschap en leren. Neem de tijd om onze site te verkennen.</p>
    </div>

    <div class="section" id="blogs">
        <h2>Blogs</h2>
        <p>Lees onze laatste artikelen en blogs:</p>
        <a href="#blog1" class="blog-link">Blog 1: De kracht van gebed</a>
        <a href="#blog2" class="blog-link">Blog 2: Onze tradities en feesten</a>
        <a href="#blog3" class="blog-link">Blog 3: De betekenis van de liturgie</a>
    </div>

    <div class="section" id="about">
        <h2>Over Ons</h2>
        <p>Wij zijn een warme en gastvrije gemeenschap die zich richt op het dienen van God en elkaar. Ons doel is om de boodschap van Christus te verspreiden en een plek van hoop en liefde te bieden.</p>
    </div>

    <div class="section" id="contact">
        <h2>Contact</h2>
        <p>Neem contact met ons op voor meer informatie of vragen:</p>
        <p>Email: info@orthodoxgemeente.nl</p>
        <p>Telefoon: 0123-456789</p>
        <a href="document.pdf" class="download-btn" download>Download PDF</a>
    </div>

    <div class="section" id="blog1">
        <h3>Blog 1: De kracht van gebed</h3>
        <p>Gebed is een essentieel onderdeel van ons geloof. Het is onze directe communicatie met God...</p>
    </div>
    <div class="section" id="blog2">
        <h3>Blog 2: Onze tradities en feesten</h3>
        <p>Onze tradities zijn rijk en diepgeworteld. Ze brengen ons dichter bij God en elkaar...</p>
    </div>
    <div class="section" id="blog3">
        <h3>Blog 3: De betekenis van de liturgie</h3>
        <p>De liturgie is een viering van ons geloof, een moment van samenkomst en aanbidding...</p>
    </div>
</div>

<footer>
    <p>&copy; 2024 Orthodoxe Christelijke Gemeente</p>
</footer>

</body>
</html>
