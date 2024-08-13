

# Bank Churn Modeling

**Presented by: Douglas Domingo**  
**Date: August 2024**

---

# Introduction

- Analyze customer churn behavior
- Predictive modeling to identify churn patterns
- Strategies for customer retention

---

# Data Overview

- Dataset: Churn Modeling.csv
- Key Features:
  - Credit Score
  - Geography
  - Gender
  - Age
  - Tenure
  - Balance
  - Number of Products
  - Has Credit Card
  - Is Active Member
  - Estimated Salary
  - Churn Status

---

# Data Exploration

- Checked for null values
- Summary statistics:
  - Mean, median, range, etc.
- Insights into data distribution through visualization

---

# Data Preprocessing

- Binning of credit scores:
  - Very bad, Bad, OK, Good, Excellent
- Salary balance ratio:
  - designed to understand how much a customer saves
- Correlation Matrix:
  - designed to look for which features may have an impact on churn rates

---

# Data Visualization

- **Credit Score Distribution**
  - Most scores between 600 and 700

- **Age Distribution**
  - Most customers aged late 20s to late 40s

- **Number of Products**
  - Customers with more than 2 products are more liekly to leave

- **Active Membership**
  - customers between 40-60 years old are more likely to leave

- **Correlation matrix**
  - Most scores between 600 and 700

---

# Modeling Approach

- Model Selection:
  - Tensor Flow- main model for technical skill demonstration
  - Decision Trees
  - Random Forests

- Evaluation Metrics:
  - Accuracy, Precision, Recall, F1-score

---

# Conclusion

- Key Findings:
  - the common patterns in customer churn are:
      - the customer is between the ages of 40-60
      - has more than 2 products
      - the customer is not an active member
  - Tensor flow model shows 86% accuracy in predicting churn
      - demographic data can be used by other departments for churn mitigation 

- Future Work:
  - Applying the model to predict and mitigate churn in real time
  - testing the model accuracy on real world data or a similar data set
