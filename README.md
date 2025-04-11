# 🧠 Metaverse Transactions EDA

Exploratory Data Analysis (EDA) project focused on understanding risk patterns, user behavior, and potential fraud in metaverse transaction data.

---

## 📌 Objective

To explore and analyze transaction-level data from a metaverse platform in order to:
- Identify patterns of user behavior
- Understand distributions and correlations between key variables
- Detect risk-prone or potentially fraudulent activities

---

## 📂 Dataset

The dataset contains transaction records with fields such as:
- `transaction_type` (e.g., purchase, scam, phishing)
- `amount`
- `risk_score`
- `session_duration`
- `login_frequency`
- `region`
- `timestamp`  
*(and others)*

---

## 🔍 Analysis Performed

### ✅ Univariate Analysis (10+)
- Distribution of amount, session duration, and risk score
- Frequency of transaction types and regions

### ✅ Bivariate Analysis (15+)
- Risk score vs amount
- Transaction type vs region
- Session duration vs transaction type
- Heatmaps and scatterplots

### ✅ Multivariate Analysis
- Risk vs amount colored by transaction type
- 3D relationships between time, session duration, and risk
- Fraud detection patterns across multiple dimensions

### ✅ Feature Engineering
- `is_fraud` (binary flag for scam/phishing)
- `risk_bucket` (Low, Medium, High based on `risk_score`)
- Time-based features (hour of transaction, etc.)

---


## 🚀 Future Scope

- Build a predictive fraud detection model
- Perform user segmentation through clustering
- Develop anomaly detection systems for real-time fraud alerting

---

## 📎 Requirements

- Python 3.7+
- pandas, numpy, matplotlib, seaborn
- jupyter (optional, for running the notebook)

Install dependencies with:

```bash
pip install -r requirements.txt
