# Heart Failure Prediction with Machine Learning

# Overview

This project focuses on building and evaluating machine learning models to predict heart failure based on clinical features. We will use four different classification algorithms: Logistic Regression (LR), Decision Tree (DT), Random Forest (RF), and XGBoost (XGB). Additionally, we will perform explanatory data analysis (EDA) and interpretability tasks to gain insights into the models' predictions.

# Dataset

We are using the "Heart failure clinical records Data Set" from the UCI Machine Learning Repository. This dataset contains medical records of 299 patients with 13 clinical features, including age, anemia, high blood pressure, and more. The target variable is "death event," indicating whether the patient deceased during the follow-up period.

Dataset Source: Heart failure clinical records Data Set

Dataset Download: heart_failure_clinical_records_dataset.csv

# Tasks

## 1. Explanatory Data Analysis (EDA)
Explore and visualize the dataset.
Analyze feature correlations, especially with the target variable.
## 2. Machine Learning Modeling
Implement machine learning models using LR, DT, RF, and XGB.
Perform hyperparameter tuning using GridSearchCV.
Evaluate models using accuracy and AUC-ROC metrics.
## 3. Machine Learning Interpretability/Explainability
3_A) Logistic Regression Interpretation

Use the 'eli5' library to visualize feature weights.
Explain specific predictions for both positive and negative labels.
3_B) Decision Tree Interpretation

Use 'eli5' to list feature importance.
Explain a prediction for both positive and negative labels.
3_C) Random Forest and XGBoost Interpretation

Use LIME to explain both models.
Calculate coefficients, intercept, and R2 for the linear model.
Interpret feature importance.
3_D) SHAP Interpretation for XGBoost

Use SHAP to interpret the XGBoost model.
Visualize explanations for both positive and negative predictions.
Create feature importance plots for each class/label.
## 4. Model Predictions
Predict observations for both positive and negative labels using all four models.
Provide accuracy results for each model.
How to Run the Code

Clone this GitHub repository to your local machine.
Ensure you have the required libraries installed (scikit-learn, xgboost, eli5, lime, shap, etc.).
Open the Jupyter (or Colab) notebook provided in this repository.
Execute the code cells step by step.
Results

The notebook contains detailed analysis, model performance, and interpretability results.

# Conclusion

This project demonstrates the application of machine learning models for heart failure prediction, along with interpretability techniques to understand the models' decision-making processes.

