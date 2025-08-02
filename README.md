# Hybrid Customer Churn Prediction using Clustering & Classification 💳

## Project Goal
The goal of this project is to predict customer churn for a credit card service. By analyzing customer demographics and transaction behavior, we build a classification model to identify clients who are likely to attrite (close their accounts). The project also involves clustering to segment customers, providing deeper insights that can help the bank design targeted retention strategies.

---

## Why This Project Stands Out 🚀
This project stands out from standard classification tasks due to its **hybrid modeling approach**, which provides deeper insights and a more robust solution:

1.  **Insight-Driven Feature Engineering:** Instead of relying only on the original features, this project first applies **K-Means Clustering** to uncover the natural "behavioral segments" hidden within the customer base.
2.  **Enhanced Supervised Learning:** The discovered cluster labels are then used as a new, powerful **engineered feature**, allowing the final classification models to learn more complex patterns.
3.  **Comprehensive Model Showdown:** The project systematically evaluates and compares a diverse set of powerful algorithms—**Logistic Regression, Random Forest, XGBoost, and an ANN**—to find the absolute best tool for the job.

This strategic, multi-layered workflow demonstrates an ability to creatively solve business problems, not just apply standard algorithms.

---

## Dataset
This project uses the "Bank Churners" dataset from Kaggle, which contains information on over 10,000 credit card customers.
* **Link:** `[You can add the link to the dataset here]`

---

## Methodology ⚙️
* **Data Cleaning & Preprocessing:** Handled categorical features using a combination of One-Hot Encoding for nominal data and Ordinal Encoding for ordinal data.
* **Unsupervised Segmentation:** Applied K-Means Clustering to identify 4 distinct customer behavior segments, which were then used as a new feature.
* **Model Development:** Developed and compared multiple classification models, including Logistic Regression, Random Forest, XGBoost, and a deep learning-based Artificial Neural Network (ANN).
* **Model Evaluation:** All models were evaluated based on their accuracy, precision, and recall on the unseen test set.

---

## Results & Insights 💡
* **Best Model:** The `XGBoost Classifier` emerged as the top-performing model, achieving an impressive accuracy of **96.45%** on the test set.
* **Key Churn Predictors:** The feature importance analysis revealed that `Total_Trans_Amt` (Total Transaction Amount), `Total_Trans_Ct` (Total Transaction Count), and `Total_Revolving_Bal` (Total Revolving Balance) were the most significant factors in predicting churn.
* **Customer Segments:** The K-Means analysis identified 4 key customer personas, including 'VIP Customers' (high credit limit, low debt) and 'Active Daily Users' (low credit limit, high transaction count), allowing for more targeted retention campaigns.

---

## Tech Stack
* Python
* Pandas
* Scikit-learn
* XGBoost
* TensorFlow (Keras)
* Matplotlib & Seaborn
