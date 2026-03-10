Customer Churn Prediction using Machine Learning

 Project Overview
Customer churn prediction is an important business problem where companies try to identify customers who are likely to leave their service.

In this project, a **Random Forest Classifier** is used to predict whether a bank customer will exit the bank based on demographic and financial attributes.

---

 Dataset
Dataset: Bank Customer Churn Prediction Dataset

Features include:
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Estimated Salary

Target variable:
- **Exited** (1 = Customer left the bank, 0 = Customer stayed)

---

 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

Machine Learning Model
Random Forest Classifier

Parameters:
- n_estimators = 110
- criterion = entropy

---

Model Evaluation

Accuracy: 87%

Classification Metrics:

| Class | Precision | Recall | F1-score |
|------|-----------|--------|---------|
| Stayed (0) | 0.88 | 0.97 | 0.92 |
| Exited (1) | 0.78 | 0.47 | 0.59 |

The model performs very well at identifying customers who stay with the bank. However, churn prediction recall is lower due to class imbalance.

---

Visualizations
The project includes several visualizations:

- Credit Score distribution
- Balance distribution
- Credit Score vs Salary scatter plot
- Age vs Churn analysis
- Confusion Matrix

---

Project Workflow
1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Model Training
6. Model Evaluation

---

Future Improvements
- Hyperparameter tuning



