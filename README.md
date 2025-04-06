# 🔍 Bank Churn Prediction Project

Predict whether a customer will churn (i.e., leave the bank) using machine learning techniques. This project utilizes structured customer data to train a model that helps banks identify at-risk customers early.

---

## 📁 Dataset Overview

The dataset contains 14 columns related to customer information. Below is the feature summary:

| Feature Name       | Description |
|--------------------|-------------|
| `RowNumber`        | Index of the row in dataset (not useful for modeling) |
| `CustomerId`       | Unique ID of the customer |
| `Surname`          | Customer’s surname |
| `CreditScore`      | Credit score of the customer |
| `Geography`        | Country of residence (e.g., France, Spain, Germany) |
| `Gender`           | Male / Female |
| `Age`              | Age of the customer |
| `Tenure`           | Number of years the customer has stayed with the bank |
| `Balance`          | Account balance |
| `NumOfProducts`    | Number of bank products the customer is using |
| `HasCrCard`        | Whether the customer has a credit card (1 = Yes, 0 = No) |
| `IsActiveMember`   | Whether the customer is active (1 = Yes, 0 = No) |
| `EstimatedSalary`  | Estimated annual salary |
| `Exited`           | Target Variable — 1 if the customer left the bank, 0 otherwise |

---

## 🚀 Project Goals

- Clean and preprocess data for ML modeling
- Encode categorical variables using label and one-hot encoders
- Detect and treat class imbalance via downsampling or SMOTE
- Train and evaluate a classification model (Random Forest, ANN, etc.)
- Deploy the model using Streamlit

---

## ⚙️ Tech Stack

- **Python 3**
- **Pandas / NumPy**
- **Scikit-learn**
- **TensorFlow / Keras** (for ANN)
- **Streamlit** (for web deployment)
- **Matplotlib / Seaborn** (for visualization)

---

## 🌐 Deployment

The project is deployed using **Streamlit** for interactive customer churn prediction.

### Try it out locally:
```bash
streamlit run app.py
