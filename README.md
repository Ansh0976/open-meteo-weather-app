# Weatherly

A polished, responsive weather dashboard built as a single `index.html` file. Search for a city to see live current conditions and a five-day outlook, with Tokyo shown by default.

## Features

- Live current weather and daily forecasts from the [Open-Meteo API](https://open-meteo.com/), with no API key or account required.
- City search powered by the Open-Meteo geocoding API.
- Current-location weather using your browser's location permission.
- Hardcoded sample forecast when live weather cannot be loaded.
- Weather-specific icons, compact forecast cards, and light/dark themes that follow your system preference.
- Responsive layout, keyboard-friendly search, and accessible status updates.
- No framework, server, build step, or dependencies.

## Run it

Open `index.html` directly in a modern browser. An internet connection is needed for live city search and weather data; the sample forecast is used when the weather request fails.

## Data and attribution

Weather forecasts are provided by [Open-Meteo](https://open-meteo.com/). Geocoding uses the [Open-Meteo Geocoding API](https://open-meteo.com/en/docs/geocoding-api). Forecast temperatures are shown in Celsius and wind speed in km/h.

## License

This project is released under the MIT License. See [LICENSE](LICENSE).
