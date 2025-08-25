# Regression-on-Boston-Housing-Dataset
Implemented regression models on the Boston Housing dataset to predict house prices. Performed data preprocessing, EDA, and feature engineering to identify key factors like crime rate and rooms. Used Linear, Ridge, Lasso, and Random Forest with cross-validation, achieving improved prediction accuracy.
# 🏡 Boston Housing Price Prediction

## 📌 Project Overview
This project predicts house prices using the **Boston Housing dataset**, a classic dataset in machine learning.  
The objective is to analyze the effect of socioeconomic, geographic, and structural factors on housing prices and build regression models for accurate prediction.

## 📊 Dataset
- The dataset contains **506 samples** and **13 features** such as crime rate, number of rooms, property tax, and proximity to employment centers.  
- **Target variable:** MEDV (Median value of owner-occupied homes in $1000s).  

## 🔑 Key Features
- **Data Preprocessing:** Handled missing values, outliers, and standardized features.  
- **Exploratory Data Analysis (EDA):** Visualized feature distributions, correlations, and housing trends.  
- **Feature Engineering:** Added derived features like age categories, room-per-household ratio, and log transformations for skewed variables.  
- **Model Development:** Implemented multiple regression techniques:
  - Linear Regression  
  - Ridge Regression  
  - Lasso Regression  
  - Random Forest Regressor  
- **Model Evaluation:** Compared performance using R², RMSE, and MAE metrics.  

## 🛠️ Tech Stack
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Techniques:** Regression, Feature Engineering, Cross-Validation  

## 🚀 Implementation Steps
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/boston-housing-regression.git
   cd boston-housing-regression
Install required dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook or script to execute preprocessing, EDA, training, and evaluation.

📈 Results

Linear Regression baseline achieved an R² of ~0.73.

Ridge and Lasso improved generalization with reduced overfitting.

Random Forest delivered the best performance with R² > 0.85 and lower RMSE.

Identified that number of rooms, crime rate, and property tax are the most influential factors in predicting home prices.

📉 Visualization Samples

Heatmap of feature correlation

Distribution of target variable (MEDV)

Predicted vs. actual housing prices

🔮 Future Improvements

Experiment with Gradient Boosting & XGBoost for better performance.

Apply deep learning (ANNs) for complex feature interactions.

Expand dataset with external features like school quality, job growth, and infrastructure development.

Email - settypallijaayadrithareddy@gmail.coml
linkedin - linkedin.com/in/jayadrithareddy
