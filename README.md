🕵️ Fraud Detection Project

📌 Overview

This project aims to detect fraudulent transactions by analyzing various financial datasets. It involves data preprocessing, feature engineering, and implementing a machine learning model to classify transactions as fraudulent or legitimate.



📂 Dataset

The project uses multiple CSV files containing customer and transaction data:
📁 account_activity.csv
📁 customer_data.csv
📁 fraud_indicators.csv
📁 suspicious_activity.csv
📁 merchant_data.csv
📁 transaction_category_labels.csv
📁 amount_data.csv
📁 anomaly_scores.csv
📁 transaction_metadata.csv
📁 transaction_records.csv

🚀 Steps Involved

🔍 1. Data Loading & Exploration

Read multiple datasets using pandas.

Merge relevant datasets based on common identifiers like CustomerID and TransactionID.

Display dataset information, shape, and summary statistics.

🏗 2. Feature Engineering

Identify numerical and categorical features.

Generate 📊 box plots for numerical columns to identify outliers.

Compute 🔥 correlation heatmaps to understand feature relationships.

Convert timestamp columns to datetime format and extract useful features like Hour and gap (difference between last login and transaction time).

🧹 3. Data Cleaning

Drop unnecessary columns such as TransactionID, MerchantID, CustomerID, Name, Age, and Address.

Label encode categorical features.

🎯 4. Data Splitting

Split data into training and testing sets using train_test_split.

🤖 5. Model Training & Evaluation

Train a Logistic Regression model.

Evaluate performance using:
✅ Accuracy
✅ Precision
✅ Recall
✅ F1-score
✅ Confusion matrix

📈 Plot a count plot of the FraudIndicator feature.

⚖️ 6. Handling Class Imbalance

Apply Random Over-Sampling using imbalanced-learn to balance the dataset.

Retrain the Logistic Regression model on the balanced dataset and evaluate performance again.

🔧 Dependencies

🐍 Python

🔢 NumPy

📊 Pandas

🎨 Matplotlib

🎭 Seaborn

🤖 Scikit-learn

⚖️ Imbalanced-learn

🖥 Google Colab (optional)

🎯 Results

The model is trained and evaluated on both imbalanced and balanced datasets.

Performance metrics such as accuracy, precision, recall, and F1-score are calculated to assess the model’s effectiveness.

A confusion matrix provides insights into the classification results.

🔮 Future Improvements

🚀 Implement other machine learning models (e.g., Decision Trees, Random Forest, XGBoost) for better performance.

🛠 Perform hyperparameter tuning to optimize model accuracy.

🎯 Apply feature selection techniques to improve model efficiency.

▶️ How to Run

✅ Ensure all required libraries are installed.

📥 Load datasets and preprocess them as described.

🤖 Train and evaluate the model using the provided code.

🔬 Experiment with different models and oversampling techniques for better results.

This project provides a foundational approach to fraud detection using machine learning and can be further enhanced with more advanced techniques. 🚀

