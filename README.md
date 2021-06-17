# Sentiment-Analysis-on-IMDB-dataset
Data Loading and Data preparation:
This dataset comes from research work by D. Kotzias, M. Denil, N. De Freitas, and P. Smyth described in the KDD 2015 paper 'From Group to Individual Labels using Deep Features'. We are grateful to these authors for making the dataset available. Data set is in CSV file format, with 2400 input, output pairs in the training set, and 600 inputs in the test set.
Training set of 2400 examples
• x_train.csv : input data
o Column 1: 'website_name' : one of ['imdb', 'amazon', 'yelp']
o Column 2: 'text' : string sentence which represents the raw review
• y_train.csv: binary labels to predict
o Column 1: 'is_positive_sentiment' : 1 = positive sentiment, 0 = negative
Test set of 600 examples
• x_test.csv : input data

Using this data, I've combined x_train and y_train files and converted the data into text format and used for the importing because it makes easy to compute and also to analyse. However, both the excel values are input pairs.

There are many ways to approach the feature representation out of which I’ve performed three majorly used classifiers, thery are:
- Multinomial Naive Bayes classifier
- CountVectorizer feature extraction from text classifier
- Term Frequency - Inverse Document Frequency classifier

