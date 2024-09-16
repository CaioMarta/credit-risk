# Credit Risk Assessment

## Project Description

This project aims to develop a machine learning model to predict the probability of customer default for a financial institution. Default occurs when a customer fails to meet their financial obligations, which can cause significant losses for institutions. The developed model helps predict which customers are at higher risk of defaulting on their debts, allowing institutions to take preventive measures.

## Problem Context

Financial institutions constantly face the challenge of managing credit risk. Accurately assessing the likelihood of default is essential to minimize financial losses. This project seeks to create a predictive solution based on real-world data to assist institutions in this process.

The dataset used in this project contains 32,581 entries with 12 different variables. The data was obtained from the Kaggle platform and represents a realistic sample of a financial credit scenario.

## Objective

The main objective of this project is to build a machine learning model capable of predicting whether a customer will fail to meet their financial obligations.

## Methodology

1. **Data Preprocessing:**
   - Data import and consistency check.
   - Handling missing values and categorizing variables.
   - Applying techniques to handle class imbalance, such as SMOTE and RandomUnderSampler.

2. **Machine Learning Models Used:**
   - **Random Forest**
   - **XGBoost**
   - **Logistic Regression**
   - **Naive Bayes**

3. **Validation:**
   - Splitting the data into training and test sets (holdout method).
   - Cross-validation for hyperparameter tuning.
   - Evaluation metrics such as ROC-AUC, F1-Score, and Confusion Matrix.

## Technologies Used

- **Python**: Main language for data analysis and modeling.
- **Libraries**:
  - pandas for data manipulation.
  - scikit-learn for modeling and model evaluation.
  - imblearn for data balancing techniques.
  - matplotlib and seaborn for data visualization.
  - xgboost for the XGBoost model implementation.


## Results

The final model achieved an accuracy of 89%. The XGBoost model was the most efficient, balancing precision and recall to identify defaulting customers.

## Conclusion

This project demonstrated the effectiveness of using machine learning algorithms to predict credit risk. The practical application of this model can help financial institutions mitigate risks and reduce losses caused by default.

## Author

- [Caio Marta](https://github.com/CaioMarta)

---

This README provides a professional and concise overview of your project. Let me know if you'd like to add any specific details!
