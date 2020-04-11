Problem:-

Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers.

This is a classification problem where we have to predict whether a loan will be approved or not. Specifically, it is a binary classification problem where we have to predict either one of the two classes given i.e. approved (Y) or not approved (N). Another way to frame the problem is to predict whether the loan will likely to default or not, if it is likely to default, then the loan would not be approved, and vice versa. The dependent variable or target variable is the Loan_Status, while the rest are independent variable or features. We need to develop a model using the features to predict the target variable.

Data:-

The training set will be used for training the model, i.e. our model will learn from this data. It contains all the independent variables and the target variable. The test set contains all the independent variables, but not the target variable. We will apply the model to predict the target variable for the test data. There are 13 columns of features and 614 rows of records in the training set and 12 columns of features and 367 rows of records in the test set. The dataset variables are summarized as below:

1	Loan_ID	- Numerical - Discrete -	Unique Loan ID

2	Gender -	Categorical - Nominal -	Male / Female

3	Married -	Categorical - Nominal -	Applicant married (Y/N)

4	Dependents -	Categorical - Ordinal -	Number of dependents (0, 1, 2, 3+)

5	Education -	Categorical - Nominal -	Applicant Education (Graduate / Under Graduate)

6	Self_Employed -	Categorical - Nominal -	Self employed (Y/N)

7	ApplicantIncome -	Numerical - Continuous -	Applicant income

8	CoapplicantIncome -	Numerical - Continuous -	Coapplicant income

9	LoanAmount	Numerical -  Continuous -	Loan amount in thousands

10	Loan_Amount_Term -	Numerical - Discrete -	Term of loan in months

11	Credit_History -	Categorical - Nominal -	credit history meets guidelines (0, 1)

12	Property_Area -	Categorical - Ordinal -	Urban / Semi Urban / Rural

13	Loan_Status -	Categorical - Nominal -	Loan approved (Y/N)


