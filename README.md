# 🌦️ Weather App

A simple and responsive **Weather App** built using **HTML, CSS, and JavaScript**. The application fetches real-time weather information from the **OpenWeatherMap API** and displays the current weather details based on the city entered by the user.

## 🚀 Features

* 🔍 Search weather by city name
* 🌡️ Display current temperature
* ☁️ Show current weather condition
* 💧 Display humidity
* 🌬️ Display wind speed
* ❌ Show an error message for invalid city names
* 📱 Responsive and clean user interface

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* OpenWeatherMap API

## 📂 Project Structure

```text
Weather-App/
│── index.html
│── style.css
│── images/
│   ├── clear.png
│   ├── clouds.png
│   ├── drizzle.png
│   ├── humidity.png
│   ├── mist.png
│   ├── rain.png
│   ├── search.png
│   └── wind.png
│── README.md
```

## ⚙️ How It Works

1. Enter a city name in the search box.
2. Click the search button.
3. The app sends a request to the OpenWeatherMap API.
4. Weather information is displayed, including:

   * City Name
   * Temperature
   * Weather Condition
   * Humidity
   * Wind Speed
5. If the city name is invalid, an error message is shown.

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/Prabhat-gif/Weather-App.git
```

### Open the Project

Open the project folder in **VS Code**.

### API Key

Create a free account on **OpenWeatherMap**, generate an API key, and replace the following line inside `index.html`:

```javascript
const apiKey = "YOUR_API_KEY";
```

### Run the Project

Simply open `index.html` in your web browser or run it using the **Live Server** extension in VS Code.

## 🔮 Future Improvements

* 5-Day Weather Forecast
* Hourly Forecast
* Current Location Weather
* Dark/Light Mode
* Air Quality Index (AQI)
* Weather Animations


