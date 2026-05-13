<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Smart Shop BD</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, sans-serif;
}

body{
    background:#f4f4f4;
}

/* Header */
header{
    background:#0d6efd;
    color:white;
    padding:15px 50px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

header h1{
    font-size:28px;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
    font-weight:bold;
}

/* Hero Section */
.hero{
    background:url('https://images.unsplash.com/photo-1512436991641-6745cdb1723f?q=80&w=1200') no-repeat center center/cover;
    height:400px;
    display:flex;
    justify-content:center;
    align-items:center;
    color:white;
    text-align:center;
}

.hero-content{
    background:rgba(0,0,0,0.6);
    padding:30px;
    border-radius:10px;
}

.hero-content h2{
    font-size:40px;
    margin-bottom:15px;
}

.hero-content p{
    font-size:18px;
    margin-bottom:20px;
}

.btn{
    background:#ffc107;
    color:black;
    padding:12px 25px;
    text-decoration:none;
    border-radius:5px;
    font-weight:bold;
}

/* Products */
.products{
    padding:50px;
    text-align:center;
}

.products h2{
    margin-bottom:30px;
    font-size:35px;
}

.product-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.product-card{
    background:white;
    border-radius:10px;
    overflow:hidden;
    box-shadow:0 2px 10px rgba(0,0,0,0.1);
    transition:0.3s;
}

.product-card:hover{
    transform:translateY(-5px);
}

.product-card img{
    width:100%;
    height:220px;
    object-fit:cover;
}

.product-info{
    padding:20px;
}

.product-info h3{
    margin-bottom:10px;
}

.price{
    color:#0d6efd;
    font-size:20px;
    font-weight:bold;
    margin-bottom:15px;
}

.buy-btn{
    background:#198754;
    color:white;
    padding:10px 20px;
    border:none;
    border-radius:5px;
    cursor:pointer;
}

/* About */
.about{
    background:white;
    padding:50px;
    text-align:center;
}

.about h2{
    margin-bottom:20px;
}

/* Contact */
.contact{
    padding:50px;
    background:#e9ecef;
}

.contact h2{
    text-align:center;
    margin-bottom:25px;
}

.contact form{
    max-width:500px;
    margin:auto;
}

.contact input,
.contact textarea{
    width:100%;
    padding:12px;
    margin-bottom:15px;
    border:1px solid #ccc;
    border-radius:5px;
}

.contact button{
    width:100%;
    background:#0d6efd;
    color:white;
    border:none;
    padding:12px;
    border-radius:5px;
    cursor:pointer;
}

/* Footer */
footer{
    background:#212529;
    color:white;
    text-align:center;
    padding:20px;
}
</style>
</head>

<body>

<!-- Header -->
<header>
    <h1>Smart Shop BD</h1>

    <nav>
        <a href="#">Home</a>
        <a href="#">Products</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>
</header>

<!-- Hero Section -->
<section class="hero">
    <div class="hero-content">
        <h2>Welcome to Smart Shop BD</h2>
        <p>Your Trusted Online Shopping Platform</p>
        <a href="#" class="btn">Shop Now</a>
    </div>
</section>

<!-- Products -->
<section class="products">
    <h2>Featured Products</h2>

    <div class="product-grid">

        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?q=80&w=800" alt="">
            <div class="product-info">
                <h3>Running Shoes</h3>
                <p class="price">৳2500</p>
                <button class="buy-btn">Add to Cart</button>
            </div>
        </div>

        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30?q=80&w=800" alt="">
            <div class="product-info">
                <h3>Smart Watch</h3>
                <p class="price">৳4500</p>
                <button class="buy-btn">Add to Cart</button>
            </div>
        </div>

        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1511707171634-5f897ff02aa9?q=80&w=800" alt="">
            <div class="product-info">
                <h3>Smart Phone</h3>
                <p class="price">৳15000</p>
                <button class="buy-btn">Add to Cart</button>
            </div>
        </div>

    </div>
</section>

<!-- About -->
<section class="about">
    <h2>About Us</h2>
    <p>
        Smart Shop BD is a professional E-commerce website where customers can
        easily buy products online with secure payment and fast delivery.
    </p>
</section>

<!-- Contact -->
<section class="contact">
    <h2>Contact Us</h2>

    <form>
        <input type="text" placeholder="Your Name">
        <input type="email" placeholder="Your Email">
        <textarea rows="5" placeholder="Your Message"></textarea>

        <button type="submit">Send Message</button>
    </form>
</section>

<!-- Footer -->
<footer>
    <p>© 2026 Smart Shop BD | All Rights Reserved</p>
</footer>

</body>
</html>
