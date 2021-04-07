# Capstone_Project_Home_credit_dafault_risk


Home Credit Default Risk

Overview :

There are lots of people who do not particularly have a prior credit history, for example students, small businessmen, etc. who need credits, be it for studies, or for setting up some sort of businesses. Without adequate credit history, the lending organizations find it difficult to lend credits to such people, as these loans could be associated with high risks. In these kinds of situations, some lending organizations even tend to exploit the borrowers by asking for too high of an interest rate.
There are another subset of people, who do have prior credit history, which could be with the same organization or some other organizations. However, going through that historical data could be very time consuming and redundant. This would scale up even further as the number of applicants increases.
For such cases, if there could be a way through which the lending organization could predict or estimate the borrower’s repayment capability, the process could be streamlined and be made effective for both the lender and the borrower. It could save resources both in terms of humans and time.
So the main two questions that the lender needs answer to are:
1) How risky is the borrower?
2) Given the borrower’s risk, should we give him/her loan?



Business Objective: Home Credit Default Risk
Home Credit strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. In order to make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data--including telco and transactional information--to predict their clients' repayment abilities.
 
Home depot wants to have a model that clients capable of repayment are not rejected and that loans are given with a principal, maturity, and repayment calendar that will empower their clients to be successful.



Data:

application_{train|test}.csv<br>
This is the main table, broken into two files for Train (with TARGET) and Test (without TARGET).<br>
Static data for all applications. One row represents one loan in our data sample.<br>
bureau.csv<br>
All client's previous credits provided by other financial institutions that were reported to Credit Bureau (for clients who have a loan in our sample).<br>
For every loan in our sample, there are as many rows as number of credits the client had in Credit Bureau before the application date.<br>
bureau_balance.csv<br>
Monthly balances of previous credits in Credit Bureau.<br>
This table has one row for each month of history of every previous credit reported to Credit Bureau – i.e the table has (#loans in sample * # of relative previous credits * # of months where we have some history observable for the previous credits) rows.<br>
POS_CASH_balance.csv<br>
Monthly balance snapshots of previous POS (point of sales) and cash loans that the applicant had with Home Credit.<br>
This table has one row for each month of history of every previous credit in Home Credit (consumer credit and cash loans) related to loans in our sample – i.e. the table has (#loans in sample * # of relative previous credits * # of months in which we have some history observable for the previous credits) rows.<br>
credit_card_balance.csv<br>
Monthly balance snapshots of previous credit cards that the applicant has with Home Credit.<br>
This table has one row for each month of history of every previous credit in Home Credit (consumer credit and cash loans) related to loans in our sample – i.e. the table has (#loans in sample * # of relative previous credit cards * # of months where we have some history observable for the previous credit card) rows.<br>
previous_application.csv<br>
All previous applications for Home Credit loans of clients who have loans in our sample.<br>
There is one row for each previous application related to loans in our data sample.<br>
installments_payments.csv<br>
Repayment history for the previously disbursed credits in Home Credit related to the loans in our sample.<br>
There is a) one row for every payment that was made plus b) one row each for missed payment.<br>
One row is equivalent to one payment of one installment OR one installment corresponding to one payment of one previous Home Credit credit related to loans in our sample.<br>
HomeCredit_columns_description.csv<br>
This file contains descriptions for the columns in the various data files.<br>




WorkFlow:<br>
Collecting data and applying data wrangling<br>
Exploring the data and do some data analysis to find trends and story telling<br>
Find the relationship between different variables<br>
Implement Machine Learning algorithms<br>
Model evaluation and validation<br>

Deliverables:<br>

Jupyter notebook (.ipynb code)<br>
Final report<br>
Slide deck<br>
Presentation <br>
