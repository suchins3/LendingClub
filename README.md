# Lending club case study
> Here we analyze and understand the driving factors behind loan default.The company does the risk assessment and based on the analysis decide on the loan disbursemtns.
> 
> In this process we explain dervied reccomendation also identifies  applicants who likely to repay the loan or not. 
In the step by step processes we show how we process data given, clean unnecessary data set, pre process and perform exploratory data analysis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contributers](#contributers)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This case study identify patterns  which identifies an applicant will repay their loan instalments which may be used for taking
further actions such as 
  - denying the loan
  - reducing the amount of loan
  - lending at a higher interest rate, etc.
- The company wants to understand the driving factors behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment
- Loan Data set used in this EDA contains loan data for all loans issued through the time period 2007 t0 2011.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
  - People with very high credit revolving balance (above 40k) have higher default rate of 18.17%. These should be avoided.
  - For high percent_cred_utlization over 98%, more than 25% customers have defaulted. So high percent credit use customers should be avoided.
  - People with credit lines above 30 seem to have high default rate of 25%. People with open credit lines more than 30 should be avoided.
  - People with public records seem to have high default rate of 22.5%. They can be avoided as loan applicants.
  - People with low loan_to_income ratio (<6) are safe people to give loan with 10% default rate.
  - People with high loan_to_income ratio (>30) are risky with 22% default rate.
  - Loans for small businesses, renewalble energy are of the highest risk with 27.7% people defaulting. 
  - Small business, education loans with high loan amnt to income ratio are very risky and should be avoided.
  - People default very less for credit card, car and wedding. If these people have low loan to annual income ratio, These seem to be very safe loans.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 
- numpy
- pandas
- seaborn
- matplotlib

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contributers
- Indrajeet Jadhav 
- Suchin chouta


