# Predicting Hospital Length of Stay (LOS)

## Introduction

Healthcare organizations are under increasing pressure to improve patient care outcomes and achieve better care. While this situation represents a challenge, it also offers organizations an opportunity to dramatically improve the quality of care by leveraging more value and insights from their data. Health care analytics refers to the analysis of data using quantitative and qualitative techniques to explore trends and patterns in the acquired data. While healthcare management uses various metrics for performance, a patient’s length of stay is an important one.

Being able to predict the length of stay (LOS) allows hospitals to optimize their treatment plans to reduce LOS, to reduce infection rates among patients, staff, and visitors.

## Objectives

- Predict the duration of hospital stays to improve resource management.
- Analyze various factors influencing the length of stay.
- Develop and evaluate multiple machine learning models to identify the best-performing model.

## Data Source

The dataset consists of de-identified electronic health records from a tertiary general university hospital, comprising 318,438 records with 18 variables.
  
## Skills and Topics Covered

- **Data Exploration**: Understanding data distribution and identifying key patterns.
- **Data Preprocessing**: Cleaning and preparing the dataset, handling missing values, and correcting errors.
- **Feature Engineering**: Creating new features and selecting relevant ones to improve model performance.
- **Data Visualization**: Using plots and charts to visualize data distribution and model outcomes.
- **Machine Learning Models**: Implementing and evaluating models like Decision Tree, Random Forest, Naive Bayes, and XGBoost.
- **Model Evaluation**: Assessing performance using accuracy, precision, recall, and F1 score.
- **Correlation and Association Analysis**: Identifying relationships between variables using statistical measures.
- **Normalization**: Scaling numerical variables to enhance model accuracy.

## Results

- **Decision Tree**: Achieved 95% accuracy with an F1 score of 93%.
- **Random Forest**: Demonstrated the highest performance with 99% accuracy, 98% precision, and a 99% F1 score.
- **Naive Bayes**: Overfitted the data due to the imbalanced nature of the dataset.
- **XGBoost**: Showed high accuracy but indicated overfitting.

**Conclusion**: The Random Forest classifier is recommended for predicting hospital stay duration due to its superior accuracy and performance. Implementing this model can significantly enhance hospital resource management and patient care.
