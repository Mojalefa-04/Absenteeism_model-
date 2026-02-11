#  Employee Absente﻿eism Prediction Model

## Project Overview
This project focuses on solving a real-world business problem by predicting whether an employee is likely to be absent from work for an **excessive amount of hours (>3 hours)** during a workday.

Employee absenteeism can negatively impact productivity, workflow planning, and operational efficiency. By leveraging machine learning and data analytics, this project provides insights that help businesses make **data-driven workforce management decisions**.

---

## Business Problem
Employees may be absent for various reasons, leading to disruptions in business operations and reduced productivity.

Organizations need a way to:
- Identify employees at risk of excessive absenteeism
- Understand key factors driving absentee behavior
- Optimize operational workflows proactively

---

## Project Goal
Develop a predictive model that determines whether an employee is likely to be absent from work for **more than 3 hours** in a workday.

This enables businesses to:
- Anticipate operational disruptions
- Improve workforce planning
- Enhance productivity through proactive decision-making

---

## Tools 
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Pickle
- Tableau Public

---

## Project Workflow

### 1. Data Preprocessing
- Cleaned and transformed raw absenteeism data
- Hand﻿led categorical variables
- Prepared features for machine learning modeling

### 2. Model Development
- Built a Logistic Regression model
- Generated predictions and probability scores

### 3. Module Creation
- Integrated preprocessing and machine learning pipelines
- Created a reusable Absenteeism Prediction Module

### 4. Deployment & Output Generation
- Deployed the module
- Exported predictions and probabilities for business analysis

### 5. Data Visualization
- Imported model outputs into Tableau
- Per﻿formed analytical exploration and visualization

---

## Key Findings

### Absence Reasons vs Probability
- **Reason 1 (Serious Disease):** Probability of excessive absenteeism > 50%
- **Reason 2 (Pregnancy Related):** No meaningful impact observed
- **Reason 3 (Symptoms of Diseases):** Mixed probability distribution
- **Reason 4 (Light Reasons e.g., Blood Donation):** Probability < 50%

### Transportation Expense & Children
- Higher transportation expenses are associated with increased absenteeism probability

### Age vs Probability
- Employees aged **30–40** show an average probability below 50%
  
---
Note: The link for my Tableau visualizations is in the Tableau folder in my repository.
---

## Business Impact
This project demonstrates how machine learning can:
- Identify absenteeism risk patterns
- Improve workforce productivity planning
- Support data-driven operational decisions
