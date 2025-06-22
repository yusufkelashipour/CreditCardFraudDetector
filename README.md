🛡️ Credit Card Fraud Detection
This project focuses on building a machine learning model to detect fraudulent credit card transactions using logistic regression. The model was trained and evaluated on a real-world dataset consisting of 284,807 transactions, with only 492 labeled as fraud—making this a classic case of working with imbalanced data.

The dataset was preprocessed using Pandas and NumPy, with exploratory analysis performed to understand the nature of fraudulent behavior compared to legitimate activity. After confirming there were no missing values, the data was balanced by randomly undersampling the majority class to match the number of fraud cases.

An 80/20 stratified train-test split was applied using scikit-learn, ensuring consistent class representation across training and test sets. The logistic regression model was then trained with an increased iteration limit to allow for proper convergence. The model achieved a training accuracy of 95.81% and a test accuracy of 92.89%, indicating strong performance on unseen data.

This project utilized the following tech stack: Python for core programming, Pandas and NumPy for data manipulation and preprocessing, and scikit-learn for model training, evaluation, and data splitting. All analysis was done within a Jupyter Notebook environment.

The dataset used is available on Kaggle. Future improvements could include trying more advanced classification algorithms such as Random Forest or XGBoost, applying SMOTE for oversampling, adding precision/recall/F1-score metrics, and deploying the model with tools like Flask or Streamlit for interactive fraud detection interfaces.

