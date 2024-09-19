<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Store Name</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Your Store Name</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h2>Welcome to Your Store</h2>
            <p>Find the latest trends in fashion and accessories.</p>
        </section>

        <section id="products">
            <h2>Our Products</h2>
            <div class="product-grid">
                <div class="product-item">
                    <img src="product1.jpg" alt="Product 1">
                    <h3>Product 1</h3>
                    <p>$19.99</p>
                    <button>Add to Cart</button>
                </div>
                <div class="product-item">
                    <img src="product2.jpg" alt="Product 2">
                    <h3>Product 2</h3>
                    <p>$29.99</p>
                    <button>Add to Cart</button>
                </div>
                <!-- Add more products as needed -->
            </div>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <form action="#" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Your Store Name. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 15px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

main {
    padding: 20px;
}

.product-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
}

.product-item {
    border: 1px solid #ccc;
    padding: 10px;
    text-align: center;
    width: 200px;
}

footer {
    text-align: center;
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    position: relative;
    bottom: 0;
    width: 100%;
}
