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





Task 2 : Basic Portfolio Website

You must try making your own portfolio website for yourself. Showcase your projects, your social media handles, your experience on the website. You can refer to some templates available for free on Google for that.


#HTML code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h1>Hello, I'm [Your Name]</h1>
        <p>Welcome to my portfolio website. I'm a [Your Profession] with experience in [Your Skills].</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>Description of project 1.</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>Description of project 2.</p>
        </div>
        <!-- Add more projects as needed -->
    </section>

    <section id="experience">
        <h2>Experience</h2>
        <div class="job">
            <h3>Job Title at Company</h3>
            <p>Description of your role and responsibilities.</p>
        </div>
        <!-- Add more job experiences as needed -->
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>You can find me on:</p>
        <ul>
            <li><a href="https://linkedin.com/in/yourprofile" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a></li>
            <li><a href="https://github.com/yourusername" target="_blank"><i class="fab fa-github"></i> GitHub</a></li>
            <!-- Add more social media links as needed -->
        </ul>
    </section>

    <footer>
        <p>&copy; 2024 [Your Name]. All rights reserved.</p>
    </footer>
</body>
</html>
#css code
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 1rem;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 2rem;
    max-width: 800px;
    margin: 0 auto;
}

#about {
    background: #f4f4f4;
    text-align: center;
}

.project, .job {
    margin-bottom: 1.5rem;
}

#contact ul {
    list-style: none;
    padding: 0;
    text-align: center;
}

#contact ul li {
    display: inline;
    margin: 0 1rem;
}

#contact ul li a {
    text-decoration: none;
    color: #333;
    font-size: 1.2rem;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}



Task 3 :Weather Forecast Website

In this project, you will make a web application to check out the weather forecast for the current day and for the next few days. You will use an API to fetch real-time data and then add it to your application. The user will input his/her location and the weather forecast for the next 5 days will be displayed. In addition, a feature to automatically detect the location can add to the versatility of the project.


==>Creating a weather forecast web application involves several key steps, including setting up a web server, fetching data from a weather API, and creating a user interface to display the weather information. Here's a step-by-step guide to help you build this project:
1. Choose Your Technology Stack
You will need to choose a technology stack for your web application. Here’s a recommended stack:
•	Frontend: HTML, CSS, JavaScript (with a framework like React.js or Vue.js if you prefer)
•	Backend: Node.js with Express.js
•	API: OpenWeatherMap API or any other weather API
•	Geolocation: Browser Geolocation API
2. Set Up Your Development Environment
•	Install Node.js and npm.
•	Set up your project directory and initialize it with npm init.
•	Install necessary dependencies: express, axios (for making HTTP requests), and dotenv (for managing environment variables).
3. Create Your Backend
Your backend will handle API requests to the weather service and serve the frontend files.
server.js:
const express = require('express');
const axios = require('axios');
const path = require('path');
require('dotenv').config();

const app = express();
const port = process.env.PORT || 3000;
const apiKey = process.env.WEATHER_API_KEY;

app.use(express.static(path.join(__dirname, 'public')));

app.get('/weather', async (req, res) => {
    const { lat, lon } = req.query;
    if (!lat || !lon) {
        return res.status(400).json({ error: 'Location coordinates are required' });
    }

    try {
        const response = await axios.get(`https://api.openweathermap.org/data/2.5/forecast`, {
            params: {
                lat,
                lon,
                appid: apiKey,
                units: 'metric' // or 'imperial' for Fahrenheit
            }
        });
        res.json(response.data);
    } catch (error) {
        res.status(500).json({ error: 'Failed to fetch weather data' });
    }
});

app.listen(port, () => {
    console.log(`Server is running on port ${port}`);
});

.env:
WEATHER_API_KEY=your_openweather_api_key
4. Create Your Frontend
The frontend will have an HTML file, a CSS file for styling, and a JavaScript file to handle interactions and fetch data from the backend.
public/index.html:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather Forecast</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Weather Forecast</h1>
        <button id="getLocationBtn">Get My Location</button>
        <div id="weatherData"></div>
    </div>
    <script src="app.js"></script>
</body>
</html>

public/styles.css:
body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: #f0f0f0;
}

.container {
    text-align: center;
    background: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

#weatherData {
    margin-top: 20px;
}
public/app.js:
document.getElementById('getLocationBtn').addEventListener('click', () => {
    if (navigator.geolocation) {
        navigator.geolocation.getCurrentPosition(showPosition, showError);
    } else {
        alert('Geolocation is not supported by this browser.');
    }
});

function showPosition(position) {
    const lat = position.coords.latitude;
    const lon = position.coords.longitude;

    fetch(`/weather?lat=${lat}&lon=${lon}`)
        .then(response => response.json())
        .then(data => displayWeather(data))
        .catch(error => console.error('Error fetching weather data:', error));
}

function showError(error) {
    let errorText;
    switch(error.code) {
        case error.PERMISSION_DENIED:
            errorText = "User denied the request for Geolocation.";
            break;
        case error.POSITION_UNAVAILABLE:
            errorText = "Location information is unavailable.";
            break;
        case error.TIMEOUT:
            errorText = "The request to get user location timed out.";
            break;
        case error.UNKNOWN_ERROR:
            errorText = "An unknown error occurred.";
            break;
    }
    alert(errorText);
}

function displayWeather(data) {
    const weatherDiv = document.getElementById('weatherData');
    weatherDiv.innerHTML = '';

    data.list.forEach(item => {
        const weatherItem = document.createElement('div');
        weatherItem.className = 'weather-item';
        weatherItem.innerHTML = `
            <h3>${new Date(item.dt_txt).toLocaleDateString()}</h3>
            <p>Temperature: ${item.main.temp} °C</p>
            <p>Weather: ${item.weather[0].description}</p>
        `;
        weatherDiv.appendChild(weatherItem);
    });
}
5. Run Your Application
Start your backend server:
node server.js

1.	Open your browser and navigate to http://localhost:3000.
You should now have a functioning weather forecast web application that can detect the user's location and display the weather forecast for the next 5 days. If you want to deploy this application, consider using platforms like Heroku, Vercel, or Netlify.
4o


