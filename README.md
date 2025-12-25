# customer-churn-prediction
Machine learning based customer churn prediction using Decision Tree, Random Forest, and XGBoost models, with performance evaluation and comparative analysis to support customer retention strategies.

## Project Overview
Customer churn prediction is a critical task for businesses to identify customers who are likely to stop using a service. This project applies machine learning techniques to predict customer churn based on historical customer data.
The goal is to help organizations improve customer retention strategies and reduce revenue loss.

## Objectives
- To analyze customer behavior using historical data
- To build machine learning models for churn prediction
- To compare model performance using standard evaluation metrics

## Machine Learning Models Used
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier


## Dataset Description
The dataset contains customer-related information such as:
- Demographic details
- Account information
- Service usage patterns
- Churn status (Target Variable)

**Target Variable:**  
`Churn` (Yes / No)

## Methodology
1. Data Cleaning and Preprocessing
2. Feature Encoding and Scaling
3. Train-Test Split
4. Model Training
5. Model Evaluation
6. Performance Comparison


## Model Performance

| Model          | Accuracy | Precision | Recall | F1-Score |
|----------------|----------|-----------|--------|----------|
| Decision Tree  | 0.78     | 0.77      | 0.76   | 0.76     |
| Random Forest  | 0.84     | 0.83      | 0.82   | 0.82     |
| XGBoost        | 0.83     | 0.82      | 0.81   | 0.81     |

## Technologies Used
- Python
- Google Colab
- Scikit-learn
- XGBoost
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Results & Conclusion
Random Forest achieved the highest accuracy and overall performance, making it the most suitable model for this dataset. The project demonstrates how machine learning can effectively assist in predicting customer churn.

## Future Work
Hyperparameter tuning
Deep learning models
Real-time churn prediction
Deployment using Flask or Streamlit
