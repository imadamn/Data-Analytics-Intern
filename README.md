# Data-Analytics-Intern

# Machine Learning Mini Projects

This repository contains three tasks demonstrating basic data analysis, visualization, and machine learning techniques using Python.

---

## Task 1: Exploring and Visualizing the Iris Dataset

### Objective

Understand how to load, inspect, and visualize a dataset.

### Approach

* Loaded the dataset using pandas.
* Used `.shape`, `.columns`, and `.head()` for inspection.
* Created visualizations:

  * Scatter plots to examine relationships
  * Histograms to analyze distributions
  * Box plots to detect outliers

### Results and Insights

* Petal features clearly separate species.
* Most variables show near-normal distribution.
* Some outliers are present in sepal measurements.

---

## Task 2: Credit Risk Prediction

### Objective

Predict whether a loan applicant is likely to default.

### Approach

* Handled missing values using median (numerical) and mode (categorical).
* Performed basic EDA on income, loan amount, and education.
* Encoded categorical variables.
* Trained Logistic Regression and Decision Tree models.
* Evaluated using accuracy and confusion matrix.

### Results and Insights

* Income and loan amount strongly influence predictions.
* Education has moderate impact.
* Model performance is affected by class imbalance.

---

## Task 3: Customer Churn Prediction

### Objective

Identify customers likely to leave the bank.

### Approach

* Cleaned data and removed irrelevant columns.
* Encoded categorical variables:

  * Gender using label encoding
  * Geography using one-hot encoding
* Trained Logistic Regression and Random Forest models.
* Analyzed feature importance.

### Results and Insights

* Age and balance are key factors in churn.
* Active customers are less likely to leave.
* Geographic differences affect churn rates.
* Random Forest performed better overall.

---

## Conclusion

These tasks demonstrate core skills in data preprocessing, visualization, classification, and interpretation of results using Python-based tools.
