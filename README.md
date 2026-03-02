# Fraud-Detection-ML
🚀 A production-style fraud detection system built using Random Forest on 6.3 million financial transactions.

The project focuses on handling severe class imbalance and optimizing fraud recall while maintaining low false positives.

# Fraud Detection using Machine Learning

This project builds a scalable fraud detection system using a Random Forest classifier on a large-scale financial transaction dataset containing 6.3 million records.

## 📌 Objective

To develop a machine learning model capable of proactively detecting fraudulent financial transactions while handling severe class imbalance.

---

## 📊 Dataset Overview

- Total Transactions: 6.3 Million
- Target Variable: `isFraud`
- Severe Class Imbalance (~0.1% fraud cases)
- Features include transaction type, amount, account balances before and after transaction

---

## ⚙️ Techniques Used

- Data Cleaning and Preprocessing
- One-Hot Encoding for categorical variables
- Stratified Train-Test Split
- Random Forest Classifier
- Class Imbalance Handling using `class_weight="balanced"`
- Feature Importance Analysis

---

## 🚀 Model Performance

Confusion Matrix (Test Set):

True Negatives: 1,270,854  
False Positives: 27  
False Negatives: 358  
True Positives: 1,285  

### Fraud Detection Metrics:
- Precision: 0.98
- Recall: 0.78
- F1 Score: 0.87

The model maintains high precision while achieving strong fraud detection recall.

---

## 🔎 Key Insights

- Account balance changes are strong indicators of fraudulent activity.
- Transaction types such as TRANSFER and CASH_OUT contribute significantly to fraud detection.
- Class weighting significantly improved fraud detection performance.

---

## 💡 Business Recommendations

- Deploy real-time fraud scoring systems.
- Apply additional verification for high-risk transactions.
- Monitor abnormal balance behavior.
- Retrain the model periodically to adapt to evolving fraud patterns.

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📈 Conclusion

The developed Random Forest model demonstrates strong capability in detecting fraudulent transactions in a highly imbalanced dataset. 

This solution can be integrated into real-time financial monitoring systems to reduce fraud-related losses.


Author: Ankit Yadav  
Project Type: Machine Learning / Fraud Detection  
