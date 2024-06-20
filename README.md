<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BlaBlaSleep</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap" async defer></script>
</head>
<body>
    <header>
        <div class="logo">BlaBlaSleep</div>
        <nav>
            <ul>
                <li><a href="#" class="nav-link" data-section="home">Home</a></li>
                <li><a href="#" class="nav-link" data-section="hotels">Hotels</a></li>
                <li><a href="#" class="nav-link" data-section="flights">Flights</a></li>
                <li><a href="#" class="nav-link" data-section="trains">Trains</a></li>
                <li><a href="#" class="nav-link" data-section="buses">Buses</a></li>
                <li><a href="#" class="nav-link" data-section="airbnb">Airbnb</a></li>
                <li><a href="#" class="nav-link" data-section="contact">Contact Us</a></li>
            </ul>
        </nav>
        <div class="user-account"><a href="#">Login</a></div>
    </header>

    <main>
        <section id="home" class="search-section active-section">
            <h1>Find Your Perfect Stay and Travel</h1>
            <div class="search-bar">
                <input id="search-input" type="text" placeholder="Search for hotels, flights, trains, buses, Airbnb...">
                <button id="search-button">Search</button>
            </div>
        </section>

        <section class="featured-listings">
            <h2>Featured Listings</h2>
            <div class="carousel" id="carousel">
                <div class="carousel-inner" id="carousel-inner">
                    <!-- Dynamic content will be inserted here -->
                </div>
                <a class="carousel-control-prev" href="#carousel" role="button" data-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="sr-only">Previous</span>
                </a>
                <a class="carousel-control-next" href="#carousel" role="button" data-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="sr-only">Next</span>
                </a>
            </div>
        </section>

        <section class="map-section">
            <h2>Map View</h2>
            <div id="map"></div>
        </section>

        <section id="hotels" class="service-section">
            <h2>Hotels</h2>
            <div class="listings" id="hotel-listings">
                <!-- Dynamic hotel content -->
            </div>
        </section>

        <section id="flights" class="service-section">
            <h2>Flights</h2>
            <div class="listings" id="flight-listings">
                <!-- Dynamic flight content -->
            </div>
        </section>

        <section id="trains" class="service-section">
            <h2>Trains</h2>
            <div class="listings" id="train-listings">
                <!-- Dynamic train content -->
            </div>
        </section>

        <section id="buses" class="service-section">
            <h2>Buses</h2>
            <div class="listings" id="bus-listings">
                <!-- Dynamic bus content -->
            </div>
        </section>

        <section id="airbnb" class="service-section">
            <h2>Airbnb</h2>
            <div class="listings" id="airbnb-listings">
                <!-- Dynamic Airbnb content -->
            </div>
        </section>

        <section id="contact" class="service-section">
            <h2>Contact Us</h2>
            <form id="contact-form">
                <input type="text" id="name" name="name" placeholder="Your Name" required>
                <input type="email" id="email" name="email" placeholder="Your Email" required>
                <textarea id="message" name="message" placeholder="Your Message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
    </main>

    <footer>
        <div class="footer-links">
            <a href="#">Quick Links</a>
            <a href="#">Contact</a>
            <a href="#">Terms and Conditions</a>
            <a href="#">Privacy Policy</a>
        </div>
        <div class="social-media">
            <!-- Social Media Icons -->
        </div>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
