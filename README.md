# customer-churn-prediction
Machine learning project predicting customer churn using Random Forest

This project develops a machine learning model to predict customer churn for a telecom company using Random Forests. Early identification of churners helps businesses increase customer retention and reduce revenue loss.

## Business Problem

Customer churn is costly for subscription-based businesses. It’s more expensive to acquire new customers than to retain existing ones. This project aims to predict which customers are likely to churn to enable proactive retention strategies.

## Dataset

The dataset contains 1,000 telecom customers with 19 features including demographic info, service details, and billing. The target variable is `Churn` indicating whether a customer left (Yes) or stayed (No).

## Methodology

- Data cleaning & preprocessing (handling missing values, encoding, scaling)
- Exploratory Data Analysis (EDA) and visualization
- Model building with Random Forest
- Hyperparameter tuning using GridSearchCV
- Model evaluation with classification metrics and ROC AUC
- Feature importance analysis and business insights

## Key Findings

- Month-to-month contracts and low tenure significantly increase churn risk
- Higher monthly charges correlate with more churn
- Fiber optic internet customers show higher churn rates

**Business recommendations:**

- Promote long-term contracts
- Target retention efforts on newer customers
- Review pricing and services for fiber optic customers

## Model Performance Visualizations

**Confusion Matrix:**

![Confusion Matrix](images/confusion_matrix.png)

**Feature Importance:**

![Feature Importance](images/feature_importance.png)

**ROC Curve:**

![ROC Curve](images/roc_curve.png)

## Model Evaluation Metrics

| Metric    | Score  |
|-----------|---------|
| ROC AUC   | 0.XXX   |
| Accuracy  | XX.X%   |
| Precision | XX.X%   |
| Recall    | XX.X%   |
| F1-Score  | XX.X%   |

## Technologies Used

- Python 3.12
- pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Future Improvements

- Deploy model as a web app
- Use advanced algorithms (XGBoost, LightGBM)
- Add model explainability (SHAP)
- Build interactive dashboards (Streamlit)

