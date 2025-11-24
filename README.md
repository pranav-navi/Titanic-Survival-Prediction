Titanic Survival Prediction using Logistic Regression

📌 Objective

Predict whether a Titanic passenger survived the shipwreck using Logistic Regression.
This is a Supervised Machine Learning (Binary Classification) project.

📂 Dataset

Dataset used: Titanic Dataset (Seaborn / Kaggle’s train.csv)

Features Used

Pclass – Ticket class

Sex – Gender

Age – Passenger age

SibSp – Siblings/spouses aboard

Parch – Parents/children aboard

Fare – Ticket fare

Embarked – Port of embarkation

Survived – Target (1 = Survived, 0 = Not Survived)

🔧 Tools & Libraries

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-Learn

Joblib

🧹 Data Preprocessing

Renamed inconsistent column names

Handled missing values

Age & Fare → median

Embarked → mode

 One-Hot Encoding for Sex, Embarked
 
 Feature scaling with StandardScaler
 
 Train-test split: 80% training, 20% testing

🤖 Model Used: Logistic Regression

Reasons for using Logistic Regression:

Simple and interpretable

Great for binary classification

Provides probability outputs

Efficient on small-to-medium datasets

📈 Model Evaluation

Evaluated using:

Accuracy

Precision

Recall

F1 Score

ROC-AUC

Confusion Matrix

Performance (Typical Output)

Accuracy: ~82–85%

ROC-AUC: ~0.85

📊 Visualizations

Confusion Matrix Heatmap

ROC Curve

Coefficient Importance Plot

These help explain how well the model performs and which features impact survival.

🧠 Feature Importance (Key Findings)

Female passengers had the highest survival chances

1st Class > 2nd Class > 3rd Class survival

Higher Fare → higher chance of survival

Younger passengers survived more often

💾 Model Saving

This project exports:

titanic_test_predictions.csv – Actual vs Predicted + probability

titanic_logistic_pipeline.joblib – trained model

titanic_final_model.joblib – optimized model

🧪 Project Workflow Summary

Load dataset

Clean & preprocess

Encode categorical features

Scale numeric features

Build Logistic Regression model

Evaluate using metrics

Visualize results

Save predictions and model

✅ Conclusion

The Logistic Regression model successfully predicts Titanic survival with high accuracy and interpretability.
The project demonstrates a complete end-to-end ML workflow including data cleaning, preprocessing, modeling, evaluation, and feature analysis.
