# Weather App 🌤️

A live weather app that shows current conditions for any city in the world, built with **Astro** and the **[Open-Meteo API](https://open-meteo.com)**.

## 🔗 Live Demo

**[https://projects.archieinnit.kdns.fr/weather/](https://projects.archieinnit.kdns.fr/weather/)**

## ✨ Features

- **Search any city** in the world
- Auto-detects coordinates using Open-Meteo's geocoding API
- Shows **current temperature**, condition, and emoji icon
- **Feels-like** temperature, **humidity**, and **wind speed**
- **°C / °F toggle**
- **Dynamic background** that changes based on weather
- **Graceful error handling**
- Auto-loads Nairobi on first visit

## 🛠️ Tech Stack

- Astro
- Vanilla JavaScript (fetch, async/await)
- Open-Meteo API (no API key needed!)

## 🚀 Run Locally

```bash
git clone https://github.com/joblomint/weather-app.git
cd weather-app
npm install
npm run dev
