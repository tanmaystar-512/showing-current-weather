# showing current weather 
This is a simple weather widget that displays the current weather conditions, temperature, and location using the OpenWeather API. The widget is styled with CSS and fetches weather data dynamically using JavaScript.

## Features

- Displays the current temperature, weather condition, and location.
- Fetches real-time weather data from the OpenWeather API.
- Allows users to refresh the weather data with a button click.

## How to Use

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in your browser.
3. By default, the widget fetches weather data for Jaipur. To see the weather for your city:
   - Open the `index.html` file in a text editor.
   - Locate the following line in the JavaScript code:
     ```javascript
     const response = await fetch('https://api.openweathermap.org/data/2.5/weather?q=jaipur&units=metric&appid=2992ed6018ba6464cd8e888b828246c0');
     ```
   - Replace `q=jaipur` with `q=your_city_name`. For example, to fetch weather data for London:
     ```javascript
     const response = await fetch('https://api.openweathermap.org/data/2.5/weather?q=london&units=metric&appid=2992ed6018ba6464cd8e888b828246c0');
     ```
4. Save the changes and refresh the browser to see the updated weather data.

## Prerequisites

- A valid API key from [OpenWeather](https://openweathermap.org/). Replace the `appid` value in the fetch URL with your own API key.

## Example

Here is an example of how the widget looks:

![Weather Widget Screenshot](https://via.placeholder.com/350x200.png?text=Weather+Widget)

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeather API

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.

## Acknowledgments

- [OpenWeather API](https://openweathermap.org/) for providing weather data.
