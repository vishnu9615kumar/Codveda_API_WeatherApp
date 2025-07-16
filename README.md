# 🌦️ Weather Info App – Codveda Internship Task 3 (Intermediate Level)

This is a Python-based command-line application that fetches real-time weather data using the Open-Meteo API. Developed as part of the **Codveda Python Internship**, this project demonstrates API integration, error handling, and user interaction.

## 📌 Project Objective

- Take user input for **latitude** and **longitude**
- Fetch live weather data from **Open-Meteo API**
- Display temperature, wind speed, and current time
- Allow user to repeat queries in a loop
- Exit the app anytime by typing `'exit'`

## 🧰 Technologies Used

- Python
- requests library
- Open-Meteo API (No API key required)

## 💡 Features

- Real-time weather data from Open-Meteo
- Clean and user-friendly CLI interface
- Type `exit` to quit the app
- Input validation and exception handling
- Repeated use without restarting the program

## 🖥️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/vishnu9615kumar/Codveda_API_WeatherApp.git
   ```

2. Navigate to the project folder:
   ```bash
   cd Codveda_API_WeatherApp
   ```

3. Install the required Python library:
   ```bash
   pip install requests
   ```

4. Run the script:
   ```bash
   python weather_api_app.py
   ```

## 📸 Sample Output

```
🌦️ Welcome to the Weather Info App
Type 'exit' anytime to quit.

📌 Enter Latitude (or type 'exit'): 24.58
📌 Enter Longitude (or type 'exit'): 73.68

📍 Weather Info for (Lat: 24.58, Lon: 73.68)
🌡️ Temperature: 32.5°C
💨 Wind Speed: 7.2 km/h
🕒 Time: 2025-07-15T17:00

🔁 You can try again or type 'exit' to quit.
```

## 🏁 Task Details

- Task Name: API Integration
- Level: Intermediate (Level 2)
- Internship: Codveda Python Internship
- Status:  Completed
