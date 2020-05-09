# Twitter-Sentiment-Analysis-
Sentiment analysis using nltk & scikit-learn(Naive Bayes, MultinomialNB, BernoulliNB, LogisticRegression, LinearSVC)

Requirements:
nltk,
scikit-learn,
matplotlib,
tweepy.


How to Run the code:

Step1:
First Create a pickled_algos folder in the same location where all your code is saved.

Step2:
Run the main.py file. It will train your module against the dataset and give you accuracy for all the classifiers used.

Step3:
Run the twitter.py file which will begin fetching the live stream of data from twitter api and generate a twitter-out.txt file which will contain the sentiment value of the stream of tweets fetched from the twitter api. (You need a twitter developers account for that https://developer.twitter.com/en/apps)

Step4:
Run the twittergraph.py for visualisation of your output.

Step5:
If you want to check the sentiment against random tweets, you can paste your tweet in the test.py file to check the sentiment.

