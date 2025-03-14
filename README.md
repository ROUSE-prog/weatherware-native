# Weatherware 2.0 (React Native)

## 🌦️ Overview
Weatherware 2.0 is a React Native app that provides real-time weather updates and suggests outfit recommendations based on the weather conditions. This is a mobile-friendly evolution of the original [Weatherware](https://whatweatherware.netlify.app/).

## 📁 Project Structure
```
weatherware-native/
│── assets/             # Images, icons, and fonts
│── components/         # Reusable UI components
│── screens/            # Screens (Home, Settings, etc.)
│── services/           # API calls (e.g., Weather API)
│── utils/              # Utility functions (helpers)
│── hooks/              # Custom hooks (e.g., useWeather)
│── App.js              # Main entry point
│── app.json            # Expo configuration
│── package.json        # Dependencies
│── README.md           # Documentation
```

## 🚀 Getting Started

### Prerequisites
- Install **Node.js** (latest LTS version recommended)
- Install **Expo CLI**:
  ```sh
  npm install -g expo-cli
  ```
- Install **Git** (if not installed already)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/ROUSE-prog/weatherware-native.git
   cd weatherware-native
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the Expo development server:
   ```sh
   npx expo start
   ```
4. Scan the QR code using **Expo Go** (available on iOS & Android) or run the app on a simulator/emulator.

## 🔥 Features
- 📍 **Real-time Weather Data** (via OpenWeather API)
- 👕 **Outfit Suggestions** based on the weather
- 📍 **Location-Based Forecasting** (GPS integration)
- 🎨 **Modern UI with Glassmorphism Design**
- ⚡ **Optimized for Performance**

## 📌 Roadmap
- [ ] Setup basic app UI
- [ ] Integrate weather API
- [ ] Implement outfit suggestion logic
- [ ] Improve UI with animations and effects
- [ ] Deploy on App Store & Play Store

## 🤝 Contributing
Feel free to fork the repo, create a new branch, and submit a pull request!

## 📜 License
This project is licensed under the MIT License.

---
**Author:** [Steven Rouse](https://github.com/ROUSE-prog)
