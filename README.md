# Employee-Exit-Survey-Analysis
<img width="2501" height="1307" alt="Untitled design" src="https://github.com/user-attachments/assets/e311e978-99f4-474f-810e-b87dce457285" />

# 🧠 Employee Exit Survey Analysis

Analyze HR data and employee exit survey responses to uncover key factors influencing employee departures.  
This project uses **data cleaning, statistical analysis, and predictive modeling** to help organizations reduce attrition and improve retention strategies.

---

## 📋 Project Overview

The goal of this project is to:
- Identify major reasons why employees leave the company.
- Understand department-wise attrition trends.
- Model voluntary vs involuntary exits using machine learning.
- Provide actionable HR insights to improve employee satisfaction and retention.

---

## 🚀 Features

- Data cleaning and preprocessing  
- Missing value imputation using median by department  
- Exploratory Data Analysis (EDA)  
- Statistical testing (Chi-square, ANOVA)  
- Predictive modeling using Logistic Regression  
- Feature importance visualization  
- Actionable HR insights and recommendations  

---

## 🧩 Technologies Used

| Category | Libraries |
|-----------|------------|
| Data Handling | `pandas`, `numpy` |
| Visualization | `matplotlib`, `seaborn` |
| Statistics | `scipy.stats` |
| Machine Learning | `scikit-learn` |
| Environment | `Jupyter Notebook` |

---

## ⚙️ Project Workflow

1. **Data Cleaning**
   - Fill missing numeric data with department-wise median.
   - Convert categorical columns to category type.
   - Create derived features like `is_senior_tenure`.

2. **Exploratory Data Analysis**
   - Visualize exit reasons, satisfaction scores, and department trends.
   - Identify patterns between tenure, manager ratings, and exit type.

3. **Statistical Analysis**
   - Chi-square test for categorical relationships.
   - ANOVA test for satisfaction differences among reasons.

4. **Predictive Modeling**
   - Target variable: `voluntary` (1) or `termination` (0)
   - Features: `tenure_years`, `satisfaction_score`, `manager_rating`, department encoding.
   - Train logistic regression to predict exit type.
   - Evaluate using precision, recall, F1-score, and ROC-AUC.

5. **Insights and Recommendations**
   - Departments with higher voluntary exits identified.
   - Satisfaction and manager rating strongly influence attrition.
   - Suggested HR strategies for retention.

---

## 📊 Example Insights

- **Top Exit Reasons:** Better Pay, Work-life Balance, Career Growth  
- **Departments with Highest Turnover:** Engineering & Sales  
- **Key Predictors:** Satisfaction Score, Manager Rating, Tenure  
- **Recommendations:**
  - Review compensation structure.
  - Introduce flexible work policies.
  - Enhance manager training and communication.
  - Promote internal career growth paths.

---

## 💾 Files

| File | Description |
|------|--------------|
| `Employee_Exit_Survey_Analysis.ipynb` | Main notebook with data analysis and modeling |
| `cleaned_exit_survey.csv` | Cleaned dataset after preprocessing |
| `Employee_Exit_Survey_Analysis_Explanation.pdf` | Detailed report explanation |
| `README.md` | Project documentation |

---

## 🧮 Model Performance

| Metric | Score |
|--------|-------|
| Accuracy | ~85% |
| Precision | 0.83 |
| Recall | 0.80 |
| F1 Score | 0.81 |
| ROC AUC | 0.88 |

---

## 🧑‍💼 Author

**Prasen Nimje**  


---

## 🌟 Acknowledgements

This project is part of HR analytics research and demonstrates how **data-driven decision-making** can reduce employee turnover and improve engagement.

If you find this project helpful, don’t forget to ⭐ **star this repository**!

---
