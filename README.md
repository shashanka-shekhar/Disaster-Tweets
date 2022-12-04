# DisasterTweets

Competition Description(Kaggle) :


Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster.

In this competition, you’re challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. 

Dataset :

You’ll have access to a dataset of 10,000 tweets that were hand classified.

Shape - (7613 x 5)

Languages and libraries :

This project uses python3, sklearn, numpy, pandas, re, string, collections, rake_nltk in jupyter notebook(Anaconda Distribution).

Models and techniques used :
 
 1. MultinomialNB.
 2. CountVectorizer to get frequency of words in each tweet.
 3. TfidfVectorizer to get tf-idf score for each word in the tweet.
