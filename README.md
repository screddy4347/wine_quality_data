Wine Quality Prediction using Machine Learning
📌 Project Overview

This project focuses on predicting the quality of red wine based on its physicochemical properties using Machine Learning.
The goal is to train a classification model that can accurately predict wine quality scores.

The dataset used is the Wine Quality – Red Wine dataset.

🎯 Objectives

Understand and analyze wine quality data

Perform data preprocessing

Split data into training and testing sets

Train a Random Forest Classifier

Evaluate model performance using Accuracy Score

🧠 Machine Learning Type

Supervised Learning

Classification Problem

Multi-class Classification

📊 Dataset Information

Dataset Name: Wine Quality – Red Wine

Total Samples: 1599

Features: 11

Target Variable: quality

🔹 Features

fixed acidity

volatile acidity

citric acid

residual sugar

chlorides

free sulfur dioxide

total sulfur dioxide

density

pH

sulphates

alcohol

🛠️ Technologies & Libraries Used

Python

Pandas – data handling

NumPy – numerical operations

Scikit-learn – ML models & evaluation

RandomForestClassifier

train_test_split

accuracy_score

⚙️ Project Workflow

Load the dataset

Separate features and target variable

Split data into training and testing sets

Train Random Forest Classifier

Make predictions

Evaluate model using accuracy score

🧪 Model Training

Algorithm Used: Random Forest Classifier

No feature scaling required

Handles non-linearity and feature importance well

📈 Model Evaluation
✅ Accuracy Score
Accuracy ≈ 60% – 70%


(Accuracy may vary due to randomness and data split)

📌 Key Observations

Wine quality prediction is a challenging multi-class problem

Random Forest performs reasonably well without tuning

Accuracy can be improved using:

Hyperparameter tuning

Converting to binary classification (Good / Bad wine)


Future Improvements

Hyperparameter tuning (GridSearchCV)

Feature importance visualization

Binary classification approach

Model comparison (SVM, Logistic Regression)
