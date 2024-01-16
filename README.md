# Project Name
Lending Club Case Study - Exploratory Data Analysis


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Lending Club is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
- If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
- Main objective is to identify driving factors behind loan default using EDA, which can be used by lending company for risk assessment when a loan application is received.
- Lending club loan data is given in CSV file. This file contains info only approved loans.


## Conclusions
- Conclusion 1 Borrowers who have chosen long term repayment like 60 months are more likely to default than for short term repayments as the interest rate is also high. Lending company should consider evaluating the risk associated with longer-term loans and potentially either limit the maximum term or adjust interest rates accordingly.
- Conclusion 2 Applicants who had been employed for more than 10 years accounted for the highest number of "Charged off" loans. However, when analyzed in terms of percentage distribution, we see that there is no huge variation in deafaulter% with the employment length. This indicates that long-term employment history does not necessarily guarantee successful loan repayment.
- Conclusion 3 We could see steady increase in the credit loss because of loan defaults from 2007 to 2010 but peaking very high in 2011. This could be indicative of economic or financial challenges during that year or defining the start of new trend.
- Conclusion 4 loans were predominantly taken during the last quarter, primarily in December. This peak in loan applications during the holiday season might suggest that financial pressures during the holidays contributed to loan defaults.
- Conclusion 5 Top 5 states with Maximum defaulters are : CA, NY, FL, TX and NJ. Company should monitor regional risk trends and adjust lending strategies or rates accordingly in these areas.
- Conclusion 6 'Small_business', 'medical' and 'debt consolidation' are the loan purpose categories where borrowers are defaulted the most. If the applicant is applying loan for one of these categories, lending company should scrutunize such applications as the probability of repayment is less.
- Conclusion 7 Higher the grade, we see high is the defaulter rate. Applicants with higher credit grade faced challenges in repaying their loans as the interest rate is high for higher grades. Lending company should reconsider on interest rate and have better evalution metrics on loan repayment for these high risk candidates.
- Conclusion 8 Majority of "Charged off" loan participants, lived in rented and mortgaged houses. Lending company must assess the financial stability of these applicants, as they may be more susceptible to economic fluctuations.
- Conclusion 9 Significant number of loan participants, around 15% were loan defaulters who were unable to clear their loans. The lending company should enhance risk assessment practices and  stricter credit checks. They can also offer financial education and support services to help borrowers manage their finances and improve loan repayment outcomes.
- Conclusion 10 Majority of the defaulters are with loan amount < 15k and with interest rate in the range 10 to 20%. The company should review its interest rate determination process and consider adjusting rates based on DTI ratios to better align with the borrower's ability to repay.
- Conclusion 11 For the applicants with public derogatory records, loan provided with higher amount is mostly resulted in defaults. The company can mitigate this risk by conducting more thorough assessments for these applicants and potentially capping loan amounts for higher-risk applicants.
- Conclusion 12 Majority of the loan applicants who charged off, reported an annual income between 30k to 60k and for loan amount <15k. The lending company should exercise caution when lending to low income individuals. They should implement rigorous income verification and assess repayment capacity more thoroughly for applicants in this income bracket.
- Conclusion 13 Among loan participants who charged off ,considerable portion belonged to the interest rate bucket of 15%-25%. To reduce the risk of default, the lending company can consider offering loans at lower interest rates when possible.
- Conclusion 14 The steady increase in the number of loan applicants from 2007 to 2011 indicates growth in the market. The company can capitalize on this trend by maintaining a competitive edge in the industry while keeping better risk management practices.
- Conclusion 15 Verified loan applicants are defaulting more than those who are not verified. The company should review its verification process to ensure it effectively assesses applicant creditworthiness and consider improvements or adjustments.
- Conclusion 16 Higher the revolving line utilization rate, higher the chance of defaulting. Lending company should consider revolving line utilization when approving loan and also recaliberate on interest rates.

## Technologies Used
- ipykernel - version 6.25.0
- ipython - version 8.15.0
- isort - version 5.9.3
- jupyter - version 1.0.0
- matplotlib - version 3.7.2
- seaborn - version 0.12.2


## Contact
Created by [@rajani2024] - feel free to contact me!