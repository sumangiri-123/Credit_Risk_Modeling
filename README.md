# 💳 Credit Risk Prediction

A Machine Learning-based web application built with **Streamlit** to predict whether a customer is likely to **default on a loan** based on their financial and credit-related information.

---

## 🚀 Features

- Predicts loan default risk in real time
- User-friendly Streamlit interface
- Uses a trained Machine Learning model
- Automatic feature preprocessing
- Displays prediction probability
- Fast and interactive

---

## 📂 Project Structure

```
credit_risk_app/
│── artifacts/
│   └── model_data.joblib
│
│── main.py
│── prediction_helper.py
│── requirements.txt
│── README.md
```

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Joblib

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/sumangiri-123/Credit_Risk_Modeling.git
```

### 2. Navigate to the project folder

```bash
cd credit-risk-prediction
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
streamlit run main.py
```

---

## 📊 Input Features

The application uses customer financial information such as:

- Age
- Annual Income
- Loan Amount
- Loan Tenure
- Number of Open Accounts
- Credit Utilization Ratio
- Delinquent Ratio
- Average DPD per Delinquency
- Residence Type
- Loan Purpose

---

## 🎯 Prediction Output

The model predicts one of the following:

- ✅ **Low Credit Risk (Non-Default)**
- ⚠️ **High Credit Risk (Default)**

It also displays the prediction probability.

---

## 📁 Model

The trained model is stored in:

```
artifacts/model_data.joblib
```


## 📄 License

This project is developed for educational and learning purposes.