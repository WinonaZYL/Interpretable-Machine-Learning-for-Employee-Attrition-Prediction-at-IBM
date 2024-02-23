# Interpretable Machine Learning for Employee Attrition Prediction at IBM

## Introduction
This repository presents a machine learning project aimed at predicting employee attrition within IBM. The project utilizes various predictive features, including employee demographics, job satisfaction, and performance metrics, to develop models for accurate prediction of attrition. The main objective is to identify key factors contributing to attrition and provide insights for strategic decision-making in talent retention efforts.

## Models Evaluated
Three classification models were evaluated in this project:

1. **Logistic Regression:**
   - **Accuracy (Test):** 83.33%
   - **Pros:** Easy to explain, faster pace
   - **Cons:** Prone to overfitting due to multicollinearity among features

2. **Decision Tree:**
   - **Accuracy (Test):** 85.29% (Kaggle)
   - **Pros:** Easy to explain and interpret
   - **Cons:** Complex tree structure may lead to overfitting

3. **Random Forest:**
   - **Accuracy (Test):** 85%
   - **Pros:** Handles imbalanced data well, reduces errors
   - **Cons:** Harder to interpret compared to Decision Tree, requires defining estimator

## Discussion
- High dimensionality post-encoding and limited data size pose challenges necessitating careful data preprocessing and feature selection.
- Proper parameter tuning is crucial for improving model efficiency, as evidenced by the grid search conducted to optimize the Decision Tree model.
- The decision-making process for model selection should prioritize interpretability alongside accuracy, given the personal and varied nature of reasons for employee attrition.

## Conclusion
1. Thorough data understanding and preprocessing are essential for effective modeling.
2. Interpretability should be prioritized alongside accuracy in model selection, especially in understanding the nuanced reasons for employee attrition.

