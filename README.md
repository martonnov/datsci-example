# datsci-example

Small example of what and how I learned of data science in the last semester.

## Explanation

The following methods and algorithms were used on a dataset of costumers. We had to predict wether the person will be good or bad deptor.
* dummy classifier to make a baseline for future improvements
* confusion matrix for evaluation
* metrics, like
  * precision
  * recall
  * f1 score
* tried out a decision tree
  * feature importance from the dec tree
  * tried removing and adding specific features to the feature set based on the feature importance 
  * forward and backward selection/elimination
* KNN algorithm
  * transforming the values with log function so the value with higher density wont affect the model that much
  * standard scaler
  * parameter tuning on the difference of the # of neighbors and trying out different distance functions
* NB
  * binning the continous variables

## TL;DR

*Scoring and classification with KNN, NB, DT*
