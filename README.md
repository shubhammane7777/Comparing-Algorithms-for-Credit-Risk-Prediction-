# Credit Risk Prediction: Comparison of Algorithms

This repository contains a Jupyter Notebook that compares multiple machine learning algorithms for **credit risk prediction**. The goal is to evaluate different classification models and identify which performs best in predicting whether a loan applicant is likely to default.

---

## 🚀 Project Overview
Credit risk assessment is one of the most critical tasks in the financial industry. Traditional methods often fail to capture complex patterns in borrower data.  
This project applies and compares different machine learning algorithms to predict credit risk, focusing on **accuracy, precision, recall, and AUC score**.

---

## 📂 Repository Contents
- `Comparison_of_algorithms_of_credit_risk_for_prediction_.ipynb` — Main notebook with full workflow
- `README.md` — Documentation (this file)
- `requirements.txt` — List of dependencies (see below)

---

## 🔍 Methods Used
The notebook includes:
- **Exploratory Data Analysis (EDA)**
- **Data Preprocessing** (handling missing values, encoding categorical variables, scaling)
- **Model Training & Comparison**:
  - Logistic Regression
  - Decision Trees
  - Random Forest
  - Gradient Boosting (XGBoost / LightGBM)
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
  - Neural Networks (if included)
- **Evaluation Metrics**:
  - Accuracy
  - Precision, Recall, F1-score
  - ROC Curve & AUC

---

## 📊 Dataset
The dataset consists of borrower information and loan status (good/bad credit).  
Typical features include:
- Age, Income, Employment Status  
- Credit History, Loan Amount, Duration  
- Other financial/behavioral attributes  

> ⚠️ If you are using a public dataset (e.g., **German Credit Dataset**, **Kaggle Credit Risk Dataset**), please add the source link here.

---

## 🛠️ Installation & Setup
To run this project locally:

```bash
# Clone the repository
git clone https://github.com/your-username/credit-risk-prediction.git
cd credit-risk-prediction

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
