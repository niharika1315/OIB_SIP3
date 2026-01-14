# OIB_SIP3
# Basic Weather App (Python)

The **Basic Weather App** is a Python project that fetches, analyzes, and visualizes weather data using the **OpenWeatherMap API**.  
All functionality is documented in this **single README.md file**, covering every program included in the project.

This project demonstrates a progression from **basic command-line applications** to **advanced data visualization**, making it ideal for learning and portfolio use.

---

## Project Contents 

This project contains **four weather programs**:

1. **Current Weather Application (CLI)**
2. **5-Day Temperature Forecast Visualization**
3. **Weather Condition Distribution Analysis**
4. **Temperature & Humidity Forecast Comparison**

Each script runs independently but together forms the **Basic Weather App**.

---

## Technologies Used

- **Python 3**
- **Requests** – API requests
- **Matplotlib** – Data visualization
- **Collections (Counter)** – Data aggregation
- **OpenWeatherMap API**

---

## Project Structure

basic-weather-app/
│
├── current_weather.py
├── forecast_temperature_plot.py
├── weather_condition_distribution.py
├── temperature_humidity_forecast.py
└── README.md
---
## API Key Setup (Required)

The application uses the **OpenWeatherMap API**.

### Step 1: Get an API Key
Create a free account at:
https://openweathermap.org/api

### Step 2: Set API Key as an Environment Variable

**Windows (PowerShell):**
```powershell
setx OPENWEATHER_API_KEY "your_api_key_here"

##
#  Program Usage (All Included)
1️⃣ Current Weather App (CLI)

Fetches and displays live weather data for a city entered by the user.

Information Displayed:

Temperature (°C)

Feels-like temperature

Humidity

Wind speed

Weather condition

2️⃣ 5-Day Temperature Forecast Visualization

Visualizes temperature changes over the next 5 days using forecast data (3-hour intervals).

3️⃣ Weather Condition Distribution Analysis

Analyzes and visualizes how often different weather conditions occur over a 5-day period.

4️⃣ Temperature & Humidity Forecast Comparison

Compares temperature and humidity using dual Y-axes for accurate visualization.

