Churn Prediction ML Project

 Project Overview
This project predicts customer churn using machine learning techniques.
Churn refers to customers leaving a service, and predicting it helps companies take proactive actions to retain them.

Objective:
* Identify customers likely to churn.
* Provide actionable insights for retention strategies.

 Features

Data preprocessing (handling missing values, encoding categorical variables, scaling)
Feature engineering
Model training and evaluation (Logistic Regression)
Performance metrics: Accuracy, Precision, Recall, F1-score

Dataset :
Target variable: Churn ( 0 = No, 1 = Yes)

Model Performance :

| Metric    | Class 0 | Class 1 | Overall |
| --------- | ------- | ------- | ------- |
| Precision | 0.85    | 0.68    | —       |
| Recall    | 0.90    | 0.56    | —       |
| F1-score  | 0.88    | 0.61    | —       |
| Accuracy  | —       | —       | 0.81    |


Installation & Usage

1. Clone the repository:
  git clone https://github.com/002SIDDHARTH/Churn_Prediction_ML_Project.git
cd Churn_Prediction_ML_Project

2. Install dependencies using requirements.txt:
  pip install -r requirements.txt

3. Open the notebook locally:
  jupyter notebook Churn.ipynb

Tools & Libraries

Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn

Future Improvements

Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
Experiment with advanced models (XGBoost, LightGBM)
Deploy as a web app using Streamlit
Automated model evaluation pipeline


