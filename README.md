# Ames-House-Sales-Price-Analysis
Project Overview
This project focuses on predicting residential property sale prices using the Ames Housing Dataset. Built an end-to-end machine learning pipeline starting from raw data cleaning and exploratory analysis in Python, moving to feature engineering and model training, and finishing with a comparison of three regression models — OLS, Ridge, and LASSO.
Tech Stack

Data Cleaning & EDA: Python (pandas, NumPy, SciPy, matplotlib, seaborn)
Machine Learning: Python (scikit-learn)
Environment: Google Colab

Dataset

Source: Ames Housing Dataset — Dean De Cock (2011)
Size: 2,930 records × 82 features
Target Variable: Sale Price (USD)

Methodology

Data Cleaning — Handled missing values and removed outliers
EDA — Analysed feature distributions and correlations with sale price
Feature Engineering — Log-transformed target variable; one-hot encoded categorical features (78 → 217 features)
Modelling — Trained OLS, Ridge, and LASSO regression models with cross-validated hyperparameter tuning
Evaluation — Compared models using R², RMSE, and MAE on a 30% held-out test set

Results
ModelR²RMSE ($)MAE ($)OLS0.924822,69814,081Ridge0.924122,80613,883LASSO0.930621,81413,780

✅ LASSO achieved the best performance, reducing features from 216 to 82 through automatic feature selection.
