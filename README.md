# Spam-Classification
Spam Detection Classification Model

Instead of choosing a model for this problem I have gone ahead and implemented 9 models(some same models but with
different hyperparameters).

A KFold of 10 has been chosen. Even this can be increased but doing so doesn't give a significant increase to the 
accuracy and only increases the run time.

A table with the False Positive and False Negatives and accuracy for each iteration in the Kfold of a Classifier
is generated by the code. There are 9 such tables, one for each Classifier.

At the end the Classifier which gives the maximum accuracy is specified along with its accuracy.
