# Credit Risk Analysis by Ben Altshuler

## Overview 

Using a credit card credit data set from our stakeholders at LendingClub, we used SKLearn to train and evaluate several ML models in order to reduce bias and predict credit risk. 

## Results

- Random Oversampling resulted in a balanced accuracy score of .62

- SMOTE Oversampling resulted in a slightly higher BAS of .66

- Undersampling resulted in a BAS of .51

- SMOTEENN Combination sampling resulted in a BAS of .62

- Random Forest Classification resulted in a BAS of .79

- The Easy Ensemble classifier resulted in an accuracy score of .93

# Summary

This dataset saw oversampling, underspampling, and combination campling algorithms perform similarly. Given the inherently unbalanced nature of credit risk analysis, it appears that the ensemble classifiers greatly outperformed our initial models. 

Of the six algorithms tested in this example, the Easy Ensemble AdaBoost Classifier performs best. It was able to correctly identify risky loans 93 percent of the time on this particular set. For now, this algorithm gets our recommendation. 