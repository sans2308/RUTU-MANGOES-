
<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="google-site-verification" content="CaNMZZQOoRHrOA-HMd9cw-8djM4Ma3UywTrqphANL-Y" />
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rutu Mangoes</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color:yellow;
            color: #333;
        }

        /* Header */
        header {
            background-color: orange;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            font-size: 3rem;
            margin: 0;
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            margin: 0 15px;
            color: white;
            text-decoration: none;
            font-size: 1.2rem;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Hero Section */
        .hero {
            background-image: url("rutu2.jpg"); /* Make sure rutu2.jpg is in same folder */
            background-size: cover;
            background-position: center;
            height: 60vh;

            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            position: relative;
        }

        /* Dark overlay on hero for readability */
        .hero::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.4);
        }

        .hero-content {
            position: relative;
            z-index: 1;
        }

        .hero h2 {
            font-size: 3rem;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 1.3rem;
            margin-bottom: 20px;
        }

        .cta-button {
            background-color: #FFB800;
            padding: 15px 30px;
            font-size: 1.2rem;
            color: white;
            border: none;
            cursor: pointer;
            text-decoration: none;
        }

        .cta-button:hover {
            background-color: #ff9900;
        }

        /* About Section */
        .about {
            padding: 50px 20px;
            text-align: center;
            background-color: yellow;
        }

        .about h2 {
            font-size: 2.5rem;
        }

        .about p {
            font-size: 1.2rem;
            line-height: 1.6;
            max-width: 800px;
            margin: 20px auto;
        }

        /* Products Section */
        .products {
            padding: 50px 20px;
            text-align: center;
            background-color: yellow;
        }

        .products h2 {
            font-size: 2.5rem;
            margin-bottom: 40px;
        }

        .product-cards {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 30px;
            justify-items: center;
        }

        .product-card {
            background-color: #f0f0f0;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .product-card img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 8px;
        }

        .product-card h3 {
            font-size: 1.6rem;
            margin: 15px 0;
        }

        .product-card p {
            font-size: 1.1rem;
            color: #777;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        footer a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }

        footer a:hover {
            text-decoration: underline;
           }
        
.whatsapp-btn {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 20px;
    background-color: #25D366;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

.whatsapp-btn:hover {
    background-color: #1ebe57;
}


.gallery-grid img {
    width: 24%;          /* fill the container width */
    height: 300px;        /* fixed height for uniformity */
    object-fit: cover;    /* crop image to fill container nicely */
    border-radius: 1px;
        
</style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Rutu Mangoes</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#about">About Us</a>
            <a href="#products">Products</a>
            <a href="#contact">Contact</a>
            <a href="#gallary">Gallary</a>
            <a href="https://youtu.be/gh5waLKp3cY?si=pXexwdaOPgoT_zEn" target="_blank">Advertisement song</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <h2>Welcome to Rutu Mangoes</h2>
            <p>Fresh, Natural & Farm-Fresh Mangoes</p>
            <a href="#products" class="cta-button">Shop Now</a>
        </div>
    </section>

    <!-- About Us Section -->
    <section class="about" id="about">
        <h2>About Rutu Mangoes</h2>
        <p>
            Name: Harshad Joshi.<br>
            Business Name: Rutu Mangoes.<br>
            Industry: Agriculture (Mango Farming & Trading)<br><br>
            Mr. Harshad Joshi is the owner and founder of Rutu Mangoes, a brand known for supplying quality, naturally grown mangoes. With a strong passion for agriculture, he is dedicated to maintaining high standards in cultivation, harvesting, and customer satisfaction.<br><br>
            • Cultivation and sale of premium mango varieties<br>
            • Quality control and freshness assurance<br>
            • Direct farm-to-customer supply<br>
            • Sustainable and traditional farming practices<br><br>
            Several years of experience in mango farming and agricultural business management, with in-depth knowledge of seasonal produce and market demand.
        </p>
    </section>

    <!-- Products Section -->
    <section class="products" id="products">
        <h2>Our Product</h2>
        <div class="product-cards">
            <div class="product-card" data-product="fresh mangoes" >
                <img src="RUTU.jpg" alt="Fresh Mangoes">
                <h3>Fresh Mangoes</h3>
                <p>Sweet, juicy, and ripe mangoes straight from the farm.</p>
 <div class="whatsapp-btn">
<a href="https://wa.me/<Harshad Joshi>?text=I'm%20interested%20in%20Fresh%20Mangoes" class="whatsapp-btn" target="_blank">Chat on WhatsApp</a>
            </div>
        </div>
    </section>
<section class="gallery">
    <h1 align="center">Our Farm</h1>
    <div class="gallery-grid">
        <img src="1.jpg" alt="Mango Farm 1">
        <img src="6.jpg" alt="Mango Farm 2">
        <img src="5.jpg" alt="Mango Farm 3">
        <img src="4.jpg" alt="Mango Farm 4">
        <img src="8.jpg" alt="Mango Farm 8">
<img src="7.jpg" alt="Mango Farm 7">
<img src="9.jpg" alt="Mango Farm 9">
<img src="10.jpg" alt="Mango Farm 10">
<img src="11.jpg" alt="Mango Farm 114">
<img src="12.jpg" alt="Mango Farm 124">
<img src="13.jpg" alt="Mango Farm 134">
<img src="14.jpg" alt="Mango Farm 144">
<img src="15.jpg" alt="Mango Farm 154">
<img src="16.jpg" alt="Mango Farm 164">
<img src="17.jpg" alt="Mango Farm 174">
<img src="18.jpg" alt="Mango Farm 184">
<img src="19.jpg" alt="Mango Farm 4">
<img src="20.jpg" alt="Mango Farm 4">
<img src="23.jpg" alt="Mango Farm 4">
<img src="24.jpg" alt="Mango Farm 4">

    </div>
</section>

<section class="contact" id="contact">
    <h2>Contact Us</h2>
    <p>Email: rutu.agro@gmai.com</p>
    <p>Phone: +91 9421264371</p>
    <p>Address: Near Wada Library, A/P Wada, Tal-Devgad, Dist-Sindhudurga, Maharashtra, India</p>
</section>



    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Rutu Mangoes. All rights reserved.</p>
        <p>
            <a href="#">Privacy Policy</a> |
            <a href="#">Terms of Service</a>
        </p>
    </footer>

</body>
</html>
