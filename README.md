# slashmark_project1
Task 1 : Product Landing Page

Product landing page you will use columns and align the components of the landing page within columns. Basic editing tasks like cropping images and making use of design templates are also covered in this.

#HTML code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <div class="logo">Logo</div>
            <nav>
                <ul>
                    <li><a href="#features">Features</a></li>
                    <li><a href="#details">Details</a></li>
                    <li><a href="#testimonials">Testimonials</a></li>
                    <li><a href="#pricing">Pricing</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <div class="hero-content">
                <h1>Main Headline</h1>
                <p>Subheadline that explains the product.</p>
                <button class="cta">Get Started</button>
            </div>
            <div class="hero-image">
                <img src="hero-image.jpg" alt="Product Image">
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features">
        <div class="container">
            <h2>Features</h2>
            <div class="features-grid">
                <div class="feature">
                    <h3>Feature 1</h3>
                    <p>Description of Feature 1.</p>
                </div>
                <div class="feature">
                    <h3>Feature 2</h3>
                    <p>Description of Feature 2.</p>
                </div>
                <div class="feature">
                    <h3>Feature 3</h3>
                    <p>Description of Feature 3.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Product Details Section -->
    <section id="details">
        <div class="container">
            <h2>Product Details</h2>
            <div class="details-content">
                <div class="details-text">
                    <p>Detailed description of the product...</p>
                </div>
                <div class="details-images">
                    <img src="detail-image1.jpg" alt="Detail Image 1">
                    <img src="detail-image2.jpg" alt="Detail Image 2">
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials">
        <div class="container">
            <h2>What Our Customers Say</h2>
            <div class="testimonials-grid">
                <div class="testimonial">
                    <p>"Great product!" - Customer 1</p>
                </div>
                <div class="testimonial">
                    <p>"Really improved my workflow." - Customer 2</p>
                </div>
                <div class="testimonial">
                    <p>"Highly recommend!" - Customer 3</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing">
        <div class="container">
            <h2>Pricing</h2>
            <div class="pricing-grid">
                <div class="pricing-plan">
                    <h3>Basic Plan</h3>
                    <p>$10/month</p>
                </div>
                <div class="pricing-plan">
                    <h3>Pro Plan</h3>
                    <p>$30/month</p>
                </div>
                <div class="pricing-plan">
                    <h3>Enterprise Plan</h3>
                    <p>$50/month</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="container">
            <p>Contact us: email@example.com</p>
            <p>Follow us on social media</p>
        </div>
    </footer>
</body>
</html>
#css code
<style>
  /* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

.container {
    width: 80%;
    margin: 0 auto;
}

/* Header Styling */
header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
}

header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header nav ul {
    list-style: none;
    display: flex;
}

header nav ul li {
    margin: 0 1rem;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

/* Hero Section */
.hero {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 2rem 0;
}

.hero-content {
    max-width: 50%;
}

.hero-image img {
    max-width: 100%;
}

/* Features Section */
#features {
    padding: 2rem 0;
}

.features-grid {
    display: flex;
    justify-content: space-between;
}

.feature {
    width: 30%;
}

/* Product Details Section */
#details {
    padding: 2rem 0;
}

.details-content {
    display: flex;
    justify-content: space-between;
}

.details-text {
    width: 50%;
}

.details-images {
    width: 45%;
}

.details-images img {
    width: 100%;
    margin-bottom: 1rem;
}

/* Testimonials Section */
#testimonials {
    padding: 2rem 0;
}

.testimonials-grid {
    display: flex;
    justify-content: space-between;
}

.testimonial {
    width: 30%;
    background: #f4f4f4;
    padding: 1rem;
    border-radius: 5px;
}

/* Pricing Section */
#pricing {
    padding: 2rem 0;
}

.pricing-grid {
    display: flex;
    justify-content: space-between;
}

.pricing-plan {
    width: 30%;
    background: #f4f4f4;
    padding: 1rem;
    border-radius: 5px;
    text-align: center;
}

/* Footer Section */
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
}
</style>





