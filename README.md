# CreditCardFraudDetector

🛡️ Credit Card Fraud Detection
A machine learning project using logistic regression to identify fraudulent credit card transactions with high accuracy on a real-world dataset.

📊 Project Overview
This project analyzes and models credit card transactions to detect fraud using a binary classification approach. The dataset is highly imbalanced, containing 284,807 transactions with only 492 fraud cases. The goal is to build a model that can accurately distinguish between legit and fraudulent activity.

✅ Key Features
Trained a logistic regression model with 92.89% test accuracy

Handled class imbalance using random undersampling

Applied Pandas and NumPy for data preprocessing

Used stratified 80/20 train-test split to preserve label ratios

Evaluated performance using accuracy score

Compared fraud vs legit statistics to explore patterns and differences

🧠 Technologies Used
Python

Pandas, NumPy – Data manipulation and cleaning

scikit-learn – Model training and evaluation

(Optional:) Matplotlib/Seaborn – For visualizations (if used)

📁 Dataset
Dataset: Kaggle Credit Card Fraud Detection

Features: 30 anonymized numerical features (V1–V28, Time, Amount)

Target: Class (0 = Legit, 1 = Fraud)

⚙️ How It Works
Load and inspect the dataset

Explore class imbalance and analyze fraud patterns

Undersample legit transactions to match the number of frauds

Split data using train_test_split with stratify

Train logistic regression model with max_iter=10000

Evaluate performance on both training and test sets

📌 Results
Training Accuracy: 95.81%

Test Accuracy: 92.89%

Fraud detection model performs well after class balancing, showing strong ability to generalize

🧩 Future Improvements
Use SMOTE or ensemble methods for more advanced balancing

Try other models: Random Forest, XGBoost, or Neural Networks

Add precision, recall, F1-score, and confusion matrix for deeper evaluation

Deploy using Flask or Streamlit for interactive predictions

📜 License
MIT License
