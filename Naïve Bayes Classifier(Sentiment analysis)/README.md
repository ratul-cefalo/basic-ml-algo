# Naïve Bayes Classifier #

## Description: ##

You are given a sentiment dataset in **sentiments.tsv** file.

### Data Format: ### 
* sentence \t score \n.

Score is either **1 (for positive) or 0 (for negative).**

### You are required to ###

* Split dataset into train and test set.
* Create vocabulary on training dataset.
* Calculate prior probability for each class.
* Calculate Conditional Probabilities for all vocabulary given all classes based on training dataset
* For all test instance, calculate posterior probability for each class and select the predicted class with the maximum posterior probability.
