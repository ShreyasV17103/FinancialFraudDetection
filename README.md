
# 🔍 Financial Fraud Detection Using Credit Card Transactions  
Machine Learning project for detecting fraudulent credit card transactions using classical ML models, LightGBM, SMOTE, and real-time FastAPI deployment.

---

# 📌 Overview
Credit card fraud is a major global challenge, and early detection can prevent millions in losses.  
This project builds an **end-to-end fraud detection pipeline** using the famous **Credit Card Fraud Detection Dataset**.

The solution includes:

- Data preprocessing & scaling  
- Handling extreme class imbalance using **SMOTE + class weights**  
- Model training using **Logistic Regression, Random Forest, and LightGBM**  
- Evaluation using **ROC-AUC & PR-AUC (most important for imbalance)**  
- Threshold tuning for **high recall at low false-positive rate**  
- SHAP-based explainability  
- Real-time deployment using **FastAPI**

---

## 📂 Dataset
- **Source:** Kaggle – "Credit Card Fraud Detection"  
- **Rows:** 284,807  
- **Frauds:** 492 (0.17%)  
- **Imbalance ratio:** 1 fraud for every 577 normal transactions  

Dataset contains anonymized PCA components:  
`V1, V2, ..., V28`, plus `Amount`, `Time`, and target variable: `Class`  
- `Class = 1` → Fraud  
- `Class = 0` → Non-fraud

> 🔗 *Dataset is not included in repository due to licensing. Please download from Kaggle and place it in `/data`.*




