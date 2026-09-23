# codesoft-task2
Credit_card_Fraud_Detection
README.md

# Credit Card Fraud Detection

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques.

The objective is to build classification models that can identify fraudulent transactions and compare their performance using different evaluation metrics.

## 🎯 Objective

- Detect fraudulent credit card transactions.
- Perform data preprocessing and feature engineering.
- Extract date and time features.
- Handle categorical and numerical data.
- Train and compare multiple machine learning models.
- Evaluate model performance using classification metrics.

## 📂 Dataset

The dataset contains credit card transaction information, including:

- Transaction amount
- Merchant
- Transaction category
- Gender
- City and state
- Geographic coordinates
- Transaction date and time
- Fraud indicator

The target column is:

`is_fraud`

- `0` = Legitimate transaction
- `1` = Fraudulent transaction

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Joblib

## 🤖 Machine Learning Models

The following models were trained and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

## 🔧 Data Preprocessing

The following preprocessing techniques were applied:

- Removed unnecessary columns.
- Extracted hour, day, month, and weekday from transaction timestamps.
- Handled missing values using imputation.
- Applied feature scaling to numerical features.
- Applied one-hot encoding to categorical features.
- Used class balancing for classification models.

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

## 📈 Results

The performance of Logistic Regression, Decision Tree, and Random Forest was compared using the evaluation metrics.

The comparison results are available in the project notebook.

## 💾 Model Saving

The trained Random Forest model was saved using Joblib:

`fraud_detection_random_forest.pkl`

## 🚀 Conclusion

This project demonstrates the application of machine learning techniques for detecting fraudulent credit card transactions. Model comparison helps understand the performance of different classification algorithms in fraud detection.

## 👩‍💻 Author

Khushabu Bansal
