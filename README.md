# my-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jump Out Crew - Fashion Brand</title>
    <link rel="stylesheet" href="style.css">
    <link rel="icon" href="images/favicon.ico">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="location.html">Location</a></li>
                <li><a href="#">Shop</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h1>Jump Out Crew</h1>
            <p>Elevating fashion to the next level. Shop our latest collections now.</p>
            <a href="#" class="btn-shop-now">Shop Now</a>
        </div>
    </section>

    <section class="featured-products">
        <h2>Featured Products</h2>
        <div class="product-grid">
            <div class="product-card">
                <img src="images/product1.jpg" alt="Product 1">
                <h3>Product Name</h3>
                <p>Price</p>
                <button class="btn-add-to-cart">Add to Cart</button>
            </div>
            <!-- Repeat similar structure for other products -->
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Jump Out Crew. All rights reserved.</p>
    </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - Jump Out Crew</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="location.html">Location</a></li>
                <li><a href="#">Shop</a></li>
            </ul>
        </nav>
    </header>

    <section class="about">
        <h1>About Jump Out Crew</h1>
        <p>Jump Out Crew is more than just a brand. We are a movement dedicated to bringing fresh, bold, and creative designs to the world of fashion. From streetwear to high-end fashion, our products tell a story of individuality and self-expression.</p>
        <h2>Our Values</h2>
        <ul>
            <li>Quality Craftsmanship</li>
            <li>Unique Design</li>
            <li>Customer Satisfaction</li>
            <li>Environmental Sustainability</li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2025 Jump Out Crew. All rights reserved.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Location - Jump Out Crew</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_GOOGLE_MAPS_API_KEY&callback=initMap" async defer></script>
    <script>
        function initMap() {
            var storeLocation = {lat: 40.7128, lng: -74.0060}; // Example location: New York City
            var map = new google.maps.Map(document.getElementById('map'), {
                zoom: 14,
                center: storeLocation
            });
            var marker = new google.maps.Marker({
                position: storeLocation,
                map: map,
                title: 'Jump Out Crew Store'
            });
        }
    </script>
</head>
<body onload="initMap()">
    <header>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="location.html">Location</a></li>
                <li><a href="#">Shop</a></li>
            </ul>
        </nav>
    </header>

    <section class="location">
        <h1>Our Store Location</h1>
        <div id="map" style="height: 400px; width: 100%;"></div>
        <p>Come visit us at our flagship store in New York City. We look forward to seeing you!</p>
        <p><strong>Address:</strong> 123 Fashion St, New York, NY 10001</p>
        <p><strong>Hours:</strong> Mon-Sat: 10am - 8pm, Sun: 12pm - 6pm</p>
    </section>

    <footer>
        <p>&copy; 2025 Jump Out Crew. All rights reserved.</p>
    </footer>
</body>
</html>
