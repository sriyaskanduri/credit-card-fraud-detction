🏦 Credit Card Fraud Detection

📌 Overview

This project detects fraudulent credit card transactions using Random Forests and Decision Trees. A key challenge is class imbalance, as fraud cases make up only 0.17% of the dataset. The project applies techniques to address this issue and improve model performance.

✨ Features

•	Exploratory Data Analysis (EDA) to understand fraud patterns
•	Comparison of Decision Trees vs. Random Forests
•	Handling Class Imbalance to improve fraud detection
•	Model Evaluation using Accuracy, Precision, Recall, and F1-Score

🛠️ Tech Stack

•	Python
•	Pandas, NumPy (Data Processing)
•	Scikit-learn (Machine Learning)
•	Matplotlib, Seaborn (Data Visualization)


📊 Dataset

•	The dataset contains anonymized credit card transactions.
•	It has a severe class imbalance:
•	Fraudulent Transactions: 0.17%
•	Genuine Transactions: 99.83%

🔍 Key Insights

•	Random Forest outperforms Decision Trees for fraud detection.
•	Class Imbalance Handling is crucial; otherwise, the model predicts most transactions as genuine.
•	Feature Engineering & Resampling techniques improve fraud classification.

📝 Usage

•	Load the dataset and explore transaction patterns.
•	Train and evaluate Random Forests & Decision Trees.
•	Apply techniques to handle class imbalance for better fraud detection.
