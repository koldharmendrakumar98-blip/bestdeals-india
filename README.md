# bestdeals-india
&lt;p> This website is hosted using GitHub Pages. All files like index.html, style.css, and script.js are stored in the "bestdeals" repository.  Any changes made to these files will automatically update the live website. &lt;/p>
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Best Deals India - Top Amazon Affiliate Products 2024</title>
    <meta name="description" content="Amazon ke best deals, discounts aur products. Mobile, Laptop, Earbuds, Smartwatch - sabse saste daam!">
    <meta name="keywords" content="amazon deals, best products india, affiliate products, cheap mobiles, laptops">
    
    <!-- Open Graph Tags -->
    <meta property="og:title" content="Best Deals India - Amazon Products">
    <meta property="og:description" content="Sabse best deals Amazon pe!">
    <meta property="og:type" content="website">
    
    <!-- Schema Markup -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "WebSite",
        "name": "Best Deals India",
        "url": "https://yourdomain.com"
    }
    </script>
    
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <!-- Header -->
    <header class="header">
        <nav class="navbar">
            <div class="nav-container">
                <div class="logo">
                    <h2><i class="fas fa-shopping-bag"></i> BestDeals</h2>
                </div>
                <ul class="nav-menu">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#mobiles">Mobiles</a></li>
                    <li><a href="#laptops">Laptops</a></li>
                    <li><a href="#earbuds">Earbuds</a></li>
                    <li><a href="#deals">Today's Deals</a></li>
                </ul>
                <div class="hamburger">
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>🔥 Amazon Ke Sabse Best Deals</h1>
            <p>70% Tak Discount | COD Available | Free Delivery</p>
            <div class="hero-buttons">
                <a href="#deals" class="btn btn-primary">View All Deals</a>
                <a href="#mobiles" class="btn btn-secondary">Shop Mobiles</a>
            </div>
        </div>
    </section>

    <!-- Categories Section -->
    <section id="mobiles" class="category-section">
        <div class="container">
            <h2 class="section-title">📱 Best Smartphones Under ₹20,000</h2>
            <div class="products-grid">
                <div class="product-card">
                    <div class="product-image">
                        <img src="https://images.unsplash.com/photo-1592899677059-91e3e12d7f55?w=300" alt="Samsung Galaxy A15">
                        <div class="discount-badge">45% OFF</div>
                    </div>
                    <div class="product-info">
                        <h3>Samsung Galaxy A15 5G</h3>
                        <div class="rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <span>4.8 (12,456)</span>
                        </div>
                        <div class="price">
                            <span class="old-price">₹18,999</span>
                            <span class="new-price">₹10,499</span>
                        </div>
                        <a href="https://amzn.to/YOUR_AFFILIATE_LINK" class="buy-btn" target="_blank">
                            <i class="fab fa-amazon"></i> Buy on Amazon
                        </a>
                    </div>
                </div>

                <!-- Add More Products Similarly -->
                <div class="product-card">
                    <div class="product-image">
                        <img src="https://images.unsplash.com/photo-1511707171634-5f897ff02aa9?w=300" alt="iQOO Z9">
                        <div class="discount-badge">52% OFF</div>
                    </div>
                    <div class="product-info">
                        <h3>iQOO Z9 5G</h3>
                        <div class="rating">
                            <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                            <span>4.7 (8,234)</span>
                        </div>
                        <div class="price">
                            <span class="old-price">₹19,999</span>
                            <span class="new-price">₹9,499</span>
                        </div>
                        <a href="https://amzn.to/YOUR_AFFILIATE_LINK" class="buy-btn" target="_blank">
                            <i class="fab fa-amazon"></i> Buy on Amazon
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Today's Deals -->
    <section id="deals" class="deals-section">
        <div class="container">
            <h2 class="section-title">⚡ Today's Flash Deals (Limited Time)</h2>
            <div class="deals-timer">
                <div class="timer-item">
                    <span id="hours">23</span>
                    <h4>Hrs</h4>
                </div>
                <div class="timer-item">
                    <span id="minutes">59</span>
                    <h4>Mins</h4>
                </div>
                <div class="timer-item">
                    <span id="seconds">30</span>
                    <h4>Secs</h4>
                </div>
            </div>
            <!-- Add more deal products here -->
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>BestDeals</h3>
                    <p>Amazon Affiliate Products ke best deals daily update!</p>
                </div>
                <div class="footer-section">
                    <h4>Categories</h4>
                    <ul>
                        <li><a href="#mobiles">Mobiles</a></li>
                        <li><a href="#laptops">Laptops</a></li>
                        <li><a href="#earbuds">Earbuds</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h4>Quick Links</h4>
                    <ul>
                        <li><a href="#">Privacy Policy</a></li>
                        <li><a href="#">Terms</a></li>
                        <li><a href="#">Contact</a></li>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2024 BestDeals. Amazon Affiliate Program se powered.</p>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
    line-height: 1.6;
    color: #333;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Header */
.header {
    background: #fff;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
}

.navbar {
    padding: 1rem 0;
}

.nav-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo h2 {
    color: #ff6b35;
    font-size: 1.8rem;
}

.nav-menu {
    display: flex;
    list-style: none;
    gap: 2rem;
}

.nav-menu a {
    text-decoration: none;
    color: #333;
    font-weight: 500;
    transition: color 0.3s;
}

.nav-menu a:hover {
    color: #ff6b35;
}

.hamburger {
    display: none;
    flex-direction: column;
    cursor: pointer;
}

.hamburger span {
    width: 25px;
    height: 3px;
    background: #333;
    margin: 3px 0;
    transition: 0.3s;
}

/* Hero Section */
.hero {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: white;
    margin-top: 80px;
}

