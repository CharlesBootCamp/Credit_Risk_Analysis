# Credit_Risk_Analysis

## Overview: 

LendingClub has lent us some credit data for us to examine and determine which ones are good loans or bad loans, as making bad loans can ultimately result in lost money and a potential loss of work. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans, meaning that multiple methods would be very preferable to determine which ones are good and which ones are not. In the end, 6 different methods will be used to determine which ones are good versus bad loans.

## Results: 

- Naive Random Oversampling results: Our balanced accuracy test it 65.1% and on average, the precision is 99% and the recall is 68%
![image](https://github.com/CharlesBootCamp/Credit_Risk_Analysis/blob/main/Resources/Naive.png)

- SMOTE oversampling results: Our balanced accuracy score is 62.4% and on average, the precision is 99% and the recall is 66%
![image](https://github.com/CharlesBootCamp/Credit_Risk_Analysis/blob/main/Resources/SMOTE.png)

- Undersampling results: Our balanced accuracy score is 51.6% and on average, the precision is 99% and the recall is 44%
![image](https://github.com/CharlesBootCamp/Credit_Risk_Analysis/blob/main/Resources/Undersampling.png)

- Combination(over and undersampling) results: Our balanced accuracy score is 62.1% and on average, the precision is 99% and the recall is 53%
![image](https://github.com/CharlesBootCamp/Credit_Risk_Analysis/blob/main/Resources/Combination.png)

- Balanced Random Forest Classifier results: Our balanced accuracy score is 78.7% and on average, the precision is 99% and the recall is 91%
![image](https://github.com/CharlesBootCamp/Credit_Risk_Analysis/blob/main/Resources/Balanced.png)

- Easy Ensemble AdaBoost Classifier results: Our balanced accuracy score is 92.5% and on average, the precision is 99% and the recall is 94%
![image](https://github.com/CharlesBootCamp/Credit_Risk_Analysis/blob/main/Resources/Easy%20Ensemble.png)

## Summary: 

In the first four models, a combination of undersampling and oversampling was done and found the average recalls to be between 40% and 70%. The next two models however, relied on using classifiers and were found to have recall percentages that were at least 90%. The first 4 also have lower accuracy scores than the other 2, going from around 50% to 66%, while the classifiers had around 79% and 93% accuracy. The Easy Ensemble AdaBoost Classifier has the best stats of all 6, being greater than 90% in all categories.
