# Weather App
A simple, responsive weather application built using HTML, CSS, and JavaScript. This app allows users to search for the current weather in any city worldwide and displays relevant data like temperature, humidity, wind speed, and more.

## Features
- Real-Time Weather Data: Get up-to-date weather information for any city worldwide.
- Responsive Design: Works seamlessly across devices, from desktops to mobiles.
- Interactive UI: Clean and user-friendly interface designed with HTML and CSS.
- API Integration: Fetches live weather data from a weather API.
## Technologies Used
- HTML: Structure of the app
- CSS: Styling and layout
- JavaScript: Functionality and API integration
## Functionality
# API Integration
- The app integrates with a weather API to fetch real-time weather information. This allows users to see updated weather conditions for any entered city.

## Axios for API Requests
Axios is a popular JavaScript library used to make HTTP requests. In this app, Axios is used to fetch data from the weather API, which provides the weather information in JSON format. Here’s a breakdown of its key features:

- Promise-Based: Axios uses promises, making it easy to handle asynchronous requests.
- Error Handling: Provides built-in error handling for more robust API calls.
- Automatic JSON Parsing: Axios automatically parses JSON responses, making it easier to work with the data.

## Additional Functionalities
- User Input Handling: JavaScript listens for user input and fetches weather data when a city name is entered.
- Data Parsing: The app extracts key weather information such as temperature, humidity, wind speed, and condition descriptions from the JSON response.
