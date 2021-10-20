# ML_Hackathon_supernovas_Maintenance_prediction
Problem statement
BACKGROUND:
A company has a fleet of devices transmitting daily sensor readings. They would like to create a predictive maintenance solution to proactively identify when maintenance should be performed. This apparoach promises cost savings over routine or time-based preventive maintenance because tasks are performed only when warranted.

GOAL:
You are tasked with building a predictive model using Machine Learning to predict the probability of a device failure. When building this model, be sure to minimize false positives and false negatives. The column you are trying to predict is called failure with binary value 0 for non-failure and 1 for failure.

SOLUTION:
Here, we have tried building our own model by using cost sensitive ensembles in which BalancedBaggingClassifier performed exceptionally well so, we built a model combining  oversampling and undersampling using BalancedBaggingClassifier. In this way, we were able to achieve the goal with satisfactory precision, recall and F1-score.
