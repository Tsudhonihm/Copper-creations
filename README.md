<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Copper Creations - Handmade Penny Sculptures</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            background-color: #f5f5f5;
        }

        .navbar {
            background-color: #b87333; /* Copper color */
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            color: white;
            font-size: 1.5rem;
            font-weight: bold;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            margin-left: 2rem;
        }

        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), 
                        url('sculpture-bg.jpg');
            background-size: cover;
            height: 60vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            padding: 0 5%;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .products {
            padding: 4rem 5%;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }

        .product-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .product-card:hover {
            transform: translateY(-5px);
        }

        .product-image {
            height: 200px;
            background-color: #ddd;
            background-size: cover;
            background-position: center;
        }

        .product-info {
            padding: 1.5rem;
        }

        .product-price {
            color: #b87333;
            font-size: 1.2rem;
            margin: 0.5rem 0;
        }

        .btn {
            display: inline-block;
            padding: 0.8rem 1.5rem;
            background-color: #b87333;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: #9a5e2b;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 2rem 5%;
            margin-top: 4rem;
        }

        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <div class="logo">Copper Creations</div>
        <div class="nav-links">
            <a href="#shop">Shop</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <section class="hero">
        <div>
            <h1>Handcrafted Penny Sculptures</h1>
            <p>Transform your space with unique copper creations</p>
            <a href="#shop" class="btn" style="margin-top: 1rem;">Shop Now</a>
        </div>
    </section>

    <section class="products" id="shop">
        <div class="product-card">
            <div class="product-image" style="background-image: url('sculpture1.jpg')"></div>
            <div class="product-info">
                <h3>Copper Rose</h3>
                <p class="product-price">$9.99</p>
                <p>Hand-folded penny rose perfect for gifts</p>
                <a href="#" class="btn">Add to Cart</a>
            </div>
        </div>

        <div class="product-card">
            <div class="product-image" style="background-image: url('sculpture2.jpg')"></div>
            <div class="product-info">
                <h3>Miniature Tree</h3>
                <p class="product-price">$19.99</p>
                <p>Intricate bonsai-style penny tree</p>
                <a href="#" class="btn">Add to Cart</a>
            </div>
        </div>

        <div class="product-card">
            <div class="product-image" style="background-image: url('sculpture3.jpg')"></div>
            <div class="product-info">
                <h3>Animal Collection</h3>
                <p class="product-price">$14.99</p>
                <p>Set of 3 small animal figures</p>
                <a href="#" class="btn">Add to Cart</a>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2023 Copper Creations. All rights reserved.</p>
        <p style="margin-top: 0.5rem;">0.5̇2 - Where Art Meets Numismatics</p>
    </footer>
</body>
</html>
