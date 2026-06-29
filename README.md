# Credit-Card-Fraud-Detection
Built a machine learning model to identify fraudulent credit card transactions using Python. The project includes data preprocessing, handling class imbalance, training classification models, and evaluating performance using standard machine learning metrics.

💳 Credit Card Fraud Detection

A machine learning project that detects fraudulent credit card transactions using the Kaggle Credit Card Fraud Detection dataset. The project focuses on handling imbalanced data, training classification models, and evaluating their performance to identify fraudulent transactions.

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/b7bf6d25-e9b6-4dfd-a3e7-c445c792775e" />



📌 Project Overview

The objective of this project is to build a machine learning model that can classify transactions as fraudulent or legitimate. Since fraud cases make up only a small portion of the dataset, special attention is given to handling class imbalance and selecting appropriate evaluation metrics.

📂 Dataset
Source: Kaggle - Credit Card Fraud Detection
Total Transactions: 284,807
Fraud Cases: 492 (0.17%)
Features: 30 numerical features (Time, Amount, V1–V28)
Target Variable: Class
0 – Legitimate Transaction
1 – Fraudulent Transaction


🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook


📊 Exploratory Data Analysis

Some of the analysis performed includes:

Checked class imbalance
Analyzed transaction amount and time
Visualized feature distributions
Generated a correlation heatmap
Compared fraud and non-fraud transactions

🔧 Data Preprocessing

Scaled the Time and Amount features using StandardScaler
Split the dataset into training and testing sets (70:30)
Applied undersampling to reduce class imbalance
Prepared the data for model training


🤖 Models Used
Logistic Regression
Precision: 83%
Recall: 63%
F1-Score: 0.72
ROC-AUC: 0.958

Random Forest Classifier

The Random Forest model achieved better overall performance, especially in detecting fraudulent transactions, making it the better-performing model in this project.

📈 Model Evaluation

The models were evaluated using:

Confusion Matrix
Classification Report
Precision
Recall
F1-Score
ROC Curve
ROC-AUC Score


💡 Key Findings
The dataset is highly imbalanced, so handling class imbalance is important.
Random Forest performed better than Logistic Regression in identifying fraud cases.
Recall is an important metric for fraud detection because missing fraudulent transactions can be costly.

🚀 Future Improvements

Use SMOTE for oversampling
Try XGBoost or LightGBM
Perform hyperparameter tuning
Deploy the model using Flask or Streamlit


📌 Skills Demonstrated

Data Cleaning
Exploratory Data Analysis (EDA)
Data Preprocessing
Machine Learning
Classification Models
Model Evaluation
Python
Data Visualization
