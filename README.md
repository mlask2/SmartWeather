# SmartWeather

A weather app built with Flutter that displays real-time weather data and forecasts.

## Features

- Search for weather by city name
- Get weather for current location
- Display real-time weather data:
  - Temperature in Celsius and Fahrenheit
  - Wind speed in km/h and mph
  - Humidity percentage
  - Precipitation level in mm and inches
- 7-day weather forecast:
  - Daily high and low temperatures
  - Expected precipitation percentage
  - Wind speed forecast
  - General weather conditions
- 24-hour forecast:
  - Hourly temperature
  - Hourly precipitation chance
  - Hourly wind speed

## Setup

1. Clone this repository
2. Create a `.env` file in the root directory
3. Add your WeatherAPI key to the `.env` file:
   \`\`\`
   WEATHER_API_KEY=your_weather_api_key_here
   \`\`\`
4. Run `flutter pub get` to install dependencies
5. Run the app with `flutter run`

## API Key

This app uses the [WeatherAPI](https://www.weatherapi.com/) service. You'll need to sign up for a free API key.

## Dependencies

- http: For API requests
- provider: For state management
- intl: For date and number formatting
- geolocator: For getting the user's current location
- flutter_dotenv: For loading environment variables
