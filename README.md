# Weatherly

A polished, responsive weather dashboard built as a single `index.html` file. Search for a city to see live current conditions and a five-day outlook, with Tokyo shown by default.

## Features

- Live current weather and daily forecasts from the [Open-Meteo API](https://open-meteo.com/), with no API key or account required.
- City search powered by the Open-Meteo geocoding API.
- Current-location weather using your browser's location permission, with a city-level place name from BigDataCloud reverse geocoding.
- Hardcoded sample forecast when live weather cannot be loaded.
- Weather-specific icons, compact forecast cards, and light/dark themes that follow your system preference.
- Responsive layout, keyboard-friendly search, and accessible status updates.
- No framework, server, build step, or dependencies.

## Run it

Open `index.html` directly in a modern browser. An internet connection is needed for live city search and weather data; the sample forecast is used when the weather request fails.

## Data and attribution

Weather forecasts are provided by [Open-Meteo](https://open-meteo.com/). City search uses the [Open-Meteo Geocoding API](https://open-meteo.com/en/docs/geocoding-api); location-based place names use [BigDataCloud reverse geocoding](https://www.bigdatacloud.com/docs/reverse-geocoding/reverse-geocode-to-city-api). When you choose **My location**, your browser obtains your coordinates and sends them to Open-Meteo for weather and BigDataCloud for the city-level place name. City names are approximate to the returned locality and are not a street address. Forecast temperatures are shown in Celsius and wind speed in km/h.

## License

This project is released under the MIT License. See [LICENSE](LICENSE).
