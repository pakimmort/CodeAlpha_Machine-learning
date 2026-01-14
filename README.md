# 📊 Credit Scoring Model using Machine Learning

## 📌 Project Overview
This project focuses on building a **Credit Scoring Model** to predict an individual's **creditworthiness** based on past financial and behavioral data. The model helps financial institutions assess the risk of loan default and make data-driven lending decisions.

Multiple **classification algorithms** are implemented and compared to identify the most effective model.

---

## 🎯 Objective
To predict whether an individual is:
- **Creditworthy (Low Risk)** → `1`
- **Not Creditworthy (High Risk)** → `0`

using historical financial data.

---

## 🗂️ Dataset Description
The dataset contains financial attributes such as:

- `income` – Monthly or annual income  
- `debt` – Total outstanding debt  
- `credit_utilization` – Percentage of credit used  
- `payment_history` – Record of late/missed payments  
- `employment_length` – Years of employment  
- `credit_history_length` – Length of credit history  
- `target` – Creditworthiness label (0 or 1)

> ⚠️ Dataset can be replaced with any real-world credit dataset.

---

## 🛠️ Technologies Used
- **Python**
- **Pandas & NumPy** – Data handling
- **Matplotlib & Seaborn** – Visualization
- **Scikit-learn** – Machine Learning models & evaluation

---

## 🔍 Methodology

### 1️⃣ Data Preprocessing
- Handling missing values using **median imputation**
- Feature scaling using **StandardScaler**
- Train-test split with stratification

---

### 2️⃣ Feature Engineering
- Creation of meaningful financial ratios
- Removal of irrelevant or redundant features
- Improved model interpretability

---

### 3️⃣ Models Implemented
- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**

---

### 4️⃣ Model Training
- 80% Training data
- 20% Testing data
- Random state fixed for reproducibility

---

## 📈 Evaluation Metrics
The models are evaluated using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **ROC-AUC Score**
- **Confusion Matrix**
- **ROC Curve**

> 🔑 Recall is prioritized to reduce false approvals of high-risk applicants.

---

## 📊 Results & Comparison
- Performance of all three models is compared
- ROC curves are plotted for visual comparison
- **Random Forest** generally performs best due to ensemble learning

---

## 🔎 Feature Importance
For tree-based models, feature importance is extracted to identify the most influential financial factors affecting credit risk.

---

## 📁 Project Structure
Credit-Scoring-Model/
│
├── credit_data.csv
├── credit_scoring_model.ipynb
├── README.md
└── requirements.txt
