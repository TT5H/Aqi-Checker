
# AQI Checker

AQI Checker is a web application that allows users to view the current Air Quality Index (AQI) for a specific location,
along with recommendations for outdoor activities based on air quality. The app fetches live data from the World Air
Quality Index (WAQI) API.

<div align="center">
    <img src="https://i.imgur.com/phlsrnK.png" alt="AQI Checker Screenshot">
</div>

## Features

- Displays current AQI and main pollutant information for a location
- Provides health recommendations based on AQI levels
- Shows historical PM2.5 data for multiple past days

## Technologies Used

- HTML, CSS, JavaScript
- WAQI API for air quality data

## Setup and Installation

### Prerequisites

1. A modern web browser (e.g., Chrome, Firefox, Safari)
2. An API token from the WAQI API

### Getting the WAQI API Token

1. Go to the [WAQI API Signup Page](https://aqicn.org/data-platform/token/).
2. Register for an account if you don’t have one.
3. After registering, go to the API section in your account and generate an API token.
4. Copy the token; you will need it in the next step.

### How to Use the AQI Checker

1. Replace the `token` variable in the JavaScript code with your WAQI API token.
   ```javascript
   const token = 'YOUR_API_TOKEN_HERE';
   ```
2. Open the `index.html` file in a web browser.
3. Enter a city name (e.g., "Lahore") and click "Check AQI".
4. View the AQI information, health recommendations, and historical data.

### Example Usage

The AQI Checker app will display the AQI level, the main pollutant, and provide an activity recommendation based on the AQI level. It also includes a table with historical PM2.5 data.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the MIT License.
