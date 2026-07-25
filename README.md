# Diabetes Prediction Model

A machine learning model that predicts diabetes diagnosis using the 
Pima Indians Diabetes dataset, built with a Random Forest Classifier.

## Features
- Data preprocessing: handling missing values with mean imputation
- Hyperparameter tuning using GridSearchCV
- Model evaluation: Accuracy, Precision, Recall, F1-Score
- Threshold tuning to improve recall for medical diagnosis use case
  (lowered from 0.5 to 0.25 to reduce false negatives)

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib

## Results
Optimized Random Forest with GridSearchCV, with threshold adjustment 
to prioritize recall — critical for medical screening where missing 
a positive case is more costly than a false alarm.
