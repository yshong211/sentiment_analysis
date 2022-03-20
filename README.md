# Sentiment Analysis for imdb movie review

Used dataset from http://ai.stanford.edu/~amaas/data/sentiment/ which is a IMDB Dataset of 50K Movie Reviews.

* Instead of using BERT or tf-idf for NLP, I used a expected rating of each words provided in the Dataset.
* calculated polarity metric with expected rating of each words times the frequency of the words in each review.
* able to get expected rating of each words from imdbEr.txt and get the frequency of the words in .feat file
* ran a Support Vector Machine 
