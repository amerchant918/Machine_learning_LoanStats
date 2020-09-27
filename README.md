# Machine_learning_LoanStats

## Credit Risk Ensemble

To begin the credit risk ensemble we split the data into test and train sets.
In order to eliminate the bias in the dataset we used the Random Over Sampler class for consistency that resulted in an accuracy score of 0.732 with precision of high-risk loan of 0.03 and a recall rate of .57. Versus the Easy Ensemble AdaBoostClassifier with an accuracy rate of 0.70 and precision rate of 0.71 and recall rate of 0.40. Of the two models I recommend using the Ensemble Classifier as it has a relatively similarly accuracy rate with a higher precision rate and lower recall rate meaning there will be lower false positives. 

## Credit Risk Resampling
After oversampling the data using the RandomOverSampler and SMOTE algorithm. The Naive Random Oversampling technique resulted in an accuracy score of 0.634 with a precision rate of 0.01 and recall rate of 0.59 for high risk loans. Versus the SMOTE Oversampling model that resulted in an accuracy score of 0.647 and precision rate of 0.01 with recall rate of 0.67. The results are similar whereas the Combination of Over and Under sampling model resulted in an accuracy score of 0.519 and a precision rate of 0.01 and recall rate of 0.69. Of the three main methods since the precision rate is same across the board the two variables to focus on is the accuracy and recall rate. The SMOTE would be the preferred method as it has a lower recall rate and a relatively high accuracy rate. 
