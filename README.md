# Traffic Accident Severity Prediction

This project explores the use of supervised machine learning models to predict the severity of road traffic accidents based on weather, time, and other crash-related features.
> This project was completed as a group assignment for a machine learning class.  
> This repository highlights my personal contributions and hosts the final report.

> [Dataset from Kaggle] https://www.kaggle.com/datasets/saurabhshahane/road-traffic-accidents

## Summary

- Built and evaluated three ML models:  
  - Multinomial Logistic Regression  
  - Random Forest (with GridSearchCV)  
  - XGBoost

- Data preprocessing included:
  - Missing value imputation (mean, mode, or class-conditional)
  - One-hot and label encoding
  - Feature scaling with StandardScaler
  - Feature reduction with PCA and RFE

- Models were evaluated using:
  - Accuracy, F1-macro, and ROC-AUC
  - Confusion matrices and calibration plots
  - Feature importance visualizations
 
## Result Summary

| Model                 | Accuracy | F1 Macro | ROC-AUC |
|----------------------|----------|----------|---------|
| Logistic Regression  | 80.96%   | 0.499    | 0.748   |
| Random Forest        | 85.30%   | 0.567    | 0.787   |
| XGBoost              | 85.00%   | 0.470    | 0.770   |

Random Forest performed best overall after hyperparameter tuning.

## My Contributions
- Handled **data preprocessing**, including encoding, imputation, and normalization
- Performed **feature reduction and selection** using PCA and RFE
- Tuned model performance through **hyperparameter optimization** (e.g., GridSearchCV)
- Collaborated with teammates on building and evaluating ML models (Random Forest, Logistic Regression, XGBoost)
    
## How to view

You can view the final report by opening `index.html` in your browser:

1. Clone or download the repo
2. Open `index.html` directly in any browser
   
## Relevant Files

/CS-4641-Project/Logistic_Regression.ipynb
- Contains all code for data preprocessing, Nominal Logistic Regresion implementation, visualization, and evaluation.
  
/CS-4641-Project/Random_Forest.ipynb
- Contains all code for data preprocessing, Random Forest implementation, visualization, and evaluation.

/CS-4641-Project/XGBoost.ipynb
- Contains all code for data preprocessing, XGBoost implementation, visualization, and evaluation. 
