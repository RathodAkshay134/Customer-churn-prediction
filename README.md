# Customer Churn Prediction using Machine Learning (XGBoost)

## 📌 Business Problem
No-Churn Telecom is facing high customer churn due to increasing competition. The company wants to identify customers who are likely to leave and take preventive actions through targeted retention strategies.

---

## 🎯 Project Objective
- Identify key factors influencing customer churn  
- Build a predictive model to classify churn customers  
- Help business design targeted retention campaigns  

---

## 📊 Dataset
- Source: Telecom dataset (SQL database)
- Records: ~4600 customers  
- Features: 20+ (usage, plans, customer service calls)  
- Target Variable: **Churn (Yes/No)**  

---

## 🧠 Approach

### Data Preprocessing
- Converted incorrect data types (object → numeric)  
- Cleaned and standardized dataset  
- Removed redundant features  

### Exploratory Data Analysis (EDA)
- Analyzed usage patterns and customer behavior  
- Observed class imbalance (~6:1 ratio)  

### Feature Engineering
- Selected important features  
- Removed correlated variables  

### Handling Imbalance
- Applied **SMOTE** to balance the dataset  

---

## 🤖 Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- XGBoost  

---

## 📈 Model Comparison

| Model | Accuracy | F1 Score |
|------|---------|---------|
| XGBoost | 0.96 | 0.83 |
| Random Forest | 0.96 | 0.81 |
| Gradient Boosting | 0.96 | 0.81 |
| Logistic Regression | 0.76 | 0.44 |

---

## 🏆 Final Model
- Selected Model: **XGBoost**
- Reason: Handles non-linear patterns and performs well on imbalanced data  

---

## 🔑 Key Insights
- Customers with high **customer service calls** have higher churn probability  
- Users with **international plans** show increased churn risk  
- Call usage patterns strongly influence churn  

---

## 💡 Business Impact
- Helps identify high-risk customers early  
- Enables targeted retention strategies  
- Improves customer satisfaction and reduces churn rate  

---

## 🛠 Tech Stack
- Python (Pandas, NumPy, Scikit-learn)  
- Machine Learning (XGBoost, Random Forest)  
- SQL (Data extraction)  
- Visualization (Matplotlib, Seaborn)  

---
