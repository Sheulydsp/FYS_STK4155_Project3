I have added all the functions as separate files, but unfortunately, those files showed some errors. That's why I added all the functions to the main Jupiter notebook file (analysis.ipynb).

All the functionalities with the outputs have been shown in the "analysis.ipynb" file


Diabetes Prediction Using Machine Learning Models
Author: Sheuly Debnath
Date: April 2025

📚 Project Overview
  This project explores various machine learning methods for predicting diabetes using the Pima Indians Diabetes dataset.
  We apply and compare several techniques, including:
  
  Decision Trees with cost-complexity pruning
  
  Ensemble Methods: Random Forest, AdaBoost, and XGBoost
  
  Feed-Forward Neural Networks (FFNN)
  
  Logistic Regression with Stochastic Mini-batch Gradient Descent
  
  Our goal is to evaluate model performance based on different metrics and interpretability — an essential requirement in healthcare applications.

🛠 Methods and Techniques
  Tree-Based Models:
    Decision Tree
    Random Forest
    AdaBoost
    XGBoost (Gradient Boosting)
  
  Neural Networks:
  
  Custom Feed-Forward Neural Network with tunable hidden layers, neurons, learning rate, and epochs.
  
  Logistic Regression:
  
  Custom implementation using Stochastic Mini-batch Gradient Descent.
  
  Feature Selection:
  
  Based on variable importance from Random Forest.

📊 Evaluation Metrics
  Accuracy
  Precision
  Recall
  Specificity
  F1 Score
  Area Under Curve (AUC)
  Each model is evaluated and compared based on these metrics.

📈 Results Summary

Model	Accuracy	Best Metric
Random Forest	91.6%	Strong accuracy and interpretability
Logistic Regression	Moderate	Best recall (90%)
XGBoost	100%	Highest overall accuracy
XGBoost outperformed all models, achieving perfect prediction accuracy (100%).
Random Forest provided strong balance between performance and model interpretability — crucial for healthcare applications.
Logistic Regression achieved the highest recall, making it effective in minimizing false negatives.

📂 Dataset
Name: Pima Indians Diabetes Dataset
Size: 768 samples, 8 features
Features: Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age
Target: Binary outcome (diabetic or not)
