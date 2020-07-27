# Universal-Review-Sentiment-Classifier
Scrapped Amazon, Yelp, Twitter and IMDB to create a review repository to create a review Sentiment Analyzer.
Created a Repository of 70,000+ reviews for training set. 

## Overview
In the project we used a Voting classifier to integrate the result of RandomForest , Multinomial and Logistic Regression to optimize out predictive output. We were able to achieve an accuracy of 82% using this technique 

The program reads a text file with one review per line. We removed the stopwords and used TF-IDF to vectorize text to input it into our model . 
