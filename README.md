<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lunarla - Celestial Elegance</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-color: #000;
            color: #fff;
            line-height: 1.6;
        }
        header {
            background: #111;
            padding: 20px;
            text-align: center;
        }
        header img {
            max-width: 150px;
        }
        nav {
            display: flex;
            justify-content: center;
            margin-top: 15px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        nav a:hover {
            color: #e0c28b;
        }
        .hero {
            text-align: center;
            padding: 100px 20px;
            background-image: url('hero-image.jpg');
            background-size: cover;
            background-position: center;
        }
        .hero h1 {
            font-size: 3em;
            margin: 0;
            color: #e0c28b;
        }
        .hero p {
            margin: 20px 0;
            font-size: 1.2em;
        }
        .btn {
            background: #e0c28b;
            color: #000;
            padding: 10px 20px;
            font-size: 1em;
            text-decoration: none;
            border-radius: 5px;
        }
        .btn:hover {
            background: #f3d09b;
        }
        .products-section {
            padding: 50px 20px;
            text-align: center;
        }
        .products-section h2 {
            font-size: 2.5em;
            color: #e0c28b;
        }
        .products {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 30px;
        }
        .product {
            background: #222;
            border: 1px solid #333;
            border-radius: 10px;
            padding: 20px;
            max-width: 300px;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            border-radius: 8px;
        }
        .product h3 {
            font-size: 1.5em;
            margin: 15px 0;
            color: #fff;
        }
        .product p {
            font-size: 1em;
            margin: 10px 0;
        }
        .product .btn {
            margin-top: 10px;
        }
        footer {
            background: #111;
            padding: 20px;
            text-align: center;
            margin-top: 50px;
        }
        footer p {
            margin: 0;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.png" alt="Lunarla Logo">
        <nav>
            <a href="#home">Home</a>
            <a href="#products">Products</a>
            <a href="#about">About Us</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero" id="home">
        <h1>Welcome to Lunarla</h1>
        <p>Discover celestial elegance with our luxurious products.</p>
        <a href="#products" class="btn">Shop Now</a>
    </section>

    <section class="products-section" id="products">
        <h2>Our Products</h2>
        <div class="products">
            <div class="product">
                <img src="candle.jpg" alt="Luxury Candle">
                <h3>Celestial Candle</h3>
                <p>$30.00</p>
                <a href="#" class="btn">Buy Now</a>
            </div>
            <div class="product">
                <img src="bathsoak.jpg" alt="Bath Soak">
                <h3>Moonlit Bath Soak</h3>
                <p>$25.00</p>
                <a href="#" class="btn">Buy Now</a>
            </div>
            <div class="product">
                <img src="ebook.jpg" alt="E-book">
                <h3>Astrology E-book</h3>
                <p>$20.00</p>
                <a href="#" class="btn">Buy Now</a>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Lunarla. All Rights Reserved.</p>
    </footer>
</body>
</html>


