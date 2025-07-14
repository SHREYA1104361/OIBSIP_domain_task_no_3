# OIBSIP_domain_task_no_3
# 🚗 Car Price Prediction Using Machine Learning

## 🧩 Problem Statement :
- The used car market is vast.
- Accurate pricing is essential for both sellers and buyers.
- Objective: Predict the selling price of a used car based on key features such as brand, manufacturing year, fuel type, kilometers driven, etc.

## 🎯 Objective :
- Build a machine learning model to predict used car prices.
- Perform data preprocessing, model training, evaluation, and comparison of multiple regression algorithms.

## ✅ Steps Performed :

### 1. 📥 Data Collection & Loading :
- Imported dataset in CSV format.
- Loaded car details and price data using pandas.

### 2. 📊 Data Exploration & Visualization :
- Analyzed feature distribution using:
  - Histograms
  - Boxplots
  - Correlation heatmaps
- Identified key factors influencing car price.

### 3. 🧹 Data Preprocessing :
- Handled:
  - Missing values
  - Outliers
- Encoded categorical features (e.g., Fuel Type, Seller Type).
- Dropped irrelevant columns (e.g., car name).
- Scaled numerical data (for SVR model).

### 4. 🤖 Model Building :
- Trained various regression models:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - Support Vector Regressor (SVR)
  - XGBoost Regressor

### 5. 📏 Model Evaluation :
- Evaluation metrics used:
  - R² Score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)

### 6. 📈 Visualization :
- Feature importance chart (bar plot)
- Residual plots
- Actual vs Predicted plots

## 🛠️ Tools and Technologies Used :
- **Language**: Python
- **Platform**: Jupyter Notebook / Google Colab
- **Libraries**:
  - `pandas`, `numpy` – for data handling
  - `matplotlib`, `seaborn` – for visualization
  - `scikit-learn` – for preprocessing and modeling
  - `xgboost` – for advanced regression

## 📂 Dataset Description :

### ➕ Features:
- `Year`: Manufacturing year of the car
- `Present Price`: Ex-showroom price
- `Kms Driven`: Distance the car has been driven
- `Fuel Type`: Petrol, Diesel, CNG
- `Seller Type`: Dealer or Individual
- `Transmission`: Manual or Automatic
- `Owner`: Number of previous owners

### 🎯 Target:
- `Selling Price`: Price expected by the seller

### 🔢 Rows:
- Total: **301 records**

## 🏆 Outcome :
- Successfully predicted car prices using regression models.
- Best performance achieved by **Random Forest Regressor** (R² ≈ 91%).
- Identified Year, Present Price, and Fuel Type as important features.
- Strengthened skills in data preprocessing and model evaluation.

## 📌 Conclusion :
- Demonstrates practical application of ML in pricing strategy.
- Random Forest model effectively captured complex feature relationships.
- Valuable learning in feature engineering and evaluation metrics.

