# 🌦️ PyQt5 Weather App

A simple application for displaying current weather data for a specified city, built with **Python, PyQt5, and OpenWeather API**.

## 🖥️ Application Overview

The application allows users to enter a city name and retrieve information about:
- 🌡️ Temperature (in Celsius degrees)
- 🌤️ Weather description
- ⛅ Animated emoji representing weather conditions

## 🚀 Installation and Setup

### 📥 1. Clone the Repository
```bash
git clone https://github.com/yourusername/weather-app.git
cd weather-app
```

### 📦 2. Install Dependencies
Make sure you have **Python 3** installed and run the following command:
```bash
pip install -r requirements.txt
```

### 🔑 3. Set Up the API Key
- Create a `.env` file in the root folder.
- Add your **OpenWeather API key**:
```plaintext
API_KEY=your_openweather_api_key
```

### ▶️ 4. Run the Application
```bash
python main.py
```

## 📌 Usage
1. Enter the city name.
2. Click the "Get Weather" button.
3. View the temperature, weather description, and an emoji representing the weather conditions.

## 🛠️ Technologies Used
- **Python 3**
- **PyQt5** (for GUI interface)
- **Requests** (for API communication)
- **dotenv** (for securely storing the API key)
- **OpenWeather API** (for fetching weather data)

## 🖼️ Screenshot
![Screenshot 2025-03-24 221917](https://github.com/user-attachments/assets/1796067c-049e-4fd0-b0ce-84e91f81463c)

## 🐞 Possible Issues
- If you receive a **401 Unauthorized** error, check if your API key is correct.
- If you receive a **404 Not Found** error, ensure the city name is correct.
- If the application does not launch the GUI, verify that **PyQt5** is installed.



