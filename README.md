# House-Price-Prediction
Built a machine learning model to predict house prices using Ames housing data. Performed data cleaning, feature engineering (e.g., total area, bathrooms), and encoding. Applied models like Random Forest and Gradient Boosting, achieving high accuracy using RMSE-based evaluation.
Description:

This project aims to predict the sale prices of residential homes in Ames, Iowa, using machine learning techniques on a comprehensive housing dataset. The dataset includes 70+ features related to house characteristics such as size, quality, location, construction type, and neighborhood.

Process:

Data Cleaning & Preprocessing:
Handled missing values using statistical imputation and domain knowledge. Categorical features were encoded using label encoding for ordinal variables (e.g., quality ratings) and one-hot encoding for nominal variables (e.g., roof type, neighborhood).

Feature Engineering:
Created composite features such as:

TotalSF (Total square footage from basement and floors)

TotalBathrooms (Sum of all bathrooms, weighted by type)

TotalPorchSF (Combined porch and deck areas)
Applied log transformation to the skewed SalePrice target for better model performance.

Modeling & Evaluation:
Trained multiple models including Random Forest and Gradient Boosting Regressor. Used cross-validation and RMSE as the primary metric to evaluate performance. Hyperparameter tuning further improved accuracy.

Outcome:

The best-performing model achieved strong predictive performance and generalized well on unseen data. The project demonstrates an end-to-end pipeline from raw data processing to model deployment-ready predictions, showcasing skills in exploratory data analysis, feature engineering, and supervised learning.
