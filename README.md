# cloud based Weather ETL Pipeline
A simple, fully cloud-based data engineering project that extracts weather data from a public API, transforms it using Python, and loads it into a cloud-hosted PostgreSQL database — all from Google Colab. It also exports the data to CSV for easy reporting.

## Project Features
- Extracts real-time weather data using the WeatherAPI
- Transforms JSON data into a clean tabular format using `pandas`
- Loads the data into a local **SQLite** database
- Exports results to `weather_data.csv`
- All code written and tested in **Google Colab**
---
## Technologies Used
- Python
- Google Colab
- pandas
- requests
- sqlite3
- WeatherAPI
---
## Sample Output
CSV files:
- `weather_data.csv`: Final ETL output

## Possible Extensions
- Store data in PostgreSQL (e.g. Supabase or Neon)
- Automate daily runs with GitHub Actions
- Visualize trends using Streamlit or Looker Studio
