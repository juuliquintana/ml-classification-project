# Machine Learning Classification Model

This repository contains the source code and resources necessary to develop, train, and evaluate a classification model that determines eligibility for a free premium installment plan. The project utilizes three datasets: main, paid, and address.

## Project Purpose
The objective of this project is to create a classification model to identify clients eligible for a free premium installment plan based on their payment behavior.

## Technologies and Tools Used
- **Python:** Main programming language used for development.
- **Scikit-Learn:** Library for machine learning algorithms.
- **Pandas:** Tool for data manipulation and analysis.
- **NumPy:** Library for scientific computing with arrays.
- **Matplotlib:** Visualization library for creating static, animated, and interactive visualizations.

## Main Features
- **Data Cleaning:** Comprehensive cleaning of the main, paid, and address datasets to ensure data quality.
- **Data Analysis and Visualization:** Exploration and visualization of the data to uncover patterns and insights.
- **Feature Engineering:** Creation of new columns from existing data to enhance the model's predictive power.
- **Model Development:** Selection, training, and evaluation of various classification algorithms to determine the most effective model.

## Conclusion and Future Work
After analyzing the data, clients were classified into two categories: those who pay on time in more than 85% of the months and those who do not. This classification was based on the ratio between the number of months the client paid on time and the total number of months.

A model was created to predict the classification of clients based on the `ratio_on_time` column. The model achieved an accuracy of 0.99, indicating a high degree of accuracy in predicting client classifications.

However, it is recommended to adjust the recall to increase sensitivity towards the 0 value, ensuring that clients who are likely to make their payments are correctly identified.

### Future Improvements:
1. **Enhance Model Sensitivity:** Fine-tune the model to improve recall for better identification of clients who make their payments.
2. **Feature Expansion:** Explore additional features that might improve model performance.
3. **Model Robustness:** Test the model with more diverse datasets to ensure robustness.
4. **Automated Pipelines:** Develop automated pipelines for data processing and model training to streamline the workflow.

