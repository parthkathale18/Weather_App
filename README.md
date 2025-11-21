🌦️ Weather App – Project Overview

This project is a simple and responsive weather application built using HTML, CSS, and JavaScript. It fetches real-time weather data for any city entered by the user using the OpenWeather API.

📌 Features

🔍 Search weather by city name

🌡️ Displays current temperature in Celsius

🌁 Shows weather condition icon (like rain, clear, clouds)

💧 Display of humidity

💨 Display of wind speed

📱 Fully responsive for mobile and tablet

⚠ Displays an error message if invalid city is entered (if you added that)

🛠️ Technologies Used
Technology	Purpose
HTML	Structure of the web application
CSS	Styling and responsive design
JavaScript	Fetching API and handling user interactions
OpenWeather API	Provides live weather data
🔗 How It Works

The user enters the city name in the input field.

On button click, JavaScript makes a fetch request to the OpenWeather API using:

City name

API key

Metric units (to get temperature in °C)

The response data is extracted and displayed dynamically inside the weather card.

The weather icon changes based on the API response (e.g., rain, clouds, etc.).

The layout adjusts for mobile and tablet screens using CSS media queries.

📁 Project Structure
/project-folder
├── index.html     → Main structure of the app
├── style.css      → Styling & responsive design
├── script.js      → API call and dynamic content handling
└── /weather-app-img → Weather icons and images

🔌 API Integration

The app uses the OpenWeather API to fetch data.

API endpoint includes:

Base URL (weather endpoint)

City name

API key parameter

Units set to metric

Example request structure (without exposing the key here):

BASE_URL + city + "&appid=YOUR_API_KEY"


⚠ Note: The API key is stored directly in JavaScript because this is a frontend-only project.

📲 Responsive Design

The application is designed using a mobile-first approach and then optimized for:

Smartphones (max-width: 600px)

Tablets (600px to 1024px)

Desktop screens

CSS Flexbox and media queries were used to adjust layout, text size, input fields, and icons.

🚀 Deployment

The project is deployed using GitHub Pages

Ensures live weather data works correctly as the API endpoint uses HTTPS

No backend is required

📌 Possible Future Improvements

Add loading indicator

Display error messages for invalid input

Option to get current location weather using geolocation

Show 5-day forecast or hourly weather

👍 Final Thoughts

This project helped in understanding:

✔ How to work with APIs in JavaScript
✔ DOM manipulation for dynamic results
✔ Making a web application fully responsive
✔ Real-world project deployment using GitHub Pages
