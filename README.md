🛡️ Credit Card Fraud Detection
This project focuses on building a machine learning model to detect fraudulent credit card transactions using logistic regression. The model was trained and evaluated on a real-world dataset consisting of 284,807 transactions, with only 492 labeled as fraud—making this a classic case of working with imbalanced data.

The dataset was preprocessed using Pandas and NumPy. After checking for missing values and exploring the distribution of fraud versus legitimate transactions, the dataset was balanced using random undersampling. This technique helped ensure that the model wasn't biased toward the majority class.

An 80/20 stratified train-test split was applied to preserve class distribution across both training and testing datasets. The logistic regression model was trained using scikit-learn with a high iteration limit to ensure convergence. The resulting model achieved a training accuracy of approximately 95.81% and a test accuracy of 92.89%, demonstrating its ability to generalize well on unseen data.

Feature-wise, the dataset contained anonymized numerical values (V1 to V28), along with Time and Amount. The Class column served as the target variable, indicating whether a transaction was fraudulent (1) or legitimate (0).

This project highlights fundamental machine learning practices including model evaluation, dealing with class imbalance, and performance validation using metrics like accuracy score. Future improvements may include the use of techniques such as SMOTE (Synthetic Minority Over-sampling Technique), trying alternative models like Random Forest or XGBoost, and calculating additional evaluation metrics such as precision, recall, and F1-score. Deploying the model via Flask or Streamlit for interactive use could also enhance its practical value.

The dataset used is available on Kaggle. This project was completed using Python, along with libraries including Pandas, NumPy, and scikit-learn.
