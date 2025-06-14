# 🌾 AI-Based Crop Recommendation System

This project is an **AI-powered crop recommendation system** that suggests the most suitable crop to grow based on various environmental and soil parameters. The system uses an **Artificial Neural Network (ANN)** and provides a simple **Flask-based web interface** for user interaction.

## 🔍 Problem Statement

Farmers often lack reliable, data-driven tools to decide which crops are best suited to their land and climate conditions. This leads to poor yield and inefficient resource use. The goal is to automate crop selection using historical data and AI.

## ✅ Features

- Predicts the best crop based on 7 input features
- Trained ANN model using TensorFlow/Keras
- Flask-based web UI for real-time predictions
- Easy-to-use form for input and output
- Open-source and extensible

## 🛠️ Tech Stack

- **Python 3.x**
- **TensorFlow & Keras** – Model creation and training
- **Flask** – Web framework for deployment
- **Pandas, NumPy, Scikit-learn** – Data preprocessing
- **VS Code** – Development environment

## 📊 Input Parameters

The user provides the following inputs through the web interface:
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature (°C)
- Humidity (%)
- pH
- Rainfall (mm)

## 🤖 Model Details

- **Model Type:** Artificial Neural Network (Sequential)
- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy
- **Accuracy:** ~95% on test data
- **Training/Test Split:** 80/20

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/SWETHA4251/Crop_Recommendation.git
   cd Crop_Recommendation
