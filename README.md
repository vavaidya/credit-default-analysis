# credit-fraud-analysis
![Image of Credit Default](https://github.com/vavaidya/credit-default-analysis/blob/master/credit_default.jpg)
## INTRODUCTION
The Taiwanese economy experienced tremendous growth during the 1990’s, almost doubling in value along with the other countries known as the Asian Tigers. The country’s financial sector was heavily involved in the growth of real estate during this period. However, in the early 2000’s, this growth slowed and banks in Taiwan turned towards consumer lending to continue the expansion. As a result, credit requirements were loosened and consumers were encouraged to spend by borrowing capital

## PROBLEM TO SOLVE
I will be analyzing data on Taiwanese credit card holders from mid-2005, as the flood of debt was reaching its peak. The task at hand is to be able to predict if an individual will miss their next credit card payment (predictor variable).

## APPROACH
The following classification algorithms were trained and compared for results -

* Naive Bayes
* Logistic Regression
* KNN
* Decision Tree
* Random Forest
* XG Boost

The banking data is skewed with only 22.1% defaulters which could potentially lead to biased predictions. SMOTE was used in the attempt to bump up numbers for defaulters and to better predict future tendencies.

Based on business intuition models were compared on their recall based on their Receiver Operating Characteristic Curve.

## REPOSITORY DETAILS
Access -
1. [Analysis Code](https://github.com/vavaidya/credit-fraud-analysis/blob/master/Credit_Default_Analysis.Rmd)
2. [Analysis .md File](https://github.com/vavaidya/credit-fraud-analysis/blob/master/Credit_Default_Analysis.pdf)
3. [Final Presentation - Summary of Approach and Results](https://github.com/vavaidya/credit-fraud-analysis/blob/master/Presentation%20-Credit_Default_Analysis.pdf)
