# Natural Language Processing Homework

## Background

There's been a lot of hype in the news lately about cryptocurrency, so you want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.
In this assignment, you will apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. You will also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

Complete the following tasks:

Sentiment Analysis

Natural Language Processing

Named Entity Recognition

## Instructions

### Sentiment Analysis

Use the newsapi to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.
Use descriptive statistics to answer the following questions:

Which coin had the highest mean positive score?
Which coin had the highest negative score?
Which coin had the highest positive score?

### Natural Language Processing

In this section, you will use NLTK and Python to tokenize the text for each coin. 

Next, look at the ngrams and word frequency for each coin.

List the top 10 words for each coin.

Finally, generate word clouds for each coin to summarize the news for each coin.

## Results

#### Which coin had the highest mean positive score?

Looking at the descriptive statistics generated from the sentiment analysis with vader, Ethereum had a higher mean positive score of 0.0667 as opposed to Bitcoin with a mean positive value of 0.063368.

#### Which coin had the highest negative score?

Bitcoin had the highest negative score 0.1 of a news article,  for ethereum the article with the max negative score had a value of 0.09. For all articles the mean negative values were 0.014789 for bitcoin and 0.020250 for ethereum.

#### Which coin had the highest positive score?

Ethereum had the highest positive score 0.173000 of a news article,  for ethereum the article with the max positive score had a value of 0.143000.

