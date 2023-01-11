# Bank-Deposit-Classification

## Problem Statement
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

## Dataset
Dataset taken from Bank Marketing Data Set from UCI Machine Learning Repository.  [Link](https://archive.ics.uci.edu/ml/datasets/bank+marketing)

## Conclusion
Without Hyperparameter Tuning:-
- The best recall score of 0.466 is given by Random Forest Classifier with an f1-score of 0.540
- The best accuracy score of 91.06% is given by Random Forest Classifier
- The models does not perform well on the test set in terms of recall. The accuracy on the other hand is significant.
<br>

With Hyperparameter Tuning:-<br>
* The best recall score of 0.891 is given by Logistic Regression with a balanced F1-score of 0.542
* The best accuracy score of 91.10% is given by Random Forest Classifier
* The models perform better in terms of recall and have maintained the F1-score and overall accuracy.
<br>
<img width="401" alt="result" src="https://user-images.githubusercontent.com/106606656/211789187-c30cc337-fa01-4788-83fd-2a627155b154.png">


## Verdict
* Logisitic Regression model with hyperparameter tuning is able to give a balanced F1-score of 0.542 and a decent accuracy of 83.10%. This model outperforms all the other models in terms of reducing the FN cases and increase the Recall to 0.891.
* The Logisitic Regression model is tuned with a threshold value of 0.1.
* We can choose a threshold value of 0.3 for a generalised model with a better F1-score that reduces both FN and FP.<br><br>
Hence this model can be used in practice and is a good model.
