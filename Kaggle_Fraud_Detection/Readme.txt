Outline of this code:
* undersample non fraud dataset and make a balanced dataset as 1:1 to train the model
* use precision, recall, f1 and kappa to choose the best parameter c for regularization
* try different ratio of data to get more accurate and stable results
* using SMOTE to generate synthetic data points, accuracy is 0.944 and recall is 0.914 by logistic regression
* try to use random forest and orignal 1:1 ratio data set
* try to combine random forest and data after SMOTE
* eventually achieve recall rate is 1 and accuracy is 0.999871035061 and AUC is 0.99987081469