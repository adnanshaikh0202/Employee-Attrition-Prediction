# Employee-Attrition-Prediction

## Problem Statement

Attrition, a reduction in the workforce due to retirement or resignation, is a critical issue for organizations worldwide. High attrition rates lead to increased costs for recruitment and training and can damage the brand reputation of the company.

This project aims to help a fast-growing company become proactive in predicting employee attrition. Over the past three years, the company has experienced high employee turnover, and its HR team has mainly responded to attrition reactively. The goal of this project is to build a predictive model to forecast whether an employee is likely to leave the company based on various factors in the dataset.

## Objective

The primary objective of this project is to predict whether an employee will leave the company using available HR data. This prediction will enable the HR team to make data-driven decisions and take preventive measures to reduce attrition.

## Dataset

The dataset includes multiple features describing the employees and their work environment. These features may include:

- Employee demographics 
- Job-related variables 
- Compensation details 
- Work environment factors

## Approach

- Data Exploration: Understand the data distribution, detect any missing or incorrect values, and handle data preprocessing.
- Feature Engineering: Transform and create relevant features that may improve the predictive power of the model.
- Model Training: Implement different machine learning models and choose the one with the best performance.
- Evaluation: Measure model performance using appropriate metrics (e.g., accuracy, precision, recall, F1-score).

## Results and Recommendations

After a comprehensive evaluation, it was evident that XGB outperformed others with  Best parameters for xgb : {'xgb__learning_rate': 0.008, 'xgb__max_depth': 8, 'xgb__n_estimators': 300}. Key features contributing to attrition were identified, providing actionable insights for the HR team. We strongly recommend the implementation of this model into the company's HR system to facilitate proactive attrition management.

## Conclusion

This ML project has effectively tackled the challenge of predicting employee attrition in a rapidly growing company. The proactive approach enabled by predictive models empowers the HR team to take preventative measures, ultimately reducing attrition rates and positively impacting the company's overall performance and brand value. Continuous monitoring and periodic model updates are advised to ensure the ongoing effectiveness of the implemented solution.



