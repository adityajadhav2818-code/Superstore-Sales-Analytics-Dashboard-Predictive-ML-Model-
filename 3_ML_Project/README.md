# Superstore ML Model | End-to-End Machine Learning Project

## Project Overview

This project focuses on building and evaluating multiple Machine Learning models to solve a classification problem using the Superstore dataset.

The objective is to develop a model that delivers accurate, reliable, and business-impactful predictions by comparing different algorithms and selecting the best-performing one.

---

## Objectives

- Perform data preprocessing and feature engineering  
- Train multiple ML models  
- Evaluate models using performance metrics  
- Select the best model for real-world use  

---

## Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## Workflow

1. Data Cleaning  
2. Feature Engineering (One-Hot Encoding)  
3. Train-Test Split  
4. Model Training  
5. Model Evaluation  

---

## Models Used

- Logistic Regression  
- Random Forest  
- AdaBoost  
- SVM (Support Vector Machine)  

---

## Model Comparison

| Model               | Accuracy   | F1 Score   |
|--------------------|------------|------------|
| Random Forest      | **94.48%** | **96.63%** |
| Logistic Regression| 93.91%     | 96.30%     |
| AdaBoost           | 94.27%     | 96.56%     |
| SVM                | 88.91%     | 92.78%     |

---

## Model Selection

### Random Forest is the best model

**Why?**
- Highest F1 Score (96.63%)  
- Highest Accuracy (94.48%)  
- Best balance of:
  - Precision (98.08%)  
  - Recall (95.21%)  
- Strong performance on both classes  

---

## Business Interpretation

- Provides highly accurate predictions  
- Minimizes false positives and false negatives  
- Improves decision-making reliability  
- Can be applied to real-world business problems like:
  - Customer prediction  
  - Sales analysis  
  - Business optimization  

---

## Key Insights

- Ensemble models outperform basic models  
- Logistic Regression provides strong baseline performance  
- SVM achieves high recall but lower precision  

---

## Future Improvements

- Hyperparameter tuning  
- Feature selection  
- Model deployment (Streamlit / Flask)  
- Real-time prediction system  

---



