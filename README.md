# House Price Prediction Project

This project predicts house prices using the Kaggle **Housing.csv** dataset.  
The goal is to understand which factors influence house prices and build a machine learning model that gives reliable predictions.

---

## 📌 Project Overview

I explored the dataset, cleaned the data, encoded categorical columns, scaled numerical features, and trained both Linear Regression and Random Forest models.

The Random Forest model performed much better and gave an R² score between **85–92%**, depending on the feature selection and parameters.

---

## 🔍 What This Project Includes

- Exploratory Data Analysis (EDA)
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Feature engineering (e.g., age of house, price per sqft)
- Training Linear Regression & Random Forest models
- Model evaluation (R², MAE, RMSE)
- Plotting actual vs predicted values

---

## 📊 Dataset Information

The dataset used is `Housing.csv` from Kaggle.  
It contains:

- Numeric features (area, bedrooms, bathrooms, stories, etc.)
- Yes/No categorical features (mainroad, basement, guestroom, etc.)
- Categorical column (furnishing status)
- Target column: **price**

---

## ⚙️ Models Used

### **1. Multiple Linear Regression**
- Baseline model  
- Achieved around **65% R²**

### **2. Random Forest Regressor (Improved Model)**
- Handled non-linear relationships
- Achieved **85–92% R²**

This model is used as the final model.

---

## 📈 Evaluation Metrics

- **R² Score**  
- **Mean Absolute Error (MAE)**  
- **Root Mean Squared Error (RMSE)**  
- Actual vs Predicted Scatter Plot  

---

## ▶️ How to Run This Project

1. Install all required packages:
```bash
pip install -r requirements.txt


📌 Future Improvements
Hyperparameter tuning for Random Forest

Add Gradient Boosting / XGBoost

Add feature importance visualization

Try log transformation for skewed columns

✨ Author
Diksha Joshi
Email: joshidiksha660@gmail.com
Github https://github.com/joshidiksha660
Linkedin https://in.linkedin.com/in/diksha-joshi-58b8ba304

