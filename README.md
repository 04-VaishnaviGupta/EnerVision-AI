# ⚡ EnerVision AI – Smarter Solar Solutions

**EnerVision AI** is an intelligent, AI-powered platform designed to help users make data-driven decisions about solar panel installations. It combines machine learning, real-time weather integration, and interactive dashboards to offer personalized solar energy recommendations, cost analysis, and sustainability metrics.

---

## 🚀 Key Features

### 🔍 Solar Panel Requirement Estimation
- **Algorithm Used**: Implements **Random Forest Regression (RFR)** after comparing with **Stochastic Gradient Descent (SGD)** and **Multi-Layer Perceptron (MLP)**, selected for its superior performance.
- **Dataset**: Trained on a curated dataset containing solar output, weather patterns, and geolocation data.
- **Preprocessing**: Normalization, missing value imputation, and feature selection applied to enhance prediction accuracy.
- **Tuning**: Hyperparameters optimized using **Grid Search** to fine-tune model performance.
- **Metrics**: Evaluated using **R² Score**, **Mean Absolute Error (MAE)**, and **Root Mean Squared Error (RMSE)**.

### ⚡ Energy Consumption Forecasting
Forecasts future energy usage based on user inputs and historical patterns to assist in precise planning.

### ☁️ Real-Time Weather Insights
Integrates live weather data to predict solar panel output, enabling users to make smarter energy management decisions.

### 📈 ROI & Financial Dashboard
Provides visual insights and analysis:
- Daily energy production
- Monthly consumption
- Installation costs
- Estimated savings and return on investment

### 💰 Installation Cost Calculator
Estimates the total cost of installing solar panels based on region, usage, and solar exposure.

### 🌍 Carbon Footprint Estimator
Calculates CO₂ savings from switching to solar energy, promoting sustainability and awareness.

---

## 🧰 Technologies Used

### 🔢 Machine Learning
- **Models**: Random Forest Regression (RFR), Stochastic Gradient Descent (SGD), Multi-Layer Perceptron (MLP)
- **Evaluation**: R² Score, MAE, RMSE

### 🖥️ Frontend
- HTML, CSS, JavaScript

### ⚙️ Backend
- Node.js
- Firebase Authentication
- MongoDB

### 🌐 APIs Integrated
- **OpenWeather API** – Live weather forecasting
- **Geocode API** – Location-based solar data
- **NASA Peak Sun Hours API** – Daily solar radiation data

---

## 🧱 System Architecture

### Frontend
Built using **HTML**, **CSS**, and **JavaScript** to deliver a clean, responsive interface.

### Backend
- Powered by **Node.js** for server-side operations.
- Uses **Firebase Authentication** for secure login and user management.
- **MongoDB** is used to store project and user-specific data.

### API Integrations
Real-time external APIs improve solar prediction accuracy and enhance user experience.

---

## 🔧 Getting Started

Follow these steps to run the project locally:

```bash
# Step 1: Clone the repository
git clone https://github.com/soumya-1712/radiant-future-ai.git

# Step 2: Navigate to the project folder
cd radiant-future-ai

# Step 3: Install dependencies
npm install

# Step 4: Run the application
npm start
```
Open your browser and go to:  
`http://localhost:3000`

## Final Thoughts

EnerVision AI bridges the gap between solar energy potential and real-world use. It helps homeowners, businesses, and sustainability advocates make smart, eco-friendly, and cost-effective energy decisions.

## License

This project is licensed under the MIT License.

