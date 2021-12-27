# Fake-News-Prediction
With the media world changing drastically and the news being circulated at a faster pace day by day,
one has to make certain the news the audience receives is real. 
This project uses Logistic Regression to differentiate between the real and fake news and uses 
Python's sklearn library (Tfidfvectorizer) to convert the textual data to numerical data, 
calculating Term Frequency and Inverse Document Frequency. 
Used Stemming - Removed the prefix and sufix of non-stopwords to obtain the root words for cleaning.
Preprocessed and cleaned the dataset by filtering out the stopwords using the Natural Language Toolkit.
Split the data into train and test data with 80:20 ratio and checked the accuracy of the built model
