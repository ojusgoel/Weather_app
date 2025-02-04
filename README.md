# Weather App

This project fetches and stores historical weather data for a given location and date range, making it persistent using an SQLite database. Users can retrieve stored weather data and export it to a CSV file.

## Features
- Fetch historical weather data for a location using Open-Meteo API
- Store fetched data in an SQLite database
- Retrieve stored weather data for a location
- Export stored data to a CSV file
- Validate location before fetching data

## Installation
1. Clone this repository:
   ```bash
   git clone <repository_url>
   cd weather-app
   ```

2. Install required dependencies:
   ```bash
   pip install requests sqlite3 pandas
   ```

## Usage
1. Run the script:
   ```bash
   python Weather_app.py
   ```
2. Follow on-screen prompts to:
   - Fetch and store weather data
   - Read stored data
   - Export data to CSV

## API Key
- The project requires an Open-Meteo API for fetching weather data.
- Ensure you have internet access while fetching data.

## Exporting Data to CSV
- To export stored weather data to a CSV file, use the `export_to_csv` function.
- The exported file will be saved as `weather.csv` in the project directory.

## Technologies Used
- Python
- SQLite
- Requests (for API calls)
- Pandas (for exporting CSV)

## License
This project is licensed under the MIT License.
