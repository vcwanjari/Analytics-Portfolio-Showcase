# Predicting Employee Churn at Salifort Motors

## Project Overview

The goal of this project is to develop a machine learning model that can predict employee churn at Salifort Motors, an automobile manufacturing company. Employee churn, or turnover, can have significant impacts on a company's productivity, culture, and bottom line. By identifying employees who are at risk of leaving the organization, Salifort Motors can take proactive measures to mitigate churn and improve employee retention.

## Dataset

The dataset used for this project contains historical employee data, including various attributes such as job satisfaction, years of experience, performance metrics, and other relevant factors. It includes both churned and retained employees, allowing us to build a predictive model based on past patterns and indicators of churn.

## Approach

1. **Data Preprocessing**: The first step in our analysis was to preprocess the dataset. This involved handling missing values, encoding categorical variables, and scaling numerical features as necessary. We also conducted exploratory data analysis to gain insights into the data and identify any data quality issues.

2. **Feature Engineering**: To enhance the predictive power of our model, we performed feature engineering. This involved creating new features, such as employee tenure, performance-to-salary ratio, and satisfaction-to-average department satisfaction ratio. We also identified and selected relevant features based on domain knowledge and statistical analysis.

3. **Model Selection and Training**: We experimented with several machine learning algorithms, including logistic regression, decision trees, random forests, and gradient boosting. We evaluated each model's performance using appropriate evaluation metrics, such as accuracy, precision, recall, and F1-score. The best-performing model was selected based on these metrics.

4. **Model Evaluation and Interpretation**: After selecting the best model, we evaluated its performance on an independent test set to ensure its generalization capabilities. We also assessed the importance of different features in predicting employee churn using feature importance techniques. This analysis provides insights into the key factors contributing to churn and helps identify areas for intervention.

## Key Findings

The models and the feature importances extracted from the models confirm that employees at the company are overworked.
To retain employees, the following recommendations could be presented to the stakeholders:
- Cap the number of projects that employees can work on.
- Consider promoting employees who have been with the company for atleast four years, or conduct further investigation about why four-year tenured employees are so dissatisfied.
-If employees aren't familiar with the company's overtime pay policies, inform them about this. If the expectations around workload and time off aren't explicit, make them clear. 
- Hold company-wide and within-team discussions to understand and address the company work culture, across the board and in specific contexts.
-  High evaluation scores should not be reserved for employees who work 200+ hours per month. Consider a proportionate scale for rewarding employees who contribute more/put in more effort. 


By leveraging the insights and recommendations provided by our predictive model, Salifort Motors can proactively address employee churn, foster a more engaged workforce, and ultimately improve overall organizational performance.

## Conclusion

The "Predicting Employee Churn at Salifort Motors" project demonstrates the use of machine learning techniques to predict employee churn and provide valuable insights for employee retention strategies. By accurately identifying employees at risk of leaving, Salifort Motors can take proactive steps to improve retention, foster a positive work environment, and maximize employee satisfaction and productivity.


