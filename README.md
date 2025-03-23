# MedicalDiagnosis
Link to the project: https://colab.research.google.com/drive/1vBHZ-fEcjEMitajGtaGRfzf2LbRHqqsl?usp=sharing

Problem Statement:
Diabetes is a chronic disease that affects millions worldwide. Early detection can help manage and prevent severe complications. The objective of this project is to develop a machine-learning model to predict whether a patient has diabetes based on medical diagnostic features.

Objectives:
Predict diabetes risk using patient health data.

Analyze feature importance to understand key indicators of diabetes.

Compare multiple machine learning models to identify the best-performing algorithm.

Methodology:
Dataset: PIMA Indians Diabetes Dataset (collected from Kaggle).

Data Preprocessing:

Handle missing values.

Normalize numerical features.

Split data into training (80%) and testing (20%).

Model Training:

Logistic Regression

Random Forest Classifier

XGBoost Classifier

Evaluation Metrics: Accuracy, Precision, Recall, F1-score, and Confusion Matrix.

Key Results:
Random Forest performed best with an accuracy of ~85%, outperforming Logistic Regression and XGBoost.

Feature Importance Analysis:

Glucose Level & BMI were the most influential factors.

Age & Insulin levels also played a crucial role in predictions.

Conclusion:
This project successfully developed a predictive model for diabetes detection. Random Forest proved to be the most effective classifier. Future improvements could include hyperparameter tuning, deep learning models, and additional health indicators.
