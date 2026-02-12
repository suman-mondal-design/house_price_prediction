# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict house prices (in lakhs) using Machine Learning techniques.  
The dataset contains real estate property information such as square footage, BHK number, construction status, and geographical location.

The objective is to build a regression model that accurately predicts house prices based on selected numerical features.

---

## 📊 Dataset Information

The dataset includes the following features:

- POSTED_BY
- UNDER_CONSTRUCTION
- RERA
- BHK_NO.
- BHK_OR_RK
- SQUARE_FT
- READY_TO_MOVE
- RESALE
- ADDRESS
- LONGITUDE
- LATITUDE
- TARGET(PRICE_IN_LACS) → Target Variable

For this project, only numerical features were selected to build a beginner-friendly regression model.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## ⚙️ Machine Learning Model

Model Used:
- Linear Regression

Steps Performed:
1. Data loading and exploration
2. Feature selection
3. Train-test split (80%-20%)
4. Model training using Linear Regression
5. Model evaluation using:
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Squared Error)
   - R² Score
6. Visualization of Actual vs Predicted Prices

---

## 📈 Model Performance

The model was evaluated using R² score to measure prediction accuracy.

R² Score indicates how well the model explains the variation in house prices.

Higher R² value means better model performance.

---

## 📊 Visualization

A scatter plot was created to compare actual house prices with predicted prices.

---

## 🚀 How to Run This Project

1. Upload the dataset file (`train.csv`) to Google Colab.
2. Run the full Python program.
3. Model will train and display performance metrics.

---

## 🎯 Future Improvements

- Apply Feature Scaling
- Encode categorical variables
- Use advanced models like Random Forest or XGBoost
- Hyperparameter tuning for better accuracy

---

## 👨‍💻 Author

Suman Mondal  
B.Tech Computer Science Engineering  
Aspiring AI & Machine Learning Engineer

---

⭐ If you found this project useful, feel free to give it a star!

