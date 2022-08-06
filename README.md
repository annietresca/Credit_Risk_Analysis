# Credit_Risk_Analysis

## Overview
Credit risk is a very useful tool lending companies lean on to assess what customers to lend to. This project looks to evaluate the performance of various machine learning models in predicting credit risk utilizing credit card data from LendingClub, a peer-to-peer lending services company.


## Resources

Software: Python 3.7.9, Jupyter Notebook 6.0.3, Logistic Regression, Random Forest models

Data: LoanStats_2019.csv

## Results
The following images show the results for each of the six machine learning algorithms looked at:


- Random Oversampling: ![NativeRandom](https://github.com/annietresca/Credit_Risk_Analysis/blob/main/Images/Naive%20Random%20Oversampling.png)
In this ML algorithm, the balanced accuracy score is 65%.
The precision for high risk applicants was around 1% with 70% sensitivity.
The precision for low risk applicants was at nearly 100% with a sensitivity of 61%.




- SMOTE: ![SMOTE](https://github.com/annietresca/Credit_Risk_Analysis/blob/main/Images/SMOTE%20Oversampling.png)
In this ML algorithm, the balanced accuracy score is 66%.
The precision for high risk applicants was around 1% with 63% sensitivity.
The precision for low risk applicants was at nearly 100% with a sensitivity of 69%.




- ClusterCentroids: ![ClusterCentroids](https://github.com/annietresca/Credit_Risk_Analysis/blob/main/Images/ClusterCentroids.png)
In this ML algorithm, the balanced accuracy score is 52%.
The precision for high risk applicants was around 1% with 69% sensitivity.
The precision for low risk applicants was at nearly 100% with a sensitivity of 40%.





- SMOTEENN: ![SMOTEENN](https://github.com/annietresca/Credit_Risk_Analysis/blob/main/Images/SMOTEENN.png)
In this ML algorithm, the balanced accuracy score is 64%.
The precision for high risk applicants was around 1% with 70% sensitivity.
The precision for low risk applicants was at nearly 100% with a sensitivity of 58%.




- Balanced Random Forest Classifier: ![BRFC](https://github.com/annietresca/Credit_Risk_Analysis/blob/main/Images/Balanced%20Random%20Forest%20Classifier.png)
In this ML algorithm, the balanced accuracy score is 78%.
The precision for high risk applicants was around 4% with 67% sensitivity.
The precision for low risk applicants was at nearly 100% with a sensitivity of 91%.




- Easy Ensemble AdaBoost Classifier: ![AdaBoost](https://github.com/annietresca/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble%20AdaBoost%20Classifier.png)
In this ML algorithm, the balanced accuracy score is 93%.
The precision for high risk applicants was around 7% with 91% sensitivity.
The precision for low risk applicants was at nearly 100% with a sensitivity of 94%.





## Summary
Based on these findings, its safe to say that most of the algorithms looked at show weak precision as it relates to determining high credit risk (varying between 1%-7%). On the other hand, all of these algorithms were nearly 100% with predicting low risk applicants. Out of the models looked at, the Easy Ensemble AdaBoost Classifier had the most precision when assessing high risk credit applicants with 7% precision. When it comes to sensitivity, the Easy Ensemble AdaBoost Classifier was also on top with 91% sensitivity for high risk credit applicants. Additionally, the Easy Ensemble AdaBoost Classifier had the highest balanced accuracy score on the models looked at, coming in at 93%. In layman's terms, out of all the customers marked as high risk, 7% were actually predicted correctly as being high risk from the Easy Ensemble AdaBoost Classifier and 91% of the time all high credit risk individuals were marked as such. None of these models are perfect however it would be recommended to use this model based on its accuracy, precision and sensitivity.
