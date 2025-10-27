# CaseStudy1DDS
Frito Lay Attrition Cace Study
Executive Summary
Project 1 – Employee Attrition Analysis

Author: Koosha Tabesh


1. Overall Question of Interest and Setting

The central question of this study was:

Which factors are most strongly associated with employee attrition at Frito Lay, and how accurately can we predict employees who are likely to leave the company?

Frito Lay engaged DDSAnalytics to analyze workforce data, identify the key predictors of attrition, and build predictive models to support proactive retention and talent management.


2. Key Factors Related to Attrition

Both numerical and categorical features were examined to determine their relationships with employee attrition.

Top Numeric Predictors

Total Working Years – Employees with fewer total working years are more likely to leave.

Distance From Home – Longer commute distances correlate with higher attrition rates.

Stock Option Level – Employees with low or no stock options are more likely to leave.

Work-Life Balance – Lower work-life balance scores are strongly linked to higher turnover.

Top Categorical Predictors

OverTime – Employees working overtime frequently have the highest attrition rate.

Job Role – Sales Representatives and Laboratory Technicians show elevated turnover levels.

Marital Status – Single employees tend to leave more often than married employees.

Department – Minor differences exist, with Sales showing slightly higher attrition.


3. Model Performance Summary
Naive Bayes Model

Accuracy: 72.03%

Sensitivity (Stayed): 72.60%

Specificity (Left): 69.05%

Balanced Accuracy: 70.83%

Kappa: 0.2868

The Naive Bayes model effectively identified employees who stayed or left, providing the most balanced predictive performance.

k-Nearest Neighbors (kNN) Model

Accuracy: 66.28%

Sensitivity (Stayed): 65.75%

Specificity (Left): 69.05%

Balanced Accuracy: 67.40%

Kappa: 0.218

The kNN model showed consistent but slightly lower accuracy. However, after applying SMOTE (Synthetic Minority Oversampling Technique) and 10-fold cross-validation, it maintained reliable sensitivity and specificity levels across folds.


4. Additional Findings and Inferences

Attrition rates are highest among younger employees, those with lower income, and employees working overtime.

Gender and Department showed minimal impact on turnover, indicating broader organizational patterns.

Predictive modeling demonstrated that attrition can be anticipated with ~70% accuracy, enabling targeted retention actions.

Cost analysis suggests that implementing proactive retention programs using these insights could reduce total attrition costs by up to 1 to 2 million dollors annually through improved employee engagement and reduced recruitment expenses.


Summary Conclusion

Both models support the conclusion that workload, tenure, and compensation-related factors are the primary drivers of attrition.
The Naive Bayes model offers a strong, interpretable baseline for Frito Lay’s HR analytics program, while kNN provides an alternative approach for cross-validated, data-driven decision-making.
