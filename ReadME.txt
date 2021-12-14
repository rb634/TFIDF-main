Write a Python program that learns a TFIDF model from spam_train.csv. Use 
the model to get TFIDF vectors for spam_test.csv. 

Your program will then learn an SVM model (LinearSVC in sklearn) on the 
TFIDF of spam_train.csv and predict spam or ham for spam_test.csv.

Your model should achieve at least 95% accuracy to get full points.

Your program takes in two files spam_train.csv and spam_test.csv and 
outputs the predicted labels as well as their accuracy on the spam_test.csv 
file.
