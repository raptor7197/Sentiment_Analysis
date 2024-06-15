# Sentiment_Analysis
**OVERVIEW**

The sentiment analysis is done with the help of Logistic regression

**PREQUISITES**

pandas: a python library

numpy :a python library 

sklearn :machine learning and data modeling library for Python


The code first filters out all the text using python regex except for fractions which are appended at the start of the review

Then it analyses the fraction and gives it a value of 0/1/2 according to the fraction 

The appends it into another file 
value count shows the number different sentiment .

We then split the dataset into test & train with 20 and 80 % respectively.

We train it using logistic regression and use matplotlib to visualise the data.

At last we chech the accuracy of the model.


PS: my first attempt at ML

edit : can be done better using NLP
