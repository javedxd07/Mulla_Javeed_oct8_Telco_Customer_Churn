# Telecom Customer Churn Prediction

## 📊 Project Results

| Metric | Result |
|---|---:|
| **Accuracy** | **80.55%** |
| **Precision** | **65.72%** |
| **Recall** | **55.88%** |
| **F1 Score** | **60.40%** |
| **ROC-AUC** | **84.19%** |
| **Churn Customers Correctly Identified (TP)** | **209** |
| **Non-Churn Customers Misclassified (FP)** | **109** |
| **Churn Customers Missed (FN)** | **165** |
| **Non-Churn Customers Correctly Identified (TN)** | **926** |

### 🔍 Key Finding

The Logistic Regression model achieved an **80.55% accuracy** and an **84.19% ROC-AUC**.

The model correctly identified **209 customers who actually churned**, but missed **165 churn customers**.

Since missing a real churn customer can result in lost revenue, **Recall is an important metric for this business problem**.

### 💼 Business Recommendation

Use the predicted churn probability to identify **high-risk customers** and target them with personalized retention offers, discounts, better support, or suitable contract plans.

### 🛠️ Technical Improvement

The model currently uses a **0.50 classification threshold**. A better threshold can be selected based on the business cost of **False Positives vs False Negatives**, which may help identify more potential churn customers.
