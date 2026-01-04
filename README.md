# Predicting Employee Retention (HR Analytics)
*Using Logistic Regression to Predict Attrition and Foster Workforce Loyalty*

## 🎯 Business Objective
A technology company aims to shift from reactive turnover management to proactive employee retention. This project develops a **Logistic Regression** model to predict the likelihood of an employee leaving based on demographics, job satisfaction, performance metrics, and tenure.

## 📁 Repository Structure
- **[data/](./data/):** Contains the employee dataset used for model training and testing.
- **[docs/](./docs/):** Contains the [Logistic Regression Analysis PDF](./docs/Logistic%20Regression%20Assignment.pdf) featuring ROC Curves and evaluation metrics.
- **[notebooks/](./notebooks/):** Contains the [Python Starter Notebook](./notebooks/Predicting_Employee_Retention_Starter.ipynb) with model development.



## 📊 Model Performance & Metrics
The model was optimized for **Sensitivity** to ensure HR doesn't miss employees at risk of leaving:
- **Sensitivity (Recall): 83.37%** — Effectively detects 83% of employees likely to leave.
- **ROC-AUC Score: 0.81** — Indicates strong classification ability in distinguishing between "stayers" and "leavers."
- **Accuracy: 59.6%** — A moderate baseline that prioritized high recall over general accuracy to meet HR needs.

## 🛠️ Technical Workflow
- **Data Preprocessing:** Handled missing values and identified outliers in Income and Age.
- **Statistical Analysis:** Used **VIF (Variance Inflation Factor)** to check for multicollinearity, ensuring independent feature impact.
- **Classification:** Implemented Logistic Regression with an **Optimal Cutoff** determined via the ROC Curve.

## 🎓 Academic Context
This is the second major project of the **Executive PG Programme in Data Science and AI at IIIT Bangalore** (affiliated with upGrad). It marks the transition from purely exploratory work into predictive machine learning.

---
