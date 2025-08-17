Credit Card Fraud Detection using Machine Learning

📌 Project Overview

This project aims to detect fraudulent credit card transactions using machine learning techniques. Credit card fraud is a major issue in the financial sector, and early detection helps minimize financial losses.
The model is trained on a publicly available dataset and applies classification algorithms to identify fraudulent transactions with high accuracy.


---

📂 Dataset

Source: Kaggle - Credit Card Fraud Detection Dataset

Transactions: ~284,807

Fraudulent Transactions: 492 (~0.17%)

Features:

V1 – V28: Principal Component Analysis (PCA) transformed features

Time: Seconds elapsed between each transaction

Amount: Transaction amount

Class: Target variable (0 → Legitimate, 1 → Fraudulent)




---

⚙️ Tech Stack

Programming Language: Python

Libraries Used:

pandas, numpy → Data preprocessing

matplotlib, seaborn → Visualization

scikit-learn → Machine Learning models (Logistic Regression, Random Forest, etc.)

imblearn → SMOTE for handling class imbalance




---

📊 Approach

1. Data Preprocessing

Checked for missing values

Normalized transaction amount using StandardScaler

Handled imbalanced data using SMOTE (Synthetic Minority Oversampling Technique)



2. Exploratory Data Analysis (EDA)

Distribution of fraud vs non-fraud transactions

Correlation heatmaps

Class imbalance visualization



3. Model Training

Logistic Regression

Random Forest Classifier

Compared performance metrics



4. Evaluation Metrics

Accuracy

Precision

Recall

F1-Score

ROC-AUC Score



🚀 Results

Logistic Regression achieved ~94% accuracy

Random Forest achieved ~95% accuracy with better recall on fraud cases

SMOTE improved detection of fraudulent transactions significantly# Credit-Card-Fraud-Detection