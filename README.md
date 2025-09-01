# cloud based Weather ETL Pipeline
A simple, fully cloud-based data engineering project that extracts weather data from a public API, transforms it using Python, and loads it into a cloud-hosted PostgreSQL database — all from Google Colab. It also exports the data to CSV for easy reporting.

## Tech Stack
- Google Colab (no local setup)
- Python (pandas, requests, sqlalchemy)
- WeatherAPI (for real-time weather data)
- ElephantSQL (PostgreSQL DB in the cloud)
- GitHub (version control)

## How It Works
1. **Extract**: Calls WeatherAPI to get current weather data for any city.
2. **Transform**: Cleans and flattens the JSON response using `pandas`.
3. **Load**: Inserts the cleaned data into a PostgreSQL database (ElephantSQL).
4. **Export**: Saves the data as a CSV in the Colab environment.

## Project Structure
├── weather_etl.ipynb # Google Colab Notebook
├── requirements.txt # Python dependencies
├── sample_weather_output.csv # Output sample
└── README.md # Project documentation
