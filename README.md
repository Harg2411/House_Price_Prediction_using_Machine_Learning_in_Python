# House Price Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting house prices using various machine learning models. The dataset consists of multiple numerical and categorical features related to houses, such as location, size, number of rooms, and other characteristics. The goal is to train a model that can accurately estimate house prices based on these features.

## 📂 Dataset
The dataset used is `HousePricePrediction.xlsx`, which contains:
- **Numerical features**: Square footage, number of bedrooms, number of bathrooms, lot size, etc.
- **Categorical features**: Neighborhood, house style, exterior material, etc.
- **Target variable**: House price

## ⚙️ Dependencies
Ensure you have the following libraries installed before running the project:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn openpyxl
```

## 📊 Exploratory Data Analysis
- Visualizing correlations between numerical features using a heatmap.
- Checking distributions of various attributes.
- Handling missing values and outliers.

## 🏗️ Model Training
The notebook implements and evaluates multiple models:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **XGBoost Regressor**

## 📈 Model Evaluation
The models are assessed using:
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **R² Score**
