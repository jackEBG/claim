# Insurance
# Project Title:- Analyse Historical Insurance Claim Data

## Description
The objective of the analyses is to help optimise the marketing strategy as well as discover
“low-risk” targets for which the premium could be reduced, hence an opportunity to attract new clients.
Insurance Data Analysis Findings
The primary goal of this analysis was to explore relationships and patterns within the insurance dataset. 
Specifically, we aimed to understand how total premiums and claims vary across different dimensions, 
such as time and vehicle types, as well as geographical locations.

## Procedures
Data are obtained by using Python's Pandas library to load the dataset into a DataFrame. Inspection underway such as, 
data types, and summary statistics to get an understanding of the dataset's structure. Data cleaning & pre-processing 
also taken place, by handling missing values. Relevant numerical and categorical features were identified for analysis, 
including Total Premium, Total Claims, Vehicle Type, and Postal Code.
Exploratory Data Analysis (EDA):- utilize visualization libraries such as Matplotlib and Seaborn in Python for graphical 
exploration. Examine distributions, correlations, and patterns in the data, especially between features and the target variable total premium and total target
The  distribution  of  total  premiums  showed  a  right-skewed  pattern, indicating that while most premiums are relatively low, there are a few significantly high premiums.
This skewness suggests that a small number of policies contribute disproportionately to total premium revenue.
![image](https://github.com/user-attachments/assets/4c344d1e-9cae-40c3-b2a8-e5b1091638c1)

![image](https://github.com/user-attachments/assets/b701efc1-7d3e-48a7-a570-18f79e03c89a)

The above image shows a correlation matrix, which is a square matrix that displays the correlation coefficients between different variables. In this case, the variables are TotalPremium, TotalClaims, and CapitalOutstanding.

The key observations from the correlation matrix are:

TotalPremium has a strong positive correlation (1.0) with itself, as expected.
TotalClaims has a moderate positive correlation (0.12) with TotalPremium, suggesting there may be some relationship between the total premiums and total claims.
CapitalOutstanding has a weak positive correlation (0.0063) with TotalPremium, indicating a relatively low degree of linear relationship between the two variables.
TotalClaims has a strong positive correlation (1.0) with itself, again as expected.
CapitalOutstanding has a weak negative correlation (-0.001) with TotalClaims, suggesting there may be a small inverse relationship between the two variables.
CapitalOutstanding has a strong positive correlation (1.0) with itself, as expected.
Overall, the correlation matrix provides insights into the linear relationships between the three variables, which could be useful for further analysis or modeling.

![image](https://github.com/user-attachments/assets/7f901e4e-41d0-4ded-8d63-a79da054a7c6)
Explanation
•	Correlation and Trends: Both variables generally follow an upward trend but with different intensities and timings. The sharp rise and fall in Total Claims indicate periods of high activity or significant events affecting claims.
•	Business Implications:
o	The rise in Total Premiums could indicate successful sales or marketing strategies, policy renewals, or increased customer base.
o	The sharp rise and subsequent fall in Total Claims could be tied to specific incidents, regulatory changes, or seasonal effects.
Visual Interpretation:
•	Initial Steady Rise: From October 2013, there's a steady increase in both Total Premiums and Total Claims, reflecting a growing business or market conditions.
•	Claims Peak: The sharp peak around early 2015 in Total Claims suggests a period of high claims activity, which might need further investigation.
•	Premiums Peak: Around mid-2015, Total Premiums peak and stabilize, showing sustained revenue from premiums.


