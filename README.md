# Loan-Prediction
Train and Test Datasets can be found on Analytics Vidhya: https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/#ProblemStatement

In the notebook, I tried modelling with different classification models such as Random Forest Classifier, Logistic Regression, Decision Tree Classifier, Support Vector Machine, in order to see which one gave a higher accuracy. Even though Random Forest is known to be an unexcelled choice in terms of its capabilities to examine a large number of decision trees, it didn't seem to produce a good result compared to other models in my notebook(maybe I misused it in some way because I wasn't really familiar with its use). With the other models, I tried to combine the use of StratifiesKFold and GridSearchCV, and some other parameter tuning methods.

# Data Dictionary:

Train file: CSV containing the customers for whom loan eligibility is known as 'Loan_Status'

Variable	Description
Loan_ID:	Unique Loan ID
Gender:	Male/ Female
Married:	Applicant married (Y/N)
Dependents:	Number of dependents
Education:	Applicant Education (Graduate/ Under Graduate)
Self_Employed:	Self employed (Y/N)
ApplicantIncome:	Applicant income
CoapplicantIncome:	Coapplicant income
LoanAmount:	Loan amount in thousands
Loan_Amount_Term:	Term of loan in months
Credit_History:	credit history meets guidelines
Property_Area:	Urban/ Semi Urban/ Rural
Loan_Status(Target): Loan approved (Y/N)


Test file: CSV containing the customer information for whom loan eligibility is to be predicted

Variable	Description
Loan_ID:	Unique Loan ID
Gender:	Male/ Female
Married:	Applicant married (Y/N)
Dependents:	Number of dependents
Education:	Applicant Education (Graduate/ Under Graduate)
Self_Employed:	Self employed (Y/N)
ApplicantIncome:	Applicant income
CoapplicantIncome:	Coapplicant income
LoanAmount:	Loan amount in thousands
Loan_Amount_Term:	Term of loan in months
Credit_History:	credit history meets guidelines
Property_Area:	Urban/ Semi Urban/ Rural

# Problem Statement:

Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers. 



