# Car Price Prediction
# Project Overview
This project focuses on predicting the selling price of used cars using machine learning regression techniques. Different models were trained and evaluated to identify the best-performing approach for accurate price prediction.
# Objective
The objective of this project is to build and compare regression models to predict car prices and select the most reliable model based on performance metrics.
# Dataset
The dataset used in this project contains information about used cars, including features related to the car specifications and their selling prices.
# Methodology
- Loaded and explored the car price dataset
- Performed data cleaning and preprocessing
- Selected relevant features for prediction
- Trained two regression models:
  - Linear Regression
  - Random Forest Regressor
- Evaluated both models using:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- Compared actual vs predicted values using visual analysis
# Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
# Conclusion
In this project, both Linear Regression and Random Forest Regressor were trained to predict the selling price of used cars. The models were evaluated using MAE, RMSE, and R² score.
Random Forest achieved a lower MAE (0.6141) compared to Linear Regression (0.8141), indicating more accurate price predictions. The Actual vs Predicted graph also showed that Random Forest predictions were closer to the ideal line. Although Linear Regression had a slightly higher R² score, Random Forest provided better real-world predictive performance.
Therefore, Random Forest Regressor was selected as the final model due to its superior accuracy and stability.
