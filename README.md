# L-T-Finance
For L and T finance AV hackathon

## About LTFS Data Science FinHack ( ML Hackathon):<br>
L&T Financial Services & Analytics Vidhya presents **‘DataScience FinHack’.**
Amazing opportunity for all creative nerds to apply their data science & machine learning skillset to best solve a real business problem.
In this FinHack, you will develop a model for our most common but real challenge **‘Loan Default Prediction’ & also, get a feel of our business!**<br>
**If your solution adds good value to our organization, take it from us, Sky is the limit for you!**
<br>
<br>
## About L&T Financial Services (LTFS):<br>
Headquartered in Mumbai, LTFS is one of India’s most respected & leading NBFCs providing finance for two wheeler, farm equipment, housing, infra & microfinance. With a strong parentage & stable leadership, it also has a flourishing Mutual Fund & Wealth Advisory business under its broad umbrella.
<br><br>
![](images/av_img.png)
<br><br>
Our Advanced Analytics team,
Solves only ‘Real’ Business Problems through Data
Enables business decisioning across all verticals
Harnesses external data (incl. mobile, social media, bureau, socio economic etc)
Utilises non-conventional and innovative data science approaches
**LTFS was featured in "Forbes Super 50 Companies“(August 2018)**
To know more about LTFS, please visit: www.ltfs.com.

## Problem Statement<br>
## Vehicle Loan Default Prediction<br>
Financial institutions incur significant losses due to the default of vehicle loans. This has led to the tightening up of vehicle loan underwriting and increased vehicle loan rejection rates. The need for a better credit risk scoring model is also raised by these institutions. This warrants a study to estimate the determinants of vehicle loan default.
A financial institution has hired you to accurately predict the probability of loanee/borrower defaulting on a vehicle loan in the first EMI (Equated Monthly Instalments) on the due date. Following Information regarding the loan and loanee are provided in the datasets:<br>

  * **Loanee Information** (Demographic data like age, income, Identity proof etc.)
  * **Loan Information** (Disbursal details, amount, EMI, loan to value ratio etc.)
  * **Bureau data & history** (Bureau score, number of active accounts, the status of other loans, credit history etc.)<br>
  
Doing so will ensure that clients capable of repayment are not rejected and important determinants can be identified which can be further used for minimising the default rates.<br>
 

## Data Description<br>
### train.zip<br>
train.zip contains train.csv and data_dictionary.csv.<br>
  * **train.csv** contains the training data with details on loan as described in the last section
  * **data_dictionary.csv** contains a brief description on each variable provided in the training and test set.<br>

### test.csv<br>
test.csv contains details of all customers and loans for which the participants are to submit probability of default.
 

### sample_submission.csv<br>
sample_submission.csv contains the submission format for the predictions against the test set. A single csv needs to be submitted as a solution.
 

## Evaluation Metric<br>
Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.
 

## Public and Private Split<br>
Test data is further randomly divided into Public (25%) and Private (75%) data.
Your initial responses will be checked and scored on the Public data.
The final rankings would be based on your private score which will be published once the competition is over.
