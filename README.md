# Weather App

## Overview

The Weather App is a simple and user-friendly web application that provides real-time weather updates for any city in the world. The application fetches data from the OpenWeatherMap API and displays the current temperature, humidity, wind speed, and weather conditions.

## Features

- **City Search**: Enter the name of any city to get the latest weather information.
- **Real-time Data**: Displays up-to-date temperature, humidity, and wind speed.
- **Dynamic Icons**: Weather icons change based on the current weather conditions (e.g., Clouds, Clear, Rain).
- **Error Handling**: Displays an error message if an invalid city name is entered.

## Technologies Used

- **HTML5**: For the structure of the application.
- **CSS3**: For styling and layout.
- **JavaScript (ES6)**: For making API requests and dynamically updating the UI.
- **OpenWeatherMap API**: To fetch real-time weather data.

## Installation

To run the Weather App locally:

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/weather-app.git
    ```

2. Navigate to the project directory:
    ```bash
    cd weather-app
    ```

3. Open the `index.html` file in your browser.

## Usage

- Type the name of the city you want to check the weather for in the search box.
- Click the search button to get the latest weather information.
- The app will display the temperature, humidity, wind speed, and weather condition for the selected city.

## API Key

This project uses the OpenWeatherMap API. You need to replace the `apikey` variable in the `index.html` file with your own API key:

```javascript```
const apikey = "your_api_key_here";



## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any features, bug fixes, or improvements.


[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](https://opensource.org/licenses/MIT)