# 📊 Client Churn Prediction

This project focuses on predicting customer churn using a synthetic dataset and a logistic regression model. The goal is to identify clients who are likely to leave a service based on their usage patterns and profile data.

## 🚀 Features

The dataset includes the following features:

- `tenure`: Time with the company (in months)
- `monthly_charges`: Monthly billing amount
- `total_charges`: Total amount billed to date
- `num_support_calls`: Number of customer support calls
- `uses_internet`: Binary flag indicating internet usage (0 = No, 1 = Yes)
- `contract_type`: Type of contract
  - 0 = Month-to-month
  - 1 = One-year
  - 2 = Two-year

## 🧠 Model

The script trains a **Logistic Regression** model and evaluates its performance using:

- Accuracy
- Confusion matrix

The trained model is saved as `churn_model.pkl`.

## 🛠 How to Run

Ensure you have the required dependencies installed (see below), then run the script:

```bash
python churn_model.py
