# 🌤️ WeatherApp

A simple WPF desktop application built with the MVVM pattern that fetches and displays real-time weather information using the AccuWeather API.

---

## 🛠 Technologies Used

- **WPF (Windows Presentation Foundation)**
- **C#**
- **MVVM Architecture**
- **AccuWeather API**
- **Newtonsoft.Json**
- **Git / GitHub**

---

## 📸 Features

- 🔍 Search for a city using the autocomplete feature
- 🌤 View real-time weather conditions
- 🌡 Display temperature in Celsius
- 🌧 Show weather description and precipitation status
- 🖼️ Display weather icon dynamically from AccuWeather
- ✨ Clean, responsive and user-friendly interface

---

## 🧠 Architecture

This application follows the **MVVM (Model-View-ViewModel)** design pattern:

- **Model**: Contains plain C# classes (City, CurrentConditions, etc.)
- **ViewModel**: Handles API communication and data binding logic
- **View (XAML)**: UI that binds directly to the ViewModel using data binding

---

## 🔌 API Usage

This project uses [AccuWeather's API](https://developer.accuweather.com/) to:

- Fetch city suggestions (`autocomplete`)
- Fetch current conditions using the selected city's key

⚠️ **Note**: Free API keys have daily usage limits (usually 50 requests per day). If the limit is exceeded, the app may return errors or fallback responses.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/WeatherApp.git
2. Open the solution (.sln) in Visual Studio

3. Replace the API_KEY in AccuWeatherHelper.cs with your own

4. Run the project (F5)
