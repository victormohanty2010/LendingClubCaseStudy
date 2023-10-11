Project Name: Lending Club Case Study

This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. The objective is to be able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. 


Table of Contents
•	General Info
•	Technologies Used
•	Conclusions
•	Acknowledgements


Project Information
The project is a case study that uses the lending club data set to predict whether a loan will be defaulted or not.

Project Background

Lending loans to ‘risky’ applicants is the largest source of financial loss
(called credit loss). The credit loss is the amount of money lost by the lender 
when the borrower refuses to pay or runs away with the money owed.  
The main objective is to be able to identify these risky loan applicants, 
then such loans can be reduced thereby cutting down the amount of credit loss. 
Identification of such applicants using EDA is the aim of this case study.   
Perform an analysis to understand the driving factors (or driver variables)
behind loan default, i.e.the variables which are strong indicators of default.  
The company can utilise this knowledge for its portfolio and risk assessment. 

Project Statement

Find the major driving factors which leads to the defaulted loans which are source of loss for the company.

Data Set & Process Followed - 
The data set is a csv file with the loan data of the Lending Club.
1.	Data Understanding
2.	Data Cleaning/ Outlier Treatment including Datatype changes, outlier treatment based on boxplots, removing '%'s and character values from numerical columns, extracting year/month from data column, creating buckts of continuous variables, creating derived column for Perc Charged Off (Defaulter %)
3.	EDA - Univariate Analysis
4.	EDA- Bivariate/ Multivariate Analysis


Conclusions
•	From the detailed Univariate, Bivariate and Multivariate analysis above, below are the key indicators that drive high Default Rates (highlighted in bold):
1. About 74% of the Charged Off Loans are from 60 month tenure loans
2. Almost 50% of the Defaulters lie in loans taken under the purpose of debt consolidation
3. Small Business Loans, that had the 3rd highest contribution to loans has the highest Default perc at 27%
4. < 1 yr experience acc holders have highest Defaulter %
5. There is a steep increase in Defaulter % as the interest rate increases with ~29% for > 17% interest rate bucket
6. Low income buckets: there is a stark declining trend in Defaulter % as income buckets move higher (highest at 20% in the < 20k bucket)
7. There is a steep increase in Defaulter % at higher Grades (E, F, G) at 27%, 33% and 34% respectively
8. Public Recorded Bankruptcies > 1: While the # of loans for users with >= 1 bankruptcies is minimal, the default rates are as high as 40% for users with 2 records
9. There is high consolidation of Charged Off loans at low annual income and lower loan amount


Technologies Used

•	Pandas - version 1.3.4
•	NumPy - version 1.20.3
•	Seaborn - version 0.11.2
•	MatplotLib - version 3.4.3
•	Plotly - version 5.7.0

Acknowledgements
This project was inspired by UpGrad IITB EPGP Programme as a case study for the Machine Learning and Artificial Intelligence course.
