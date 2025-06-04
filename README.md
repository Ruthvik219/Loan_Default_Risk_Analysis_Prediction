# 💰 Loan Default Prediction using Machine Learning

This project leverages machine learning techniques to analyze financial and demographic data for predicting the likelihood of loan default. It includes a complete pipeline: from exploratory data analysis (EDA) to model training and prediction on unseen data.

---

## 🎯 Goals

- Understand relationships between applicant features and default behavior  
- Clean and transform raw data for modeling  
- Train robust classifiers to predict loan default risks  
- Evaluate models using industry-relevant metrics  
- Provide interpretable insights to aid in risk assessment

---

## 🧱 Project Structure
house-price-analysis/
│
├── data/ # Contains the raw dataset
│ └── loan_data.csv
│
├── notebooks/ # Jupyter Notebooks for EDA and experimentation
│ └── eda_analysis.ipynb
│
├── src/ # Core Python scripts
│ ├── data_cleaning.py
│ ├── model_building.py
│ └── risk_predictor.py
│
├── requirements.txt # Python dependencies
└── README.md # Project documentation

---

## 📊 EDA Summary

The EDA notebook explores:

- Distribution of loan defaults  
- Impact of income, loan amount, and credit score  
- Correlation analysis of numeric features  
- Visualizations for categorical trends  
- Handling missing values and anomalies

---

## 🧼 Data Preparation

Key preprocessing steps (in `data_cleaning.py`):

- Missing value handling using statistical methods  
- Encoding categorical features  
- Normalization of continuous variables  
- Splitting dataset into train-test sets
- 

---

## 🤖 Model Training & Evaluation

Performed in `model_building.py`, this step includes:

- Classifier options: Logistic Regression, Random Forest, and XGBoost  
- Model evaluation using:
  - Accuracy
  - Precision/Recall
  - F1-score
  - ROC-AUC  
- Best model saved for deployment

---



## 🧪 Run Instructions

1. **Clone this repo**
   ```bash
   git clone https://github.com/your-username/loan-default-predictor.git
   cd loan-default-predictor
pip install -r requirements.txt

now run this file
python loan_predictor.py

---
Submit a Pull Request or open an Issue to discuss changes.

🧑‍💻 Author Sunkari Ruthvik 📧 s.ruthvik14@gmail.com 🔗 GitHub

