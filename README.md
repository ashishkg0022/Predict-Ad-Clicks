# Predict-Ad-Clicks

### A Machine Learning challenge to predict the probability whether an ad will get clicked or not.

This repo contains solution of [this](https://www.hackerearth.com/practice/algorithms/string-algorithm/string-searching/practice-problems/machine-learning/predict-ad-clicks/description/) challenge.

Relevant datasets can be found at the [contest](https://www.hackerearth.com/practice/algorithms/string-algorithm/string-searching/practice-problems/machine-learning/predict-ad-clicks/description/) site.

### File Description

* xg_boost_final.ipynb  --> Final model which uses XGBoost to predict the probability of ad-clicks.

* other_algos.ipynb  --> Other models like Naive bayes, Decision trees and Random Forest.

* submission_xg.csv.zip  --> Output file after running the model on test.csv.

### Results

* xg_boost_final gives ***`AUC-ROC score of 0.806684`*** and ***`overall Accuracy of 0.98011`*** using validation set as 25% of training set.



