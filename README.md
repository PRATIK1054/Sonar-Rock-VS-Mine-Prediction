# Sonar-Rock-VS-Mine-Prediction

This project is a Machine Learning classification model that predicts whether a sonar signal is bouncing off a metal mine or a rock. The dataset consists of sonar signals with 60 features, and the model is trained using Logistic Regression for binary classification.

📊 Dataset

Source: Sonar dataset (commonly used for binary classification tasks)

Features: 60 numerical attributes representing sonar signal returns

Labels:

M → Mine

R → Rock

⚙️ Workflow

Data Collection & Preprocessing

Loaded dataset into Pandas DataFrame

Performed exploratory data analysis (EDA)

Separated features (X) and labels (Y)

Model Training

Split dataset into training and testing sets (stratified split)

Trained Logistic Regression classifier

Model Evaluation

Evaluated accuracy on training and test sets

Verified predictions with sample inputs

✅ Results

The model achieves good accuracy in distinguishing mines from rocks using sonar signals.

Demonstrates how Logistic Regression can be applied to real-world binary classification problems.

🚀 Tech Stack

Python

Pandas, NumPy for data handling

Scikit-learn for machine learning

Pandas, NumPy for data handling

Scikit-learn for machine learning
