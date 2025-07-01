# EnsembleLearning
Ensemble Learning: Bagging, Boosting and Stacking


# Exercise Description

In this exercise first, I use the IRIS Dataset to implement three different basic algorithms using Bagging, Boosting and Stacking.


*   First, I implemented Bagging for Decision Tree as the base estimator.
*   Second, I used Boosting (AdaBoost) for Decision Tree as the base estimator.
*   Finally, I used Stacking with Decision Tree and Logistic Regression as base estimators and SVM as the meta learner.

The second part of this exercise is a comparison between the results obtained using Staking technique over the Wine Dataset. The comparison is made by different metrics and also applying cross validation as we see in previous lectures.
The learners are:

*   **Learner 1:** Random Forest, Decision Tree and SVC as learners and Logistic Regression as meta learner.
*   **Learner 2:** Random Forest, Gradient Boosting and SVC with kernel RBF as learners and a Neural Network as meta learner.
