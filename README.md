# Task 2 – Credit Risk Prediction

## Objective
The goal of this task is to predict whether a loan applicant is likely to repay a loan, using the Loan Prediction Dataset. This task involves data cleaning, feature encoding, exploratory data analysis, model training using classification algorithms, and evaluating the results using accuracy and a confusion matrix.

## Approach
- Loaded the dataset and performed a detailed inspection of columns and missing values
- Handled missing data by:
  - Filling categorical values with the mode
  - Filling numerical values with the median or mode where appropriate
- Conducted exploratory data analysis (EDA), including:
  - Distribution of income and loan amounts
  - Box plots and scatter plots by loan status
  - Feature correlation and visual patterns
- Engineered additional features (e.g., Total Income)
- Encoded categorical features using Label Encoding and One-Hot Encoding
- Split the data into training and testing sets
- Trained and evaluated two classification models:
  - Logistic Regression
  - Decision Tree Classifier
- Compared model performance using:
  - Accuracy
  - Confusion matrix
  - Classification report

## Results and Insights
- Both models were successfully trained to classify applicants based on features like income, credit history, and property area
- Logistic Regression achieved an accuracy of **X%**
- Decision Tree achieved an accuracy of **Y%**
- The most influential features appeared to be:
  - Credit History
  - Total Income
  - Loan Amount
- Logistic Regression slightly outperformed the Decision Tree on generalization

---
This task demonstrated the complete classification pipeline, from raw data handling to model evaluation. It builds practical experience in preprocessing, modeling, and interpreting results in real-world financial datasets.
