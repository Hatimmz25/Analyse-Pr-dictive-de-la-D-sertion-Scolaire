# 📊 Predictive Analysis of Student Dropout  
### Multinomial Logistic Regression (R Project)

## 📌 Overview
This project focuses on the **predictive analysis of student dropout** using a **multinomial logistic regression model**. The objective is to classify students into three possible academic outcomes:

- 🎓 Graduate  
- 📚 Enrolled  
- ❌ Dropout  

By analyzing academic, demographic, and socio-economic factors, the model helps identify **students at risk of dropping out** and supports data-driven decision-making in education.

---

## 🎯 Objectives
- Apply **multinomial logistic regression** to predict student outcomes  
- Identify **key risk factors** influencing dropout  
- Evaluate model performance using classification metrics  
- Provide **actionable recommendations** for reducing student attrition  

---

## 📂 Dataset
- 📊 **4425 student records**
- 🔢 **35 variables** (34 features + 1 target)

### Features include:
- 👤 Demographic: age, gender, nationality  
- 🎓 Academic: grades, approved units, evaluations  
- 💰 Financial: tuition payment, debtor status  
- 🎓 Support: scholarship status  
- 📈 Economic: unemployment rate, inflation, GDP  

---

## ⚙️ Methodology

### 1. Data Preparation
- Cleaning and formatting variables  
- Converting categorical variables into factors  
- Defining **Dropout as reference class**

### 2. Exploratory Data Analysis (EDA)
- Distribution of student outcomes  
- Impact of tuition payment  
- Effect of grades and scholarships  

### 3. Model Building
- Multinomial logistic regression using **R (`nnet` package)**  
- Selected key predictors:
  - Approved units (1st & 2nd semester)
  - Grades (2nd semester)
  - Tuition payment status
  - Scholarship status
  - Debtor status  

### 4. Evaluation
- Confusion matrix  
- Accuracy, precision, recall  
- Class-wise performance analysis  

---

## 📈 Results
- ✅ **Accuracy:** 72.83%  
- 🎯 Strong prediction for:
  - Dropout (Recall ≈ 80%)  
  - Graduate (Recall ≈ 94%)  
- ⚠️ Weak prediction for:
  - Enrolled (due to class imbalance)

### 🔑 Key Insights
- 📊 Academic performance (especially 2nd semester) is the **strongest predictor**
- 💰 Paying tuition on time significantly increases success probability  
- 🎓 Scholarships reduce dropout risk  
- ❗ Being in debt negatively impacts graduation chances  

---

## 🧠 Technologies Used
- **R**
- Libraries:
  - `nnet`
  - `tidyverse`
  - `caret`
  - `aod`

---

## 💡 Applications
- Early warning systems for at-risk students  
- Academic performance monitoring  
- Policy-making in education  
- Resource allocation for student support  

---

## 🚀 Future Improvements
- Try advanced models:
  - Random Forest 🌲  
  - XGBoost ⚡  
  - Neural Networks 🤖  
- Include behavioral and engagement data  
- Perform longitudinal analysis  

---

## 👥 Authors
- Mazigh Hatim  
- Moussa Mansour Ibrahim  

---

## 📚 References
- Agresti, A. (2019). *An Introduction to Categorical Data Analysis*  
- Hosmer, D. W. et al. (2013). *Applied Logistic Regression*  
- James, G. et al. (2021). *An Introduction to Statistical Learning*  

---

## ⭐ If you found this project useful, consider giving it a star!
