# 🌤️ Weather Web Application

A basic weather-checking website developed while learning Python and Flask. This web app allows users to enter a city name and view its current weather conditions in a clean and minimal interface.

---

## 🔍 Features

- Enter any city to check the current weather.
- Displays:
  - Temperature (`°C`)
  - Weather condition (e.g., Cloudy, Sunny)
  - Feels like temperature
- Shows a fallback page if the city is not found.
- Clean, responsive design using basic HTML and CSS.

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS (Vanilla)
- **Backend:** Python, Flask
- **API Used:** [OpenWeatherMap](https://openweathermap.org/current)

---

## 📁 File Structure

weatherwebapplication/
├── templates/
│ ├── index.html # Home page
│ ├── weather.html # Weather results
│ └── city_not_found.html # Error page if city not found
├── static/
│ └── styles/
│ └── style.css # Basic CSS styling
├── server.py # Flask app
├── weather.py # Handles API requests
├── .env # Stores the OpenWeatherMap API key
