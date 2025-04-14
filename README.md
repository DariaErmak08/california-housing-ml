# 🏡 California Housing Price Prediction

## ✨ Project Overview
This machine learning project explores housing data from California to predict median home values based on income, population, and location features. We apply several regression models and analyze their performance to uncover patterns behind housing prices.

The goal: build accurate predictive models and explain the key drivers behind California home prices — from median income to geography.

---

## 📊 Dataset
The dataset comes from the 1990 California Census and includes:
- Median income
- Average rooms and bedrooms
- House age
- Average occupancy per household
- Population
- Latitude & Longitude (location)
- Median home value (target, in 100,000s USD)

---

## 🔧 What’s Inside
- 📦 Data preprocessing (cleaning, scaling, train/test split)
- 🔢 Regression models:
  - Linear Regression
  - Ridge & Lasso
  - Random Forest Regressor
- 📈 Evaluation with MAE, MSE, R²
- 📊 Visualizations: Actual vs Predicted, Error Distribution, Feature-to-Target relationships
- 🧠 Feature importance analysis

---

## 🧠 Key Insights
- 📍 Location (lat/lon) and 💰 median income are the strongest price drivers
- Random Forest performed the best in R² score and generalization
- Price values are **capped at $500,000**, which impacts model performance on high-end predictions
- Visual exploration reveals nonlinear patterns traditional regression can’t capture

---

## 🚀 Future Ideas
- Try XGBoost or Gradient Boosting Regressors
- Add additional context: school quality, crime rates, infrastructure
- Apply hyperparameter tuning and cross-validation

---

## 🛠️ Tools Used
- Python
- scikit-learn
- pandas, numpy
- seaborn, matplotlib
- Jupyter Notebook

---

## 👩‍💻 Author

**Daria Ermak**  
[[GitHub](https://github.com/DariaErmak08?tab=repositories)]

---

_Thanks for checking it out! Feel free to reach out for questions or feedback 🙂_
