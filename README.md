# Lending Club Case Study
> A consumer finance company specializing in lending various types of loans to urban customers wants to analyze the risk of approving loan application based on past data

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The aim is to :
    Understand the driving factors (or driver variables) behind loan default
    Identify patterns which indicate if a person is likely to default, for taking actions such as –
    Denying the loan
    Reducing the amount of loan
    Lending (to risky applicants) at a higher interest rate

- Loan Dataset:
    Loan status can be of the following two types:
    - Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
        Fully paid – Paid back loan amount in full.
        Current – Loan account is still active. Considered in analysis if >90% of term length has been paid.
        Charged-off – Defaulted. These two terms have been used interchangeably throughout analysis.
    - Loan rejected: The company had rejected the loan, these records are not considered for analysis


## Conclusions
- Most important parameters to be considered for analysing default risk
    Length of employment
    Annual income
    Debt to income ratio
    Employer reputation
    Requested loan amount
    Employment verification

- Exercise caution while approving loan application for customers with employment length less than five years
- Recommended approved loan amounts are given in the ppt
- In case requested funding amount is considerably more than the recommended levels, consider it to be a risk
- Rigorous verification of employment/source of income to be done for all loan applications
- Consider raising interest rate by 5% for mid and high income group customers seeking 36 months of term
- Employer reputation and job stability to be considered


## Technologies Used
- Python - version 3.0
- Pandas
- Numpy
- Seaborn

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@sanchita238] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->