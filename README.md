


https://github.com/user-attachments/assets/588cb8a9-45ee-4762-ab35-e02dd653ff3b


# 🌦️ WeatherWorld Mobile App

📝 **Contents**
- [Introduction](#introduction)
- [Technology Stack](#technology-stack)
- [App Features](#app-features)
- [Directory Structure](#directory-structure)
- [How to Run](#how-to-run)
- [API Key Management](#api-key-management)
- [Contribution Guidelines](#contribution-guidelines)
- [Get in Touch](#get-in-touch)

## 🗺️ Introduction
The **WeatherWorld Mobile App** is a versatile, cross-platform application that delivers real-time weather updates and detailed forecasts for locations across the globe, powered by the OpenWeatherMap API.

## 💻 Technology Stack
- **Flutter**: The primary SDK used for crafting the application.
- **Dart**: The programming language behind the app.
- **Provider**: State management solution to handle app state efficiently.
- **HTTP**: Utilized for making network requests to fetch weather data.

## 👀 App Features
- **Live Weather Data**: Instantly view current weather conditions.
- **Forecasting**: Access both hourly and daily weather forecasts.
- **Favorites**: Save your favorite locations for quick access.
- **Detailed Weather Metrics**: Includes details like wind speed, humidity, and more.

## 🗂️ Directory Structure
- **`/android`** and **`/ios`**: Directories containing platform-specific configurations and native code.
- **`/lib`**: Contains the main application logic and UI components.
  - **`main.dart`**: The app’s entry point.
  - **`homePage.dart`**: The primary screen displaying weather data.
  - **`detailPage.dart`**: Displays detailed weather information for a selected location.
  - **`database_helper.dart`**: Manages local database operations for storing favorite locations.
  - **`dataset.dart`**: Handles data models and the core business logic.
  - **`extraWeather.dart`**: Additional utilities for processing weather data.
  - **`favoriteCitiesScreen.dart`**: Manages and displays the user’s saved favorite cities.
  - **`unit_provider.dart`**: Provides unit conversion functionalities throughout the app.
- **`/assets`**: Directory for images and other static assets.
- **`/test`**: Contains automated tests written in Dart to ensure the app’s stability.

## 🚀 How to Run
1. **Clone the repository:**
    ```bash
    git clone https://github.com/OKihichak/weather_world_mobile_app.git
    cd weather-world_mobile-app
    ```

2. **Install the required dependencies:**
    ```bash
    flutter pub get
    ```

3. **Launch the app:**
    ```bash
    flutter run
    ```

## 🔑 API Key Management
To maintain security, ensure that your API keys are stored in a `.env` file and that this file is listed in your `.gitignore` to prevent it from being tracked by version control.

## 🤝 Contribution Guidelines
Interested in contributing to the project? Here’s how you can get started:

1. **Fork the repository.**
2. **Create a new branch:**
    ```bash
    git checkout -b feature/YourFeatureName
    ```
3. **Commit your changes:**
    ```bash
    git commit -m 'Add YourFeatureName'
    ```
4. **Push to the branch:**
    ```bash
    git push origin feature/YourFeatureName
    ```
5. **Open a pull request** to discuss and merge your changes.

## 📧 Get in Touch
- **Email**: oleg15062005@gmail.com
- **GitHub**: [Oleh Kihichak](https://github.com/OKihichak)
