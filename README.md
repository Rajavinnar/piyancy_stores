<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Piyancy Stores</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="#">Cart</a></li>
                <li><a href="#">Wishlist</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section class="product-list">
        <h2>Featured Products</h2>
        <div class="product-card">
            <img src="product1.jpg" alt="Product 1">
            <h3>3M Scotch-Brite Sponge</h3>
            <p>₹85</p>
            <button>Add to Cart</button>
        </div>
        <div class="product-card">
            <img src="product2.jpg" alt="Product 2">
            <h3>3M Mask N95</h3>
            <p>₹120</p>
            <button>Add to Cart</button>
        </div>
        <!-- Add more products here -->
    </section>

    <footer>
        <p>© 2025 Piyancy Stores | All Rights Reserved</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
<section class="product-list">
    <h2>Featured Products</h2>
    <div class="product-card">
        <img src="product1.jpg" alt="Product 1">
        <h3>3M Scotch-Brite Sponge</h3>
        <p>₹85</p>
        <button>Add to Cart</button>
    </div>
    <div class="product-card">
        <img src="product2.jpg" alt="Product 2">
        <h3>3M Mask N95</h3>
        <p>₹120</p>
        <button>Add to Cart</button>
    </div>
    <!-- Add more products here -->
</section>

<footer>
    <p>© 2025 Piyancy Stores | All Rights Reserved</p>
</footer>

<script src="script.js"></script>/* Basic CSS for layout */
body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    color: #333;
}

header {
    background-color: #4c9f70;
    padding: 10px;
    color: white;
    text-align: center;
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

.product-list {
    display: flex;
    justify-content: space-around;
    padding: 20px;
}

.product-card {
    background-color: #fff;
    border: 1px solid #ddd;
    padding: 15px;
    text-align: center;
    width: 200px;
}

.product-card img {
    width: 100%;
    height: auto;
}

button {
    background-color: #4c9f70;
    color: white;
    padding: 10px;
    border: none;
    cursor: pointer;
    margin-top: 10px;
}
document.querySelectorAll('button').forEach(button => {
    button.addEventListener('click', function() {
        alert('Product added to cart!');
    });
});
