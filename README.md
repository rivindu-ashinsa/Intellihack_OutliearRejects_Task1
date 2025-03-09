# 🌦️ Weather Forecasting using Machine Learning

![Project Status](https://img.shields.io/badge/Status-Active-green) 
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Supervised-orange)
![License](https://img.shields.io/badge/License-MIT-brightgreen)

## 📌 Overview  
This project aims to predict **daily rainfall probability** based on historical weather data using **machine learning models**. The dataset includes weather parameters such as temperature, humidity, wind speed, cloud cover, and pressure. The final model predicts whether it will rain on a given day, helping businesses and individuals make data-driven decisions.

## 🚀 Features  
- **Data Preprocessing**: Handles missing values, outliers, and feature scaling.  
- **Exploratory Data Analysis (EDA)**: Visualizes trends and correlations.  
- **Machine Learning Model**: Trains multiple models and selects the best one.  
- **Hyperparameter Tuning**: Uses GridSearchCV for optimization.  
- **Real-time Predictions**: Designed for API integration with IoT sensor data.  

---

## 📂 Project Structure  
```bash
📦 Weather-Forecasting
│── weather_data.csv       # Raw & Processed Datasets
│── Intellihack_q1.ipynb   # Jupyter Notebooks for EDA, Data cleaning, feature engineering, & Model Training
│── models/                # Saved ML Models
│── requirements.txt       # Required Python Packages
│── README.md              # Project Documentation
│── report.pdf             # Detailed Report (if applicable)
```

# 📊 Dataset  

The dataset consists of **296+ daily observations** with the following features:  

- **avg_temperature (°C)**  
- **humidity (%)**  
- **avg_wind_speed (km/h)**  
- **cloud_cover (%)**  
- **pressure (hPa)**  
- **rain_or_not** (Binary: `1 = Rain`, `0 = No Rain`)  

## 📌 Correlation Insights:  

- **Humidity & temperature** are highly correlated with rain.  
- **Wind speed** has minimal impact on rain prediction.

## 📌 Installation & Setup  

### 🔧 1️⃣ Prerequisites  

Ensure you have **Python 3.8+** installed. Then, install the required dependencies:  

```bash
pip install -r requirements.txt
```


# ⚙️ System Architecture  

The system is designed to work with **real-time IoT sensor data**.  

## 🔹 Data Flow:  

1️⃣ **IoT Sensors & APIs** → 2️⃣ **Data Cleaning & Storage** → 3️⃣ **ML Model Prediction** → 4️⃣ **API & Dashboard**  

📌 _(Check the `report.pdf` for a detailed system diagram.)_  


## 🔮 Future Improvements  

- 🔹 **Deploy the model using Flask/FastAPI for real-time predictions**  
- 🔹 **Implement LSTM for time-series forecasting**  
- 🔹 **Optimize data pipeline for large-scale weather data**  

## 📜 License  

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.  

