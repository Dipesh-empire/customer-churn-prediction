# 📊 Telco Customer Churn Prediction

This project uses both **Logistic Regression** and a **Transformer-based deep learning model** to predict whether a customer will churn, using the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). The goal is to compare both models and identify the better-performing approach.

## 📌 Objectives

- Build a baseline Logistic Regression model for binary classification.
- Implement a Transformer model customized for tabular data.
- Evaluate and compare both models using accuracy, precision, recall, and F1-score.
- Recommend the best model based on performance metrics.

## 🛠 Tech Stack

- **Language**: Python
- **Libraries**:
  - pandas, numpy
  - scikit-learn
  - torch (PyTorch)
  - sklearn.metrics for evaluation

##  Model Comparison

| Metric    | Logistic Regression | Transformer Model |
|-----------|---------------------|-------------------|
| Accuracy  | 0.79                | 0.78              |
| Precision | 0.62                | 0.63              |
| Recall    | 0.51                | 0.46              |
| F1 Score  | 0.56                | 0.53              |

After comparing both model performance:
- Both models had similar overall accuracy.
- The Logistic Regression model was better at catching customers who are likely to leave.
- It also offered a better balance between correct predictions and false alarms.

## Recommendation
Although the Transformer is more complex and a revised model, Logistic Regression performed better in this case.
It is faster, easier to interpret, and more effective for this customer churn prediction task.

