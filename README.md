# Quora-Question-Pair-Similarity
The objective of the analysis was for two given questions, to determine whether the questions are duplicate of each 
other or not. It was a binary classification problem, Used Calibrated Classifier on top of Logistic Regression to
predict the classification of the pair of questions. Applied advanced feature engineering to create features which
would help in determining the similarity between the questions such as common word count, common token count, 
common stop word count, fuzz ratio, fuzz_token sort_ratio etc using packages like numpy, pandas and fuzzywuzzy.
Performed data optimization tasks such as data mining, data cleaning, text preprocessing and exploratory data analysis
which consisted of creating a random model with a metric of log loss to determine the worst log loss of the given 
data after feature engineering.Finally applied Logistic Regression on the complete data to check how good the model
classified the data points correctly by comparing log loss, confusion, precision, recall matrices and the misclassified
points with the random model.
