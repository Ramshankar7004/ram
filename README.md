# Weather Web App

## Overview

**Weather Web App** is a simple web application that provides weather information for any location using the OpenWeather API. Users can search for a city and receive real-time weather data, including temperature, humidity, and weather conditions.

## Features

- **Current Weather Data**: Display current temperature, humidity, and weather conditions.
- **Location Search**: Search for weather information by city name.
- **Weather Icons**: Show weather conditions with appropriate icons.

## Technologies Used

- **HTML/CSS**: For structure and styling.
- **JavaScript**: For interacting with the OpenWeather API and handling user input.
- **OpenWeather API**: Provides real-time weather data.

## Getting Started

To get started with the Weather Web App, follow these steps:

### Prerequisites

- A web browser to view the application.
- An API key from OpenWeather. You can get one by signing up at [OpenWeather](https://openweathermap.org/).

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/weather-web-app.git
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd weather-web-app
    ```

3. **Open the Project in Your Browser**:
    - Open `index.html` in your preferred web browser to view the application.

### Configuration

1. **API Key**: Replace `YOUR_API_KEY` in `script.js` with your actual OpenWeather API key.
    ```javascript
    const apiKey = 'YOUR_API_KEY';
    ```

### Usage

1. **Open the Application**: In your web browser, open the `index.html` file.
2. **Search for a City**: Enter a city name in the search field and click the "Get Weather" button.
3. **View Weather Data**: The application will display the current weather information for the specified city.

## Example

Here's an example of how the weather information is displayed:

- **City**: New York
- **Temperature**: 75°F
- **Humidity**: 65%
- **Weather**: Clear sky
- **Icon**: ![Clear sky](http://openweathermap.org/img/wn/01d.png)

## Contributing

Contributions are welcome! To contribute to the Weather Web App:

1. **Fork the Repository**.
2. **Create a New Branch**:
    ```bash
    git checkout -b feature/your-feature-name
    ```

3. **Make Your Changes** and **Commit** them:
    ```bash
    git add .
    git commit -m "Add feature: your feature description"
    ```

4. **Push to Your Fork**:
    ```bash
    git push origin feature/your-feature-name
    ```

5. **Create a Pull Request** on GitHub.
