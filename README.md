# Weather App

A simple and user-friendly weather app that fetches real-time weather information using the OpenWeatherMap API. Stay informed about the current weather conditions, temperature, and more.

## Features
- Display the current weather conditions including temperature, humidity, wind speed, and weather description.
- Allow users to search for weather data of different cities.
- Automatically detect and display the weather data of the user's current location.
- Responsive Design to ensure a seamless experience across devices.
 
## Technologies Used
- HTML, CSS and JavaScript for the frontend user interface.
- OpenWeather API to fetch real-time weather data.
- Geolocation API to detect the user's current location.

## Demo

![Output Screenshot](/Output%20-1.png)
![Output Screenshot](/Output%20-2.png)
![Output Screenshot](/Output%20-3.png)
![Output Screenshot](/Output%20-4.png)


Check out the live demo [here](link-to-your-live-demo).

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/gajendra-ingle/Weather-App.git

2. Navigate to the project directory:

    ```bash
    cd weather-app

3. Open index.html in your preferred web browser.
4. Allow the app to use your device's location to automatically fetch the weather data for your current location.  
5. Enter the name of the city you want to check the weather for in the search box.
6. Press the "Search" button to fetech and display the weather data for the specified city.

## API Key Setup

To use the Open Weather API, you need to sign up on their website to obtain an API key. Once you have the API key, create a file named config.js in the project directory and store your API key in it as follows:

 - config.js
    ```bash
    const API_KEY = 'YOUR_API_KEY_HERE';
Replace 'YOUR_API_KEY_HERE' with your actual API key.


## Note
 Do not share your API key publicly or commit it to version control. Use environment variables or other secure methods to manage the API key in production.
