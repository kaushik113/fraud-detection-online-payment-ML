# 💳 Online Payment Fraud Detection

A machine learning project focused on identifying **fraudulent online transactions** using various classification algorithms.  
The system analyzes key transaction patterns to classify each payment as **Fraudulent (1)** or **Genuine (0)**.

---

## 📂 Dataset

**Source:** [Google Drive Link](https://drive.google.com/file/d/133E0TDrfIjnhwRoGTw9OEozwBXUL38D8/view?usp=sharing)  

The dataset records simulated financial transactions over time, including sender and receiver account balances.

| Column | Meaning |
|--------|----------|
| `step` | Time interval (in hours) |
| `type` | Transaction category (e.g., CASH_OUT, TRANSFER) |
| `amount` | Transaction amount |
| `nameOrig` | ID of the sender account |
| `oldbalanceOrg` | Sender’s balance before transaction |
| `newbalanceOrg` | Sender’s balance after transaction |
| `nameDest` | ID of the receiver account |
| `oldbalanceDest` | Receiver’s balance before transaction |
| `newbalanceDest` | Receiver’s balance after transaction |
| `isFraud` | Label → **1 for Fraudulent**, **0 for Legitimate** |

---

## 🧠 Machine Learning Models

Several ML models are compared to evaluate fraud detection performance:

| Model | Description |
|-------|--------------|
| **Logistic Regression** | Establishes a linear boundary for binary classification. |
| **Support Vector Classifier (SVC)** | Maximizes the margin between fraud and genuine transactions. |
| **Random Forest** | Combines multiple decision trees to improve stability and reduce overfitting. |
| **XGBoost** | Gradient boosting technique optimized for imbalanced datasets. |

---

## ⚙️ Tech Stack

- **Language:** Python  
- **Core Libraries:**  
  - `pandas`, `numpy` – data manipulation and analysis  
  - `matplotlib`, `seaborn` – visualization and exploratory analysis  
  - `scikit-learn` – model training and evaluation  
  - `xgboost` – gradient boosting implementation  

---

## 🚀 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/<your-username>/online-payment-fraud-detection.git
   cd online-payment-fraud-detection
