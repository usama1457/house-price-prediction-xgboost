# 🏡 House Price Prediction using XGBoost

## 📌 Overview
This project is a machine learning regression model that predicts house prices based on various housing features. The model uses **XGBoost Regressor**, a powerful gradient boosting algorithm, to learn complex relationships between features and target values.

---

## 🎯 Problem Statement
House prices depend on multiple factors such as crime rate, number of rooms, tax rate, and location-based indicators. The goal of this project is to build a predictive model that can estimate house prices accurately using historical data.

---

## 📊 Dataset
- **Source:** Boston Housing Dataset (`boston.csv`)
- **Type:** Regression dataset
- **Target Variable:** `MEDV` (Median house price)

### Features include:
- Crime rate
- Average number of rooms
- Property tax rate
- Distance to employment centers
- Socioeconomic indicators

---

## 🛠️ Technologies Used
- Python 🐍
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## 🔍 Project Workflow

### 1. Data Loading & Inspection
- Loaded dataset using Pandas
- Checked shape, missing values, and statistical summary

### 2. Exploratory Data Analysis (EDA)
- Generated correlation matrix
- Visualized feature relationships using heatmap
- Identified important features affecting house prices

### 3. Data Preprocessing
- Split dataset into features (X) and target (Y)
- Performed train-test split (80% training, 20% testing)

### 4. Model Training
- Used **XGBoost Regressor**
- Trained model on training dataset
- Learned patterns between features and house prices

### 5. Model Evaluation
Evaluated using:
- **R² Score** (accuracy measure)
- **Mean Absolute Error (MAE)** (average prediction error)

### 6. Visualization
- Plotted Actual vs Predicted values for both training and test sets
- Evaluated model performance visually

---

## 📈 Results
- The model achieved strong predictive performance on unseen data.
- XGBoost effectively captured non-linear relationships in the dataset.
- Visualization showed good alignment between actual and predicted prices.

---

## 📊 Model Performance Metrics
- R² Score: High accuracy on both training and test data
- MAE: Low average prediction error

---

## 💡 Key Learnings
- Understanding full machine learning pipeline (EDA → Training → Evaluation)
- Feature relationship analysis using correlation heatmaps
- Practical implementation of XGBoost for regression problems
- Importance of evaluation metrics in model validation

---

## 🚀 Future Improvements
- Hyperparameter tuning for better accuracy
- Feature engineering to improve predictions
- Comparison with other models (Random Forest, LightGBM)
- Deployment using Flask or Streamlit

---

## 📂 How to Run
```bash
# Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn xgboost

# Run the notebook or script
python house_price_prediction.py
