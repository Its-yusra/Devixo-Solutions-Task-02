# Customer Churn Prediction Using Machine Learning

## Project Overview
This project focuses on predicting customer churn using machine learning classification algorithms. The IBM Telco Customer Churn dataset is used to identify customers who are likely to leave a telecommunications service.

The project was completed as **Task 02 – Build and Compare Machine Learning Models** for Devixo Solutions.

## Dataset
- **Source:** [IBM Telco Customer Churn – Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Total Records:** 7,043
- **Original Columns:** 21
- **Target Variable:** Churn
- **Problem Type:** Binary Classification

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Data Preprocessing
- Dataset inspection
- Missing value handling
- Duplicate checking
- Removal of unnecessary customer ID column
- Target variable encoding
- Categorical feature encoding using OneHotEncoder
- Numerical feature scaling using StandardScaler
- Train-test split (80:20)

## Machine Learning Models
Three classification algorithms were implemented:
1. Logistic Regression
2. Decision Tree
3. Random Forest

## Model Evaluation
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### Initial Model Results

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 80.55% | 65.72% | 55.88% | 60.40% |
| Decision Tree | 72.11% | 47.55% | 49.20% | 48.36% |
| Random Forest | 78.64% | 62.54% | 48.66% | 54.74% |

## Hyperparameter Tuning
GridSearchCV with 3-fold cross-validation was used to optimize model hyperparameters using F1 Score.

### Tuned Model Results

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 74.17% | 50.87% | 78.61% | 61.76% |
| Decision Tree | 72.11% | 48.34% | 73.80% | 58.41% |
| Random Forest | 76.22% | 53.96% | 71.12% | 61.36% |

## Best Performing Model
Tuned Logistic Regression was selected as the best-performing model based on its highest test F1 Score of **61.76%** and recall of **78.61%**.

## Project Files
- `Devixo_Task_02_Machine_Learning_Model_Comparison.ipynb` – Complete Jupyter Notebook.
- `Devixo_Task_02_Report.pdf` – Project report.
- `Screenshots/` – Screenshots of preprocessing, model training, evaluation, and tuning results.

## Conclusion
This project demonstrates the application of machine learning techniques for customer churn prediction. It covers data preprocessing, model training, evaluation, comparison, and hyperparameter tuning.

**Submitted by:** Yusra Komal
