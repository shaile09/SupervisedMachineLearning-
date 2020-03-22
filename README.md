# SupervisedMachineLearning-

In this challenge, we used different techniques to train and evaluate models to assess credit risk, using data from LendingClub; a peer-to-peer lending services company. We used the imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. We used Naïve Random Sampling, SMOTE Oversampling , UnderSampling, and Combination.

In the table below, the precision shows us how many people are out of the total positive are true positive. The Precision is the measure of how reliable a positive classification is. From our results, the precision for the good loan applications can be determined by the ratio TP/(TP + FP), which the average is 0.99. The higher the precision score the better the model.  

Recall is the ability of the classifier to find all the positive samples. This tell us out of the positives, how many members are true positives by using this formula TP/(TP + FN). F1 score is a weighted average of the true positive rate (recall) and precision, where the best score is 1.0 and the worst is 0.0. The higher the score the better the model. Support is the number of actual occurrences of the class in the specified dataset. For our dataset, there are 17205 occurrences.

![](/Challenge.PNG)

From this analysis, we can see that oversampling is the best model to use due to the highest recall average. I think this is the best model to use.  
