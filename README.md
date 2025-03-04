# Weather App

A simple web-based Weather App that retrieves and displays current weather data for a user-specified location using the OpenWeatherMap API. The application is built with HTML, CSS, and JavaScript, featuring a modern, responsive design and a visually appealing interface.

---

## Features

- **Search by Location:**  
  Enter the name of a city to retrieve current weather information.
  
- **Weather Details:**  
  Displays temperature (in Celsius), weather condition (e.g., cloudy, clear), humidity, and wind speed.
  
- **Weather Icons:**  
  Uses OpenWeatherMap icons to visually represent weather conditions.
  
- **Responsive Design:**  
  A full-screen background image with a centered search card provides a modern and immersive user experience.

---

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, etc.)
- An active OpenWeatherMap API key

## How It Works

## User Input:
The user enters a city name in the search input field and submits the form.

## API Request:
The JavaScript function constructs a URL using the provided city name and API key, then fetches the weather data from the OpenWeatherMap API.

## Data Processing:
The app converts the temperature from Kelvin to Celsius and extracts other key details such as humidity and wind speed.

## UI Update:
The weather data is dynamically inserted into the page, updating the main content area with weather details and relevant icons.

## Error Handling:
The application ensures that empty input values are not processed, and proper error handling is in place for the API fetch process.