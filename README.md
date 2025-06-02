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
- Basic and clean frontend design using HTML & CSS

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
├── requirements.txt
├──  README.md

---

## 🔐 Environment Variables

Create a '.env' file in the root directory with your API key:
```env
API_KEY=your_openweathermap_api_key
```

---

## **🚀How to Run**

1. Clone the repository
```
git clone https://github.com/SruthiJayaram/weatherwebapplication.git
cd weatherwebapplication
```

2.Create a virtual environment and activate it
```
python -m venv .venv
source .venv/bin/activate    # On Windows: .venv\Scripts\activate
```

3.Install the dependencies
```
pip install --upgrade pip
pip install -r requirements.txt
```

4.Set up your .env file (see above)

5.Run the app
```
python server.py
```

Visit: http://localhost:8000

---

## **🌐Demo**

You can check out the live demo of this weather web app here:
👉 [Click here to view the live demo](https://weatherwebapplication-0thb.onrender.com)

---

## **🙋‍♀️ About Me**

I'm Sruthi, a B.Tech student learning web development and building fun beginner projects like this! 😊
Feel free to check out more at https://github.com/SruthiJayaram

---

## **📄 License**

This project is for educational purposes and does not include any production-level deployment or UI design.
