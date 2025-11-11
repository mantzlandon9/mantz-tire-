# mantz-tire-
Website for Mantz Tire Shop
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mantz Tire Shop</title>
  <style>
    body { font-family: Arial, sans-serif; margin:0; padding:0; background:#f4f4f4; }
    header { background:#000; color:#fff; padding:20px; text-align:center; }
    header img { max-width:150px; display:block; margin:0 auto; }
    nav { background:#333; text-align:center; }
    nav a { color:#fff; padding:15px; display:inline-block; text-decoration:none; }
    nav a:hover { background:#555; }
    .container { padding:20px; }
    .product { background:#fff; padding:15px; margin:10px 0; border-radius:5px; }
    footer { background:#000; color:#fff; text-align:center; padding:10px; margin-top:20px; }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Mantz Tire Shop Logo">
    <h1>Mantz Tire Shop</h1>
  </header>

  <nav>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container" id="products">
    <h2>Our Tires</h2>
    <div class="product">
      <h3>All-Season Tire</h3>
      <p>High quality, durable, perfect for any weather.</p>
      <button>Buy Now</button>
    </div>
    <div class="product">
      <h3>Performance Tire</h3>
      <p>For maximum grip and smooth handling.</p>
      <button>Buy Now</button>
    </div>
  </div>

  <div class="container" id="contact">
    <h2>Contact Us</h2>
    <p>123 Main St, Sylva, NC</p>
    <p>Phone: (555) 123-4567</p>
    <p>Email: info@mantztire.com</p>
  </div>

  <footer>
    &copy; 2025 Mantz Tire Shop
  </footer>
</body>
</html>
