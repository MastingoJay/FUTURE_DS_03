# Loan Eligibility Prediction Analysis

# Summary

This project was completed as part of my internship at Future Interns, where I developed a Loan Eligibility Prediction model to determine whether loan applications would be approved or denied. The goal is to assist lending institutions in efficiently evaluating applicants.

# Dataset

The dataset utilized for this project contains the following columns:

Loan_ID: Unique identifier for each loan application

Gender: Gender of the applicant

Married: Marital status of the applicant

Dependents: Number of dependents of the applicant

Education: Education level of the applicant

Self_Employed: Employment status of the applicant

ApplicantIncome: Income of the applicant

CoapplicantIncome: Income of the coapplicant

LoanAmount: Amount of loan applied for

Loan_Amount_Term: Duration of the loan in months

Credit_History: Credit history of the applicant (1 = good, 0 = bad)

Property_Area: Area type of the property

Loan_Status: Loan approval status (1 = approved, 0 = not approved)

# Languages Used

Python

Jupyter Notebook

Pandas

Scikit-learn

Seaborn

Matplotlib

# Data Analysis

The project begins with exploratory data analysis (EDA) to understand the dataset's structure, identify missing values, and explore correlations between features. Key analyses include:

Investigating the relationship between Applicant Income and Education Level.

Assessing the impact of Credit History on loan approvals.

# Model Development

I implemented multiple machine learning models, including:

Decision Tree

Random Forest

Gaussian Naive Bayes (GNB)

Data preprocessing was performed to handle missing values and outliers. The models were evaluated based on their accuracy, with a focus on selecting the best-performing model.

# Key Insights

Model Performance: The Gaussian Naive Bayes model achieved the highest accuracy at 81.3%.

Income and Education: Graduates generally have higher incomes, indicating a positive correlation.

Credit History: A significant relationship was found between good credit history and higher loan approval rates.

# Results

The results demonstrate the effectiveness of machine learning in predicting loan eligibility, with the GNB model providing the most reliable predictions based on the analyzed features.

# Conclusion

This Loan Eligibility Prediction Analysis project highlights the potential of machine learning in improving the loan application process for financial institutions. Accurate predictions can streamline operations and enhance customer satisfaction.














