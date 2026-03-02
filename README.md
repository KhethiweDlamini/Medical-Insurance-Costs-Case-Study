# Medical Insurance Cost Prediction: Linear vs ML Models

## Overview

This project presents a high-level comparative analysis of classical linear regression methods and machine learning models for predicting individual medical insurance costs. The primary objective is to compare predictive performance across linear, penalised linear, and ensemble-based ML models.

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
   - Automated using `ydata-profiling`
   - Visual analysis using scatter plots  

2. **Data Preprocessing**
   - One-hot encoding categorical variables   

3. **Model Training & Evaluation**
   - Training multiple regression models  
   - Comparing performance using RMSE and R²  

## Tools & Libraries
- Python
- matplotlib
- numpy  
- pandas  
- scikit-learn  
- XGBoost  
- ydata-profiling
- Google Colab
   - Notebooks for different sections of the analysis can be found on the following links:
        - [EDA using scatter plots](https://colab.research.google.com/drive/1TxeI4jyfzjOgT91uUkuR4hZkWWTH57sf)
        - [EDA using ydata profiling](https://colab.research.google.com/drive/1QEmWRtYIZOayp7oG3D7E9kzg2OUOhZmt)
        - [Predictive modelling](https://colab.research.google.com/drive/1-r_Ese3hrz0EK6K_BbBQd3WAD5qTWgdK)

## References
- Klymentiev, R. (2018). *Health Care Cost Prediction with Linear Regression*. Kaggle.  
- scikit-learn documentation: *Gradient Boosting Regression*.  
- Thongpeth et al. (2021). *Comparison of linear, penalized linear and machine learning models predicting hospital visit costs*. Informatics in Medicine Unlocked.  
- Verma, N. (2023). *Gradient Boosting Regression Implementation in Python*. Medium.  
