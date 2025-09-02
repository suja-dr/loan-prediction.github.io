# 🏦 Loan Approval Prediction

This project predicts whether a loan will be **approved** or **rejected** using **Logistic Regression**.  
It is deployed as an **interactive Streamlit web app** that allows users to input applicant details and get instant predictions.

---

## 📌 Problem Statement
- Manual loan approvals are **time-consuming** and prone to **human error**.  
- Banks need a **fast, reliable, and automated** solution for loan approvals.  

**Goal:**  
To build a system that predicts loan approval accurately and improves efficiency.

---

## 📊 Dataset Overview
- **Income** – Applicant’s income  
- **Loan Amount** – Requested loan amount  
- **Credit Score** – Applicant’s credit score  
- **Loan Status** – Target variable (0 = Rejected, 1 = Approved)  

---

## 🔍 Exploratory Data Analysis
Some key insights from EDA:
- Higher income → more approvals ✅  
- Large loan amounts → higher risk ❌  
- Credit score strongly impacts approval probability 📈  

Visualizations include:
- Loan Amount vs. DTI Ratio (Line Plot)  
- Credit Score vs. Loan Amount (Scatter Plot)  
- Correlation Heatmap  
- Loan Approvals vs. Rejections (Bar/Count Plot)  

---

## 🚀 Streamlit App
### Features:
- Upload your own **CSV dataset**  
- Interactive sliders for:
  - Income  
  - Loan Amount  
  - Credit Score  
- Instant prediction: **Approved / Rejected**  
- Interactive charts for:
  - Approval vs Rejection distribution  
  - Credit Score distribution  
  - Income vs Loan Amount scatter  
  - Pie charts and line charts  

### Run the App Locally:
```bash
pip install -r requirements.txt
streamlit run app.py
