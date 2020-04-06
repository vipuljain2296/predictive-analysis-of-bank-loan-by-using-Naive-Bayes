# predictive-analysis-of-bank-loan-by-using-Naive-Bayes

Here I have  demonstrated a loan credibility prediction system which helps
organisations in taking right decision to reject or approve the bank loan request of
customers. This will surely aid the banking industry to open very efficient delivery
channels. I have used Naive bayes algorithm in addition to k- means clustering for
prediction. The Incorporation of some other techniques that can outperform the
performance of the most popular data mining need to be tested and implemented for
the domain.

# Algorithm
First of all I took customer details having unique id and each customer’s information is shown in a row.

## Steps:
1.	Input: Statistics of the customers : age, marital status, sex, race, occupation
                Finance of customers : credit score, income Debts
                Loan Type : (loan type)

2.	Data processing is done in this step	
    It consists of two steps:
##    (a)Data cleansing
##     (b)Data preparation
##    In data cleansing step missing values are checked.
3.	In next step debt income ratio is being calculated, in which
##   DTI > 36 will not be accepted for loan.
4.	In this step customer’s request for loan is being selected for approval or denial, in which 
##  Approved=1
##  Denied=0
5.Partitioning the data:  The data is now divided into two sets :
##  Training data Set & Testing data 
##  Set in ratio [70:30] 
6.	In this step Naive Bayes classifier is being applied 
##   Error, Accuracy and Confusion has been calculated.
      
7.	And at last a chart has been built in which
##   (green point=1) shows loan has been accepted and
##   (red points =0) shows loan has been denied.

