🌤️ AtmosWeather – Real-Time Weather & Forecast Dashboard

AtmosWeather is a modern, fully responsive weather dashboard that provides real-time conditions, a multi-day forecast, air-quality insights, and several environment metrics.
The project integrates live Weather API data, filters and restructures it, and renders it through a clean dashboard layout designed for clarity and a smooth user experience.

📘 Overview

This project started as a basic weather app idea but gradually evolved into a complete dashboard.
Instead of simply displaying raw API results, I focused on:

Structuring and filtering weather data

Converting it into readable, UI-friendly components

Designing a dashboard that feels modern and consistent

Adding extra metrics and interactive visuals

Improving the API response handling for reliability

The result is a polished, real-world style interface suitable for daily weather tracking.

✨ Key Features
🌡️ Current Weather

Live temperature

Weather condition (e.g., overcast, clear, rainy)

City switching with smooth transitions

📅 7-Day Forecast

Interactive line chart for temperature trends

Daily weather icons

Hoverable data points

🍃 Air Quality Index

Circular AQI indicator

Individual pollutant values

Visual color-coded categories

🌅 Sun Timings

Local sunrise & sunset

Auto-formatted AM/PM

🌧️ Rain Prediction

Daily rain probability bars

Percentage-based visual indicators

🌍 Additional Metrics

Humidity

Pressure

Wind speed

Visibility

Precipitation

UV index

🎨 Designed UI

Dark dashboard theme

Smooth card layout

Minimal, clean typography

Fully responsive on all screens

🧠 How the Data Is Processed

The Weather API delivers a large JSON response.
To keep the UI simple and accurate, I:

Pick only the required fields

Convert timestamps to human-readable formats

Extract multi-day forecast arrays

Format AQI values

Map daily temperature into a chart-friendly structure

Remove unused or redundant fields

Apply graceful fallback values for missing data

This results in clean, predictable data feeding into the interface.

🛠️ Tech Stack

HTML5, CSS3, JavaScript

Weather API (OpenWeather or the service you used)

Chart.js for forecast visualization

Custom icons and UI components

📁 Project Structure
├── index.html
├── style.css
├── script.js
├── /assets
│   ├── icons/
│   └── images/
└── README.md

🚀 Getting Started
1. Clone the Repository
git clone https://github.com/YOUR_USERNAME/AtmosWeather.git
cd AtmosWeather

2. Add Your API Key

Open script.js and insert your API key:

const apiKey = "YOUR_API_KEY";

3. Run the Project

Simply open the index.html file in a browser.

📸 Preview

(Replace with your screenshot)

![Dashboard Screenshot](./assets/dashboard-preview.png)

🌱 Future Improvements

Add hourly forecast

Add location search with auto-suggest

Integrate animated weather icons

Add theme switching (light/dark)

PWA support for installation

🙋‍♂️ About This Project

Although inspired by online tutorials, the final result is heavily customized.
I reworked:

The UI design

The data-filtering logic

Component layout

Graph presentation

Error handling

Responsive behavior

This version reflects my understanding of APIs, front-end structure, and dashboard design rather than a simple tutorial copy.

📬 Contact

If you’d like to discuss improvements or ideas, feel free to open an issue or reach out.
Example:<img width="1043" height="596" alt="WeatherX Dashboard" src="https://github.com/user-attachments/assets/a3000f0e-8950-4df9-a4c7-4b712a3a0328" />
