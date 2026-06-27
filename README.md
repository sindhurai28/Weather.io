

# 🌦️ Weather Analytics Dashboard

A modern **React-based Weather Analytics Dashboard** that displays real-time weather data and is designed to scale toward advanced analytics such as forecasts, historical trends, and interactive visualizations.

This project is built as part of a **Frontend Assignment** to demonstrate React fundamentals, API integration, clean project structure, and professional documentation practices.

---
## 🚀 Features

### ✅ Implemented
- 🔍 Search weather by city name  
- 🌡️ Display current temperature and weather conditions  
- 💨 Show humidity and wind speed  
- 🌐 Real-time weather data via external API  
- ⚛️ React functional components with Hooks  
- 📱 Responsive UI  

### 🧩 Planned Enhancements
- 📊 Multi-city dashboard  
- 📅 5–7 day forecast  
- ⏱️ Hourly forecast  
- ⭐ Favorite cities with persistence  
- 📈 Interactive charts (temperature, precipitation, wind)  
- 🌡️ Celsius ↔ Fahrenheit toggle  
- 🗂️ Redux Toolkit  
- ⚡ Caching & auto-refresh  
- 🔐 Authentication (Google Sign-In)  

---

## 🛠️ Tech Stack

- **Frontend:** React, JavaScript (ES6+), HTML5, CSS3  
- **API:** OpenWeatherMap / WeatherAPI  
- **State Management:** React Hooks  
- **HTTP Client:** Fetch API / Axios  
- **Tooling:** Node.js, npm, Git, GitHub  

---

## 📁 Project Structure

The project follows a modular and scalable folder structure:

Weather-App/
├── public/
├── src/
│ ├── components/ # Reusable UI components
│ ├── App.js # Root application component
│ ├── index.js # Entry point
│ └── styles.css # Global styles
├── package.json # Dependencies & scripts
├── .gitignore
└── README.md


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/wildtigress/Weather-App.git
2️⃣ Navigate to the project directory
cd Weather-App
3️⃣ Install dependencies
npm install
4️⃣ Configure API Key
Create a .env file in the root directory:

REACT_APP_WEATHER_API_KEY=YOUR_API_KEY_HERE
▶️ Available Commands
All commands should be run from the project root directory.

🔹 Start development server
npm start
Runs the app in development mode at:

http://localhost:3000
🔹 Run tests
npm test
Launches the test runner in interactive watch mode.

🔹 Build for production
npm run build
Creates an optimized production build in the build/ folder.

🔹 Eject configuration (not recommended)
npm run eject
⚠️ This is a one-way operation and should be used only if customization is required.

🧠 Application Workflow
User enters a city name

API request is sent to the weather service

Real-time weather data is returned

Data is displayed dynamically in the UI

📊 API Integration
The application fetches live weather data such as:

Current temperature

Weather condition

Humidity

Wind speed

Supported providers:

OpenWeatherMap

WeatherAPI

🎯 Project Objective
The objective of this project is to build a Weather Analytics Dashboard that:

Displays real-time weather information

Helps users understand short-term weather conditions

Lays the groundwork for long-term trend analysis and data visualization

The architecture is intentionally extensible for future analytics features.

🤝 Contribution
Contributions are welcome.

Fork the repository

Create a feature branch

git checkout -b feature-name
Commit changes

Push to your fork

Open a Pull Request

📜 License
This project is licensed under the MIT License.

👩‍💻 Author
sindhu kumari
GitHub: https://github.com/sindhurai28

