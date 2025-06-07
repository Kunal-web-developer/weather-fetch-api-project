# WeatherSphere - Real-time Weather Application

## Overview

WeatherSphere is a responsive web application that provides real-time weather updates for cities worldwide. It features a clean, modern interface with dynamic background changes based on current weather conditions, temperature unit toggling, and a 5-day forecast.

## Features

- **Current Weather Data**:
  - Temperature (with Celsius/Fahrenheit toggle)
  - Weather condition with visual icon
  - Humidity
  - Wind speed
  - Feels-like temperature
  - Atmospheric pressure
  - Visibility

- **5-Day Forecast**:
  - Daily weather predictions
  - Temperature highs
  - Weather condition icons

- **User Experience**:
  - Automatic location detection (with geolocation)
  - City search functionality
  - Responsive design for all device sizes
  - Dynamic background that changes with weather conditions
  - Loading spinner during API requests
  - Error handling for invalid locations

## Technologies Used

- HTML5
- CSS3 (with CSS variables for theming)
- JavaScript (ES6)
- OpenWeatherMap API

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/WeatherSphere.git
   ```

2. **Open the application**:
   - Simply open the `weather.html` file in your web browser
   - No server or additional dependencies required

3. **Using the application**:
   - The app will automatically try to detect your location
   - You can also search for any city using the search bar
   - Toggle between Celsius and Fahrenheit using the buttons

## API Key Note

This application uses the OpenWeatherMap API. The included API key is for demonstration purposes. For production use, consider:

1. Getting your own API key from [OpenWeatherMap](https://openweathermap.org/)
2. Storing it securely (not in client-side code for production apps)



---

You can customize this README further by:
1. Adding actual screenshot files and updating the screenshot section
2. Including your project's deployment link if hosted
3. Adding contribution guidelines if you want others to contribute
4. Including any acknowledgments or credits
