# watch-store
An e-commerce website for selling watches online
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Luxury Watch Store</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<h1>Luxury Watch Store</h1>

<div class="cart">
🛒 Cart <span id="cart-count">0</span>
</div>

</header>

<section class="hero">
<h2>Premium Watches Collection</h2>
<p>Find the perfect watch for every moment.</p>
</section>

<section class="products">

<div class="product">
<img src="images/watch1.jpg">
<h3>Classic Gold Watch</h3>
<p>$120</p>
<button onclick="addToCart('Classic Gold Watch',120)">Add to Cart</button>
</div>

<div class="product">
<img src="images/watch2.jpg">
<h3>Luxury Silver Watch</h3>
<p>$180</p>
<button onclick="addToCart('Luxury Silver Watch',180)">Add to Cart</button>
</div>

<div class="product">
<img src="images/watch3.jpg">
<h3>Sport Watch</h3>
<p>$95</p>
<button onclick="addToCart('Sport Watch',95)">Add to Cart</button>
</div>

<div class="product">
<img src="images/watch4.jpg">
<h3>Diamond Watch</h3>
<p>$320</p>
<button onclick="addToCart('Diamond Watch',320)">Add to Cart</button>
</div>

</section>

<section class="cart-section">

<h2>Your Cart</h2>

<ul id="cart-items"></ul>

<h3>Total: $<span id="total">0</span></h3>

<button onclick="checkout()">Checkout</button>

</section>

<footer>
<p>© 2026 Luxury Watch Store</p>
</footer>

<script src="script.js"></script>

</body>
</html>
