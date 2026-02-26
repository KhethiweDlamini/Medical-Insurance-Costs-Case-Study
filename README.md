# Medical Insurance Cost Prediction: Linear vs ML Models

## Overview

This project presents a high-level comparative analysis of classical linear regression methods and machine learning models for predicting individual medical insurance costs.

The project evaluates how effectively different modelling approaches estimate healthcare charges based on demographic and health-related factors. The primary objective is to compare predictive performance across linear, penalised linear, and ensemble-based models.

## Dataset

The dataset contains 1,338 observations and the following variables:

- **Age**: Policyholder age (years)  
- **Sex**: Gender (female, male)  
- **BMI**: Body Mass Index  
- **Children**: Number of dependents covered by health insurance  
- **Smoker**: Smoking status (yes, no)  
- **Region**: US residential region (northeast, southeast, southwest, northwest)  
- **Charges**: Individual medical costs billed by health insurance (target variable)  

## Models Evaluated

#### Linear Models
- Linear Regression  
- Ridge Regression  
- Lasso Regression  

#### Machine Learning Models
- Random Forest Regressor  
- Gradient Boosting Regressor  
- XGBoost Regressor  

## Methodology
1. **Exploratory Data Analysis (EDA)**
   - Automated profiling using `ydata-profiling`
   - Visual exploration using scatter plots  

2. **Data Preprocessing**
   - Encoding categorical variables   

3. **Model Training & Evaluation**
   - Training multiple regression models  
   - Comparing performance using standard regression metrics, using RMSE and R²  

## Tools & Libraries
- Python
- matplotlib
- numpy  
- pandas  
- scikit-learn  
- XGBoost  
- ydata-profiling
  
## References
- Klymentiev, R. (2018). *Health Care Cost Prediction with Linear Regression*. Kaggle.  
- scikit-learn documentation: *Gradient Boosting Regression*.  
- Thongpeth et al. (2021). *Comparison of linear, penalized linear and machine learning models predicting hospital visit costs*. Informatics in Medicine Unlocked.  
- Verma, N. (2023). *Gradient Boosting Regression Implementation in Python*. Medium.  
