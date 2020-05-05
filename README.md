# Geospatial sentiment analysis using social media data


## ABSTRACT 
Sentiment analysis, also called opinion mining, is one of the most popular topics in the fields of natural language processing. It refers to a series of procedure dealing with the text data for extracting the sentiment polarity and emotional attitude behind the words. Here we have done the following work on the sentiment analysis using tweets: 
- First, users interact with frontend for typing keywords and adjust the map. 
- Next, Twitter APIs are called to fetch tweets with the geospatial information. 
- Then, tweets will be processed applying the TextBlob library to obtain the sentiment polarity, which is classified into three categories: positive, negative and neutral. 
- Finally, the results will be marked on a map for displaying, making visualized impression for users to easily understand high level emotional attitude. 


## Core Features
- sentiment analyser
The core function of our application, which is to search a single word on tweeter and capture related tweets, then conduct semantic analysis on those tweets. 

- Friendly 
We fetch the result of sentiment analysis to front-end, and calculate the attitude of each tweets, print those tweets and attitude wrappered in a browser-based application displaying on a map. 


## Requirements
- Google Map: The official map platform from google is foundation of our data visualization.
- Flask: It is a light python framework to build a simpler wrapper of our data communication. 
- Tweepy: A python library is recommended by Tweet to access to information from Tweet.
- TextBlob: It provides an effective procedure to implement textual sentiment analysis.

## Demo
![Demo](https://github.com/cao-weiwei/SESentimentAnaylsis/blob/master/imgs/01_demo.png)
