# Twitter-sentiment-analysis
This repositrory will show how to buld a sentiment analysis model to classify tweets as positive or negative using two different algorithms the Support Vector Machine (SVM) and Naive Bayes Classifier.

# Libraries used:
The following python libraries were used in this project

* re
* pickle
* numpy
* pandas
* seaborn
* WordCloud
* matplotlib
* nltk
* LinearSVC
* BernoulliNB
* LogisticRegression
* RandomForestClassifier
* KNeighborsClassifier
* train_test_split
* TfidfVectorizer
* confusion_matrix
* classification_report


# Project Motivation:
Sentiment analysis is a valuable tool for understanding public opinion on various topics. It can be used in business to improve products and customer satisfaction, in politics to gauge public opinion on candidates and policies, in finance to analyze market sentiment, and in social media to understand trends. Overall, sentiment analysis provides valuable insights that can inform decision-making in many fields.
In this project, the aim is to design and implement supervised machine learning models to help Sentiment Analysis with Tweets (is it positive or negative?).

# File Description:
* Twitter_Sentiment_Analysis.ipynb:Notebook containing the data analysis and builded model
* dataset2000tweets.csv:Dataset contains 2000 labeld tweets 


# Summary:
This machine learning model built by support vector machine (SVM) and Naive Bayes (BNB) to classify the sentiment of tweets. The dataset used in this model contained 2000 processed tweets with their corresponding sentiments.
The data was pre-processed to clean and remove stopwords, lowercase the text, and to balance the positive and negative sentiments. The data was then split into training and testing sets.
The TfidfVectorizer was used to convert the text into numerical features, which were then fed into the models. The performance of the models was evaluated using confusion matrix and classification report.
The results showed that SVM model was the most accurate among the two models with an accuracy of about 74%.

# Blog Link:
https://medium.com/@alyabisreem/twitter-sentiment-analysis-da59f92c8cf4

# Licensing, Authors and Acknowledgments:
* Data Source: Kaggle
* Acknowledgments: Copyright (C) 1989, 1991 Free Software Foundation, Inc.  
51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA
