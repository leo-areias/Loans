
# Loan Approval Prediction

This project is a **machine learning model** designed to predict whether a loan application will be **approved or rejected** based on various input features. The model was developed using **Python**, **scikit-learn**, and **pandas**, following DataCamp code-alongs as a learning experience.

## 📌 Project Overview

Loan approval is a critical decision for financial institutions. This model aims to automate and improve the accuracy of loan acceptance predictions by analyzing key factors such as credit history, income, loan amount, and more.

The dataset contains labeled instances where:
- **1** → Loan is approved  
- **0** → Loan is rejected  

## 🛠 Technologies Used

- **Python** 🐍  
- **pandas** (Data Manipulation)  
- **scikit-learn** (Machine Learning)  
- **matplotlib & seaborn** (Data Visualization)  
- **Jupyter Notebook** (Development Environment)

## 📊 Model Performance

The classification model was trained and evaluated using **precision, recall, and F1-score metrics**. The current results show:

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| **0 (Rejected)** | 0.82 | 0.39 | 0.53 | 130 |
| **1 (Approved)** | 0.79 | 0.96 | 0.87 | 312 |

- **High recall for class 1** means the model correctly identifies most approved loans.  
- **Lower recall for class 0** suggests the model may struggle to correctly reject some loans.  
- **Precision is balanced**, but improvements can be made to reduce false positives.

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/loan-approval-prediction.git
   cd loan-approval-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook loans.ipynb
   ```

## 🔍 Next Steps

- Improve recall for rejected loans (Class 0)  
- Experiment with different algorithms (e.g., Random Forest, XGBoost)  
- Tune hyperparameters for better performance  
- Use feature engineering to enhance predictions  

## 📌 Acknowledgments

This project was developed as part of **DataCamp code-along exercises**, helping to reinforce concepts in machine learning and model evaluation.
