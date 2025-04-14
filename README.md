# 🌤️ Weather App

A full-stack weather web application that allows users to search for weather information by city using the OpenWeatherMap API. The web application displays a summary of the city in a user-friendly layout. This project securely handles API requests via a custom Node.js backend.

## 🔧 Features

- Search for weather by city
- Temperature, humidity, and weather condition display
- Emoji weather icons based on conditions
- Secure backend to protect API key

## 🔐 API Key Security

API key is securely stored in a `.env` file and only used server-side via the backend (`index.js`). The frontend never directly accesses the OpenWeatherMap API.

## 📸 Screenshot

![Weather app preview](screenshot.png)
