# Sentiment Analysis of Health Tweets

*2020 is a hard year for everyone, thus health became the most common concern in our lives. In this project I analyzed the tweets about health and try to know what type of health people are talking most. Then I did sentiment analysis, and found out that the propotion of positive tweets are most, the propotion of negative tweets are a little less, the propotion of nuetral tweets are least.*

## 1. Data Collection

[Data Collection Notbook](https://github.com/yuhan0623/Springboard/blob/master/Capstone%20project-3%20Health_Care/1-Tweets%20collection.ipynb)

The tweets data was scraped by using tweepy based on health keywords from Twitter API.

## 2. Data Wangling 

[Data Wangling Notbook](https://github.com/yuhan0623/Springboard/blob/master/Capstone%20project-3%20Health_Care/2_Data_wrangling.ipynb)

Regular data cleaning
* NA data
* Duplicates
* Change the type of some columns

Text data cleaning
* Make text all lower case
* Remove URLs
* Remove punctuation
* Remove common non-sensical text (\n)
* Remove stopwords 

## 3. EDA

[EDA Notebook](https://github.com/yuhan0623/Springboard/blob/master/Capstone%20project-3%20Health_Care/3-Exploratory-Data-Analysis.ipynb)

Here are some main findings from EDA.
* Vocabulary from all tweets without unmeaning frequent words. 
![](./figures/wordcloud_all_tweets_without_unmeaning.png)
* Health words frequency in all tweets.
![](./figures/bar_keywords_frequency.png)


## 4. Sentiment Analysis

[Sentiment Analysis Notebook](https://github.com/yuhan0623/Springboard/blob/master/Capstone%20project-3%20Health_Care/4_Sentiment%20Analysis-Copy1.ipynb) 

* Sentiment count.
![](./figures/bar_sentiment_count.png)
* Health words frequency in each sentiment category.
![](./figures/bar_keywords_frequency_sentiment.png)
