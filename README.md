# Supervised Machine Learning Classification – Bank Term Deposit Prediction

This project focuses on classifying whether a client will subscribe to a **term deposit** based on historical marketing data from a Portuguese bank. The dataset contains both **categorical and numerical features**, derived from phone-based marketing campaigns.

---

## Dataset Overview

- **Source**: [UCI Machine Learning Repository – Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- **Filename**: `bank-additional-full.csv`
- **Target Variable**: `y` (binary: `'yes'` or `'no'`)
- **Type**: Classification (Binary)

---

## Technologies Used

- **Python**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Visualizations
- **Scikit-learn** – Baseline models, evaluation
- **XGBoost**, **LightGBM** – Advanced classifiers

  
 --- 

## Objectives

- Develop multiple **classification models** to accurately predict term deposit subscription.
- Evaluate performance using accuracy, RMSE, and interpretability.
- Compare model performance to determine the best algorithm for deployment.

---

## Exploratory Data Analysis (EDA) & Preprocessing

- Checked for **missing values**, **duplicates**, and **outliers**
- Addressed **skewed distributions** and **scaled numerical features**
- **Encoded categorical variables**
- Engineered a **new feature** to enhance model learning

---

## Models Trained

| Model                    | Performance Summary                                                                 |
|--------------------------|--------------------------------------------------------------------------------------|
| Logistic Regression      | Moderate scores; simple and interpretable, captures basic linear relationships      |
| Ridge Classifier         | Improved generalization; mitigates multicollinearity through L2 regularization      |
| Decision Tree            | Strong performance; good at modeling complex relationships but prone to overfitting |
| XGBoost Classifier       | High accuracy and low RMSE; robust ensemble method                                  |
| LightGBM Classifier      | ⭐ **Best model**; high performance and efficient on large data                      |

---

## Final Model Recommendation

** LightGBM Classifier**

- Achieved the **highest test score** and **lowest RMSE**
- Effectively handles:
  - Categorical data
  - Class imbalance
  - Complex feature interactions
- Highly efficient and scalable

---

## Key Insights

- **LightGBM** outperforms other classifiers with excellent generalization.
- **XGBoost** and **Decision Trees** are solid alternatives with good accuracy.
- **Ridge Classifier** enhances logistic regression’s stability without overfitting.
- Feature scaling and encoding played a key role in improving model reliability.



