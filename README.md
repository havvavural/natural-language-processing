# Unit 12—Tales from the Crypto

![Stock Sentiment](Images/sentimental.jpeg)

## Background

There's been a lot of hype in the news lately about cryptocurrency, so you want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.

I applied natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. I also applied fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.


### Instructions

#### Sentiment Analysis

I used the [newsapi](https://newsapi.org/) to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.


#### Natural Language Processing

In this section, I use NLTK and Python to tokenize the text for each coin. 

Next, I looked at the ngrams and word frequency for each coin.

1. I used NLTK to produce the ngrams for N = 2.
2. I listed the top 10 words for each coin.

Finally, I generated word clouds for each coin to summarize the news for each coin.

![btc-word-cloud.png](Images/btc_word_cloud.png)

![eth-word-cloud.png](Images/eth_word_cloud.png)

#### Named Entity Recognition

In this section, I built a named entity recognition model for both coins and visualize the tags using SpaCy.

![btc-ner.png](Images/btc_ner.png)

![eth-ner.png](Images/eth_ner.png)

---
