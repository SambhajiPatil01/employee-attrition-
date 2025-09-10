# employee-attrition-
This project explores employee data to understand the factors behind attrition and predict whether an employee is likely to leave the company. By analyzing HR records, we gain insights into employee behavior and build machine learning models to support HR teams in reducing turnover.

## Employee Attrition Analysis
Employee attrition is a major challenge for organizations, leading to extra hiring costs, loss of skilled talent, and reduced productivity. The aim of this project is to analyze workforce data and identify patterns that explain why employees leave, and then use machine learning models to predict attrition.

## Dataset
The dataset contains details of 1,470 employees with 35 features. 

## Key Insights
- Employees who work overtime are more likely to leave
- Low salary bands show higher attrition rates compared to higher salary groups
- Sales and HR departments often experience more attrition compared to R&D
- Longer commute distances (Distance from Home) increase the risk of leaving
- Low job satisfaction and poor work-life balance are strong predictors of attrition
- Younger employees and those with fewer years at the company are more likely to quit

## Machine Learning Models
We applied different algorithms to predict employee attrition:
- Logistic Regression → Good baseline, easy to interpret
- Random Forest → High accuracy and explains feature importance well
- XGBoost / Gradient Boosting → Best overall performance for prediction
  
## Best Algorithm:
- XGBoost and Random Forest give the most accurate predictions
- Logistic Regression is useful for HR when model interpretability is needed
