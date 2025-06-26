# 🌤️ Weather App

A sleek and responsive weather web application that allows users to search for real-time weather data by city name. Built with HTML, CSS, and JavaScript, this project fetches live weather data from the OpenWeatherMap API and displays temperature, weather conditions, humidity, and wind speed — with dynamic weather icons based on current conditions.

![Weather App Screenshot]-
<img width="553" alt="Screenshot 2025-06-25 at 11 47 23 PM" src="https://github.com/user-attachments/assets/38f5254f-1099-4802-ac65-2d92dceb9564" />

## 🚀 Features

- 🔎 Search by city name
- 🌡️ Live temperature display in Celsius
- 💧 Real-time humidity
- 💨 Wind speed updates
- 🌤️ Dynamic weather icon (Clear, Clouds, Rain, Drizzle, Mist)
- 📱 Fully responsive UI
- 🎨 Gradient card design with soft visuals

## 🛠️ Tech Stack

- **HTML5** – Structure of the app
- **CSS3** – Styling and layout (custom gradients, card-based UI)
- **JavaScript (ES6+)** – Logic, API fetching, and dynamic rendering
- **OpenWeatherMap API** – Source of weather data

## 🔧 How It Works

1. User types a city name into the search bar.
2. JavaScript fetches weather data from the OpenWeatherMap API using `fetch()`.
3. If the city is found, the app dynamically updates:
   - Temperature (`°C`)
   - Weather description (e.g., "Clouds", "Clear")
   - Humidity (%)
   - Wind speed (mph)
   - Weather icon changes accordingly
4. If the city is not found, a graceful alert is shown.

## 🖼️ UI Preview

![Weather App Preview] <img width="509" alt="Screenshot 2025-06-25 at 11 48 17 PM" src="https://github.com/user-attachments/assets/b3482486-59ef-4158-8f61-0227f42c5a8b" />

## 🌐 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app
