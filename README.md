# Loan Eligibility Prediction

## Project Overview
This project predicts whether a loan will be approved or not based on applicant details using **Python** and **Machine Learning**. The goal is to help banks and financial institutions automate the loan approval process by analyzing applicant data.

---

## Dataset
The dataset contains information about loan applicants, including:
- `Gender`
- `Married`
- `Dependents`
- `Education`
- `Self_Employed`
- `ApplicantIncome`
- `CoapplicantIncome`
- `LoanAmount`
- `Loan_Amount_Term`
- `Credit_History`
- `Property_Area`
- `Loan_Status` (Target)

**Source:** [Provide Dataset Source or Mention if Custom Dataset]

---

## Tools & Technologies
- Python 3.x
- Jupyter Notebook
- Libraries:
  - pandas
  - numpy
  - matplotlib / seaborn
  - scikit-learn

---

## Project Steps

1. **Data Loading & Exploration**
   - Loaded the dataset using Pandas
   - Explored features, data types, missing values, and basic statistics

2. **Data Cleaning & Preprocessing**
   - Handled missing values
   - Converted categorical variables using encoding
   - Feature scaling (if applied)

3. **Exploratory Data Analysis (EDA)**
   - Visualized data distributions
   - Analyzed relationships between features and target variable
   - Identified patterns for prediction

4. **Model Building**
   - Trained multiple models including:
     - Logistic Regression
     - Decision Tree
     - Random Forest
   - Split data into training and testing sets
   - Evaluated model performance using accuracy, confusion matrix, and other metrics

5. **Model Evaluation**
   - Compared models and selected the best performing model
   - Achieved **[Add Accuracy]% accuracy** on test data
   - Identified key features affecting loan approval

6. **Prediction**
   - Created a function to predict loan eligibility for new applicants

---
