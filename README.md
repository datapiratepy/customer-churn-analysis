# Customer Churn Analysis (Python + Power BI)

## Project Overview

Customer churn is a critical problem for subscription-based businesses, directly impacting revenue and growth. This project analyzes customer churn behavior using a combination of Python-based data analysis and Power BI visualization to identify key drivers of churn and provide actionable business insights.

The project follows an end-to-end analytics workflow, including data cleaning, exploratory data analysis (EDA), basic machine learning, and interactive dashboard development.

---

## Objectives

- Understand customer behavior and identify patterns leading to churn  
- Perform data cleaning and preprocessing on a real-world dataset  
- Conduct exploratory data analysis to uncover trends and relationships  
- Build a basic machine learning model to predict churn  
- Develop an interactive dashboard for business stakeholders  
- Provide actionable insights to improve customer retention  

---

## Dataset

- Dataset: Telco Customer Churn Dataset  
- Contains customer information such as:
  - Demographics  
  - Account details  
  - Services subscribed  
  - Payment methods  
  - Tenure  
  - Churn status  

---

## Data Preprocessing (Python)

Performed using **Pandas**:

- Handled missing values in `TotalCharges`  
- Converted data types appropriately  
- Removed irrelevant columns (e.g., customer ID)  
- Encoded categorical variables using one-hot encoding  
- Prepared dataset for analysis and modeling  

---

## Exploratory Data Analysis (EDA)

Conducted using **Matplotlib and Seaborn**:

Key analyses performed:
- Churn distribution analysis  
- Churn by gender and senior citizen status  
- Churn by contract type  
- Churn vs tenure analysis  
- Identification of high-risk customer segments  

---

## Machine Learning (Basic)

Implemented using **Scikit-learn**:

- Built a classification model to predict churn  
- Evaluated using:
  - Accuracy  
  - Precision  
  - Recall  
  - Confusion Matrix  

### Key Learning:
- Accuracy alone is misleading for imbalanced data  
- Recall is more important in churn prediction (detecting potential churners)  
- Applied class balancing to improve churn detection  

---

## Power BI Dashboard

Developed an interactive dashboard to present insights visually.

### Key Visuals:

- **Churn Rate KPI**
- **Churn by Contract Type**
- **Churn by Tenure Group**
- **Churn by Payment Method**
- **Churn by Internet Service**

---

## Key Insights

### 1. Contract Type is the Strongest Driver
- Month-to-month customers show ~40%+ churn  
- Two-year contract customers show ~3% churn  
- Longer commitment significantly reduces churn  

---

### 2. Early Customer Lifecycle is Critical
- Customers within first 12 months show highest churn (~45%+)  
- Long-term customers (48+ months) are highly stable  

---

### 3. Payment Method Impacts Retention
- Electronic check users have the highest churn  
- Automatic payment users (credit card/bank transfer) show lower churn  
- Payment friction influences customer retention  

---

### 4. Fiber Optic Users Have Higher Churn
- Likely due to higher pricing and expectations  
- Indicates need for improved service/value proposition  

---

## Business Recommendations

- Encourage long-term contracts through incentives  
- Improve onboarding experience in first 3 months  
- Promote automatic payment methods  
- Enhance service quality for high-value customers (fiber users)  

---

## Tools & Technologies

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Power BI**
- **DAX**

---

## Key Learnings

- Importance of data cleaning in real-world datasets  
- Difference between accuracy and meaningful evaluation metrics  
- Translating data analysis into business insights  
- Building dashboards for non-technical stakeholders  
- Combining Python and Power BI for end-to-end analytics  

---

## Future Improvements

- Use advanced ML models (Random Forest, XGBoost)  
- Deploy model as a web application  
- Integrate real-time data pipelines  
- Add customer segmentation using clustering  

---

## Conclusion

This project demonstrates how data analysis and visualization can be used to understand customer behavior, identify churn drivers, and support data-driven decision-making in a business context.

---
