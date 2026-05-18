# Sante Price Index

## 📌 Overview
Sante Price Index is an Android application developed to help small-scale vendors in weekly village markets (Santes) calculate fair and profitable selling prices for their products. The application bridges the gap between wholesale market prices (Mandis) and local retail pricing by providing vendors with price intelligence, profit calculation, and market trend awareness.

The project focuses on improving financial decision-making for vendors through a simple, user-friendly, and high-contrast interface suitable for outdoor market conditions.

---

## 🚀 Features

### 📊 Daily Mandi Price Watch
- Displays mandi prices for essential commodities such as Onion, Tomato, and Potato.
- Helps vendors understand current market conditions.

### 🧮 Profit & RRP Calculator
- Calculates Recommended Retail Price (RRP) using:
  - Wholesale Cost
  - Transport Cost
  - Waste Percentage
  - Profit Margin

### 🪧 Digital Price Board
- Full-screen high-contrast display mode.
- Yellow-on-black interface for better readability in outdoor environments.

### 📈 Trend Analysis
- Provides simulated market trend insights.
- Displays possible price rise/fall indications.

### 💡 Financial Awareness
- Helps vendors understand profit calculations and pricing strategy.

---

## 🛠️ Technologies Used

- Kotlin
- Jetpack Compose
- Android Studio
- Material Design 3
- Navigation Compose
- Firebase Firestore *(optional integration)*
- Room Database *(optional offline storage)*
- Git & GitHub

---

## 📂 Project Structure

```text
screens/
 ├── HomeScreen.kt
 ├── CalculatorScreen.kt
 ├── MarketPriceScreen.kt
 └── DigitalSlateScreen.kt

utils/
 └── PriceCalculator.kt

data/
 └── Product.kt
