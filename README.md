# Credit Risk Transition Modeling Using Markov Chains

## Project Overview
This project analyzes credit card clients' repayment behavior using a Markov Chain model. The dataset contains monthly records of customers' payment statuses, credit limits, bills, and demographic information. The main focus is on the repayment status variables (PAY_0 to PAY_6), which capture the client's delay in payment month-by-month.

## Dataset Description
* **ID**: ID of each client
* **LIMIT_BAL**: Amount of given credit in NT dollars
* **SEX**: Gender (1 = male; 2 = female)
* **EDUCATION**: Education level
* **MARRIAGE**: Marital status
* **AGE**: Age in years
* **PAY_0 - PAY_6**: Repayment status from September 2005 to April 2005
* **BILL_AMT1 - BILL_AMT6**: Amount of bill statement
* **PAY_AMT1 - PAY_AMT6**: Amount of previous payment
* **default payment next month**: Default payment (1=yes, 0=no)

## Project Structure
* Data Cleaning & Preprocessing
* Feature Engineering / Risk State Creation
* Markov Model (Transition Matrix)
* Predictions & Steady State Analysis

## Key Findings
* Most clients consistently pay on time or with minimal delay.
* A gradual increase in short and medium delays is observed over time.
* The transition matrix shows the probability of moving between risk states.

## Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Future Work
* Improve model accuracy by incorporating additional features.
* Explore other machine learning algorithms for comparison.
