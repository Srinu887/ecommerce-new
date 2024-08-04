<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple eCommerce Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 1rem;
        }
        .product {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        .product-item {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            flex: 1;
            max-width: 300px;
            margin: 0 auto;
            overflow: hidden;
            transition: transform 0.3s;
        }
        .product-item:hover {
            transform: scale(1.05);
        }
        .product-img {
            width: 100%;
            height: auto;
        }
        .product-info {
            padding: 1rem;
            text-align: center;
        }
        .product-title {
            font-size: 1.25rem;
            margin: 0.5rem 0;
        }
        .product-price {
            color: #e60023;
            font-size: 1.5rem;
            margin: 0.5rem 0;
        }
        .add-to-cart {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 0.5rem 1rem;
            font-size: 1rem;
            cursor: pointer;
            border-radius: 4px;
            transition: background-color 0.3s;
        }
        .add-to-cart:hover {
            background-color: #555;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Srinivash eCommerce Store</h1>
    </header>
    
    <div class="container">
        <div class="product">
            <div class="product-item">
                <img src="https://via.placeholder.com/300" alt="Product 1" class="product-img">
                <div class="product-info">
                    <h2 class="product-title">REFREGIRATOR</h2>
                    <p class="product-price">40000</p>
                    <button class="add-to-cart">Add to Cart</button>
                </div>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/300" alt="Product 2" class="product-img">
                <div class="product-info">
                    <h2 class="product-title">SMART TV</h2>
                    <p class="product-price">50000</p>
                    <button class="add-to-cart">Add to Cart</button>
                </div>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/300" alt="Product 3" class="product-img">
                <div class="product-info">
                    <h2 class="product-title">WASHING MACHINE</h2>
                    <p class="product-price">70000</p>
                    <button class="add-to-cart">Add to Cart</button>
                </div>
            </div>
        </div>
    </div>
    
    <footer>
        <p>&copy; 2024 Srinivash eCommerce Store</p>
    </footer>
</body>
</html>