.hero-content h1 {
    font-size: 3.5rem;
    margin-bottom: 1rem;
    animation: fadeInUp 1s ease;
}

.hero-content p {
    font-size: 1.3rem;
    margin-bottom: 2rem;
    animation: fadeInUp 1s ease 0.2s both;
}

.hero-buttons {
    display: flex;
    gap: 1rem;
    justify-content: center;
    flex-wrap: wrap;
}

.btn {
    padding: 15px 30px;
    border: none;
    border-radius: 50px;
    font-size: 1.1rem;
    font-weight: 600;
    text-decoration: none;
    transition: all 0.3s;
    display: inline-block;
}

.btn-primary {
    background: #ff6b35;
    color: white;
}

.btn-primary:hover {
    background: #e55a2b;
    transform: translateY(-3px);
}

.btn-secondary {
    background: transparent;
    color: white;
    border: 2px solid white;
}

.btn-secondary:hover {
    background: white;
    color: #667eea;
}

/* Category Section */
.category-section {
    padding: 100px 0;
    background: #f8f9fa;
}

.section-title {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 3rem;
    color: #333;
}

.products-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    gap: 2rem;
}

.product-card {
    background: white;
    border-radius: 20px;
    overflow: hidden;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    transition: all 0.3s;
}

.product-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 20px 40px rgba(0,0,0,0.15);
}

.product-image {
    position: relative;
    height: 250px;
    overflow: hidden;
}

.product-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s;
}

.product-card:hover .product-image img {
    transform: scale(1.1);
}

.discount-badge {
    position: absolute;
    top: 15px;
    right: 15px;
    background: #ff6b35;
    color: white;
    padding: 8px 15px;
    border-radius: 20px;
    font-weight: 600;
    font-size: 0.9rem;
}

.product-info {
    padding: 25px;
}

.product-info h3 {
    font-size: 1.3rem;
    margin-bottom: 10px;
    color: #333;
}

.rating {
    color: #ffa500;
    margin-bottom: 15px;
}

.rating span {
    color: #666;
    font-size: 0.9rem;
    margin-left: 10px;
}

.price {
    margin-bottom: 20px;
}

.old-price {
    text-decoration: line-through;
    color: #999;
    font-size: 1.1rem;
    margin-right: 10px;
}

.new-price {
    color: #ff6b35;
    font-size: 1.5rem;
    font-weight: 700;
}

.buy-btn {
    width: 100%;
    background: linear-gradient(45deg, #ff6b35, #f7931e);
    color: white;
    padding: 15px;
    border-radius: 10px;
    text-decoration: none;
    text-align: center;
    font-weight: 600;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
    transition: all 0.3s;
}

.buy-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 10px 20px rgba(255,107,53,0.3);
}

/* Deals Section */
.deals-section {
    padding: 100px 0;
    background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 100%);
}

.deals-timer {
    display: flex;
    justify-content: center;
    gap: 2rem;
    margin-top: 2rem;
    flex-wrap: wrap;
}

.timer-item {
    background: white;
    padding: 20px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
}

.timer-item span {
    font-size: 2.5rem;
    font-weight: 700;
    color: #ff6b35;
    display: block;
}

/* Footer */
.footer {
    background: #333;
    color: white;
    padding: 50px 0 20px;
}

.footer-content {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    margin-bottom: 2rem;
}

.footer-section h3,
.footer-section h4 {
    margin-bottom: 1rem;
}

.footer-section ul {
    list-style: none;
}

.footer-section ul li {
    margin-bottom: 0.5rem;
}

.footer-section a {
    color: #ccc;
    text-decoration: none;
    transition: color 0.3s;
}

.footer-section a:hover {
    color: #ff6b35;
}

.footer-bottom {
    text-align: center;
    padding-top: 2rem;
    border-top: 1px solid #555;
    color: #ccc;
}

/* Animations */
@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* Responsive */
@media (max-width: 768px) {
    .hamburger {
        display: flex;
    }
    
    .nav-menu {
        position: fixed;
        left: -100%;
        top: 70px;
        flex-direction: column;
        background-color: white;
        width: 100%;
        text-align: center;
        transition: 0.3s;
        box-shadow: 0 10px 27px rgba(0,0,0,0.05);
        padding: 2rem 0;
    }
    
    .nav-menu.active {
        left: 0;
    }
    
    .hero-content h1 {
        font-size: 2.5rem;
    }
    
    .products-grid {
        grid-template-columns: 1fr;
    }
    
    .hero-buttons {
        flex-direction: column;
        align-items: center;
    }
}// Mobile Navigation Toggle
const hamburger = document.querySelector('.hamburger');
const navMenu = document.querySelector('.nav-menu');

hamburger.addEventListener('click', () => {
    hamburger.classList.toggle('active');
    navMenu.classList.toggle('active');
});

// Close mobile menu when clicking on a link
document.querySelectorAll('.nav-menu a').forEach(n => n.addEventListener('click', () => {
    hamburger.classList.remove('active');
    navMenu.classList.remove('active');
}));

// Smooth Scrolling
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});

// Countdown Timer
function updateTimer() {
    const now = new Date().getTime();
    const nextHour = new Date();
    nextHour.setHours(nextHour.getHours() + 1, 0, 0, 0);
    const distance = nextHour - now;

    const hours = Math.floor(distance / (1000 * 60 * 60));
    const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    const seconds = Math.floor((distance % (1000 * 60)) / 1000);

    document.getElementById('hours').textContent = hours.toString().padStart(2, '0');
    document.getElementById('minutes').textContent = minutes.toString().padStart(2, '0');
    document.getElementById('seconds').textContent = seconds.toString().padStart(2, '0');
}

setInterval(updateTimer, 1000);

// Intersection Observer for Animations
const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -50px 0px'
};

const observer
