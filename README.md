# -Loan-Prediction-Analysis
Predict borrowers chance of defaulting on loans by building a default prediction model.

# Model

    Logistic Regression Model
        Accuracy : 80.945%
        Cross-Validation Score : 80.946%

# Technologies:

    Programming Language: Python
    Libraries: Pandas, Scikit-learn, Matplotlib, Numpy

# Data Source:

    Datahack
    
# Problem Statement
## Business Problem

"Dream Housing Finance company deals in all home loans. They have presence across all urban, semi urban and rural areas. Customer first apply for home loan after that company validates the customer eligibility for loan. Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers."

Loan prediction is a very common real-life problem that every retail bank faces in their lending operations. If the loan approval process is automated, it can save a lot of man hours and improve the speed of service to the customers. The increase in customer satisfaction and savings in operational costs are significant. However, the benefits can only be reaped if the bank has a robust model to accurately predict which customer's loan it should approve and which to reject, in order to minimize the risk of loan default.

## Translate Business Problem into Data Science / Machine Learning problem

This is a classification problem where we have to predict whether a loan will be approved or not. Specifically, it is a binary classification problem where we have to predict either one of the two classes given i.e. approved (Y) or not approved (N). Another way to frame the problem is to predict whether the loan will likely to default or not, if it is likely to default, then the loan would not be approved, and vice versa. The dependent variable or target variable is the Loan_Status, while the rest are independent variable or features. We need to develop a model using the features to predict the target variable.

# Note: Do Check out project report pdf to find out how I used this algorithm.
