# lol22_ids20_jan24_project
Introductory sensitivity analysis ML project for Intro to DS Metis course

**Feb 7 Questions:**

_1) What is the question you hope to answer?_

Perform sensitivity analysis on airline twitter tweets to determine sentiment level that will allow us to answer the question: Given a particular tweet, is it positive, negative or neutral? How accurate is the prediction? Can we further improve the accuracy by the use of different features, different models, tuning hyperparameters?

_2) What data are you planning to use to answer that question?_

Twitter US Airline Sentiment
Analyze how travelers in February 2015 expressed their feelings on Twitter
https://www.kaggle.com/crowdflower/twitter-airline-sentiment

_3) What do you know about the data you're using so far?_

I am familiar with Twitter and structure of tweets in general, but this is the first time I've seen the dataset. It is pretty self explanatory with main feature being the tweet ('text' in this instance) and 'airline_sentiment' (positive, negative, or neutral) the label.

_4) Why did you choose this topic?_

NLP is very widely used in the world today and analyzing text is something I find interesting.

**Feb 14 Questions:**

_1) What data have you gathered, and how did you gather it?_

Data was gathered from Kaggle.

_2) How have you explored the data and what insights have you gained as a result?_

EDA was performed using Pandas and Seaborn. A lot of insight was gathered from the results; mainly, the imbalanced data set, the main positive/negative words, and the ability to use different libraries like NLTK, Wordcloud, etc. to further analyze the tweets.

_3) Will you be able to answer your question with this data, or do you need to gather more data (or adjust your question)?_

Yes, the question will be fully answered.

_4) What modeling approach are you using to answer your question?_

The plan will be to use Logistic Regression as that performs well in supervised classification problems and provides easy to interpret results. We can easily compare this to another model such as Naive Bayes which also does well with basic NLP problems.

