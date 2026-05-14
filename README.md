> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

# findbusstop

A web app to find nearby bus stops using 5-star open data and Google Maps.

## Demo
https://codeforfukui.github.io/findbusstop/

## Features
- Finds nearby bus stops using your device's location.
- Retrieves bus stop and route information from a 5-star open data source via SPARQL.
- Displays results on an interactive Google Map.
- Supports multiple languages, including English, Japanese, Spanish, and more.

## Usage
This project requires a Google Maps API key to run locally.

1.  **Get an API Key**: Obtain a Google Maps API key from the [Google Cloud Console](https://console.developers.google.com/).
2.  **Set the API Key**: Open `lib/gmap.js` and replace the placeholder value of `API_KEY` with your own.
3.  **Run the App**: Open `index.html` in your web browser.
4.  **Find Stops**: Click the "Nearest" button to search for bus stops around you.
5.  **Navigate**: Use the "Previous" and "Next" buttons to cycle through the search results. Click a map icon to see details.

## Data Sources
- **Bus Stop Data**: [Open Data Portal (ODP)](https://odp.jig.jp/) via its [SPARQL endpoint](https://sparql.odp.jig.jp/).
- **Mapping & Geolocation**: [Google Maps API](https://developers.google.com/maps).

## Credits
This project was created by Taisuke Fukuno ([@taisukef](https://github.com/taisukef)) for [Code for Fukui](https://github.com/codeforfukui).

## License
MIT License — see [LICENSE](LICENSE).