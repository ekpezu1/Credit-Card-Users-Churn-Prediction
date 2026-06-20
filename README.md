# Credit Card Users Churn Prediction

A machine learning classification project that predicts which credit card customers at Thera Bank are likely to churn (close their credit card account). The model analyzes customer demographics, account details, and transaction behavior to identify at-risk customers before they leave.

**Problem it solves:** Thera Bank is experiencing a steep decline in credit card users, which threatens revenue from fees (annual, balance transfer, cash advance, late payment, foreign transaction, etc.). By predicting churn early, the bank can proactively improve services, address customer concerns, and implement retention strategies to prevent customers from renouncing their credit cards.

## Overview
**Goal:** Build a classification model to predict which credit card customers will churn (leave) so Thera Bank can identify at-risk customers and improve services to prevent attrition.

**Dataset:** Public credit card customer dataset from Thera Bank containing 20 features including customer demographics, account details, transaction behavior, and usage patterns. The target variable is Attrition_Flag (Attrited Customer vs. Existing Customer).

**Techniques:** Machine learning classification models (AdaBoost, Gradient Boost, Random Forest, XGBoost, Bagging) with feature engineering, data preprocessing, and model evaluation.

## 📁 Files
- `BankChurnerML_Project.ipynb` - Main Jupyter notebook with analysis and model
- `BankChurners.csv` - Public dataset used

## 🛠️ Technologies
- Python
- pandas, numpy, scikit-learn, matplotlib, seaborn, imblearn

## Business Impact
Credit cards are a major revenue source for banks through fees (annual, balance transfer, cash advance, late payment, foreign transaction, etc.). Customer churn leads to significant revenue loss. This model enables Thera Bank to:

Proactively identify customers likely to leave
Understand key factors driving attrition
Implement targeted retention strategies
Improve customer services and reduce churn

## 🚀 How to Run
1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook: `jupyter notebook notebook.ipynb`

## 📝 License
This project is licensed under the MIT License
