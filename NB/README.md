### Project Overview

 This dataset comes from the UCI Machine Learning Repository. In total there are 422937 resources available in the dataset. The columns included in this dataset are:

1. ID: the numeric ID of the article
2. TITLE: the headline of the article
3. URL: the URL of the article
4. PUBLISHER: the publisher of the article
5. CATEGORY: the category of the news item; one of: b:business, t:science and technology, e: entertainment and m:health
6. STORY: alphanumeric ID of the news story that the article discusses
7. HOSTNAME: hostname where the article was posted
8. TIMESTAMP: approximate timestamp of the article's publication, given in Unix time (seconds since midnight on Jan 1, 1970)

Objective is to predict the 'CATEGORY' from 'TITLE' of the article.


### Approach taken to solve the problem

 1. Preprocessing the data - removal of non-alphabetic characters/expressions using re (regular expression)
2. Vectorization using bag-of-words and TF-IDF approaches
3. Predicting the category using Multinomial Naive Bayes' approach with accuracy score
4. Predicting the category using OneOverRestClassifier with Logistic Regression with accuracy score


