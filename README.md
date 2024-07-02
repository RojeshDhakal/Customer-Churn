# <b> Data Analysis and Transformation Summary </b>

# Overview:
The CustomerChurn dataset comprises 7043 entries with 20 features, primarily focused on customer demographics, services subscribed, and churn status. The goal is to analyze factors influencing customer churn.

# Data Cleaning:

- Data Types: Converted 'TotalCharges' to numeric, handled erroneous values.
- Categorical Data: Encoded binary categorical variables ('gender', 'Partner', 'Dependents', 'PhoneService', 'PaperlessBilling') into numeric format for analysis.

# <b>Feature Engineering: </b>

## Handling Service Categories:

- Replaced 'No internet service' and 'No phone service' with 'No' in service-related columns.
- Encoded categorical variables ('MultipleLines', 'OnlineSecurity', 'OnlineBackup', 'DeviceProtection', 'TechSupport', 'StreamingTV', 'StreamingMovies') to binary format.
## One-Hot Encoding:

-Applied one-hot encoding to 'InternetService', 'Contract', and 'PaymentMethod' columns to prepare categorical data for machine learning models.

# Insights:

## Service Usage:

- Most customers prefer Fiber optic (3096) and DSL (2421) internet services.
- Majority opt for month-to-month contracts (3875), followed by two-year (1695) and one-year (1473) contracts.
- Electronic check (2365) is the most common payment method.
  
## Customer Behavior:

-Significant churn observed among customers with Fiber optic internet service and month-to-month contracts.
-Customers with no additional services like OnlineSecurity, TechSupport, and Backup show higher churn rates.

# Conclusion:
Understanding these patterns can guide targeted marketing efforts and service improvements to reduce churn. Further predictive modeling can leverage these insights for proactive customer retention strategies.
