# Group62-AI-for-Sustainable-Development-Week-2

# AI-Machine-Learning-Assignment

# 🌾 AI for Sustainable Development: Crop Yield Prediction

## 🚀 Overview

This project is part of the **AI for Sustainable Development** Week 2 assignment. It focuses on **SDG 2: Zero Hunger**, using machine learning to predict crop yields based on soil and weather features. Accurate crop yield prediction helps farmers, policymakers, and agricultural planners make informed decisions to combat hunger and improve food security.

---

## 🎯 Goal

**Predict crop yield** using soil nutrients (N, P, K), temperature, rainfall, and fertilizer data through a supervised machine learning model.

---
## 📊 Dataset

- **Source**: [Kaggle - Crop Yield Prediction Using Soil and Weather](https://www.kaggle.com/datasets/gurudathg/crop-yield-prediction-using-soil-and-weather)
- **Format**: CSV
- **Features**:
  - Nitrogen (N)
  - Phosphorus (P)
  - Potassium (K)
  - Temperature
  - Humidity
  - Rainfall
  - Fertilizer Used
  - Yield (Target)

---

## 🧠 Machine Learning Approach

- **Type**: Supervised Learning
- **Model Used**: Random Forest Regressor
- **Evaluation Metrics**:
  - MAE (Mean Absolute Error)
  - R² Score

---

## 🔍 Results

- R² Score: ~0.87 (example value; varies by run)
- Key predictors: Rainfall, Fertilizer Used, Nitrogen (N)
- Visualization: Scatter plot of actual vs predicted yield and feature importance chart

![Scatter Plot](screenshots/actual_vs_predicted.png)
![Feature Importance](screenshots/feature_importance.png)

---

## 📁 Project Structure

```bash
.
├── crop_yield.csv               # Dataset file
├── crop_yield_prediction_notebook.py  # Python notebook
├── README.md                    # Project overview
└── screenshots/                 # Folder for visual outputs
