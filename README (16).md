
# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting car prices in the American market using machine
learning regression techniques.

A Chinese automobile company plans to enter the US market and wants to understand
the key factors that influence car pricing. The objective of this project is to
identify significant variables affecting car prices and to evaluate how well these
variables explain price variations.

---

## 🎯 Business Objective
- Identify the most important variables that affect car prices
- Understand pricing dynamics in the US automobile market
- Build predictive models to estimate car prices accurately
- Support business decisions related to car design and pricing strategy

---

## 📂 Dataset Description
- Dataset contains information about cars sold in the American market
- Number of observations: **205**
- Target variable: **price**
- Features include:
  - Engine specifications
  - Car dimensions
  - Fuel efficiency
  - Fuel system
  - Brand information

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Project Workflow

### 1️⃣ Data Loading and Inspection
- Loaded dataset using Pandas
- Checked data shape, column types, and basic statistics

### 2️⃣ Data Preprocessing
- Checked for missing values and duplicates (none found)
- Outlier detection using IQR method
- Skewness analysis using histograms with KDE
- Feature engineering by extracting `brand` from `CarName`
- One-Hot Encoding applied to all categorical variables
- Train–test split (80% training, 20% testing)

### 3️⃣ Machine Learning Models Implemented
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor
5. Support Vector Regressor (SVR)

Scaling was applied only to models that required it.

---

## 📊 Model Evaluation Metrics
- R² Score
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)

---

## 🏆 Best Model
**Random Forest Regressor**
- R² ≈ **0.96**
- Lowest MAE among all models

---

## 📈 Feature Importance & Correlation
- Most important features:
  - Engine size
  - Curb weight
  - Horsepower
  - Car dimensions
- Fuel efficiency features show negative correlation with price

---

## ⚙️ Hyperparameter Tuning
- Performed using GridSearchCV
- Default Random Forest parameters were already near optimal

---

## 🧾 Conclusion
The Random Forest model effectively predicts car prices and provides clear insights
into the key factors affecting pricing in the US automobile market.

---

## 👤 Author
**Amal Thomas**  
BSc (Hons) Artificial Intelligence
