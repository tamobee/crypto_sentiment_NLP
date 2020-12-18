# Crypto Sentiment

## Background

In order to make an overall assessment of the latest news articles featuring Bitcoin and Ethereum, I applied fundamental natural language processing (NLP) techniques, including named-entity recognition (NER) to understand some of the factors involved with the crypto prices.

This process is broken down into three tasks:

1. [Sentiment Analysis](#Sentiment-Analysis)
2. [Natural Language Processing](#Natural-Language-Processing)
3. [Named Entity Recognition](#Named-Entity-Recognition)

---

#### Files

[Jupyter Notebook](Code/crypto_sentiment.ipynb)

---

### Sentiment Analysis

* Used the [newsapi](https://newsapi.org/) to pull the latest news articles for Bitcoin and Ethereum.

#### Q&A

Q: Which coin had the highest mean positive score?

A: **BTC had the highest mean positive score.**

Q: Which coin had the highest compound score?

A: **ETH had the highest negative score.**

Q. Which coin had the highest positive score?

A: **ETH had the highest positive score.**

### Natural Language Processing

* Tokenized the text for each coin using NLTK and Python.
* Used NLTK to produce the ngrams for N = 2.
* Generated word clouds for each coin to summarize the news for each coin.

### Named Entity Recognition

* Built a named entity recognition model for both coins and visualized the tags using SpaCy.
