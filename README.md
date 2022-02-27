# NLP
## Unit 12 - Tales from the Crypto 

For this assignment, I applied natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. 

## 1 - Sentiment Analysis

For this part, I used News Api to get current articles regarding Ethereum and Bitcoin. I then used VADER polarity scores for sentiment analysis on these articles to see how 'negative' or 'positive' the articles were. This allowed me to answer the following questions:

Q: Which coin had the highest mean positive score?

A: Bitcoin has a mean score of 0.090800, and Eth has a mean score of 0.059100. Thus Bitcoin has a higher mean positive score

Q: Which coin had the highest compound score?

A: Ethereum had a slighty higher compound score with a score of 0.834100

Q. Which coin had the highest positive score?

A: Ethereum had a slightly higher positive score with a score of 0.234000

Overall, I would say they both have mostly neutral articles. Both Bitcoin and Ethereum had more postive articles compared to negative articles, where Bitcoin was more positive. 

## 2 - Natural Language Processing

For this part, I used NLTK and Python to tokenize text, find n-gram counts, and create word clouds for both Bitcoin and Ethereum. I was able to determine the most common words used in the articles for both coins.

For Bitcoin: 10 most common words were 'Bitcoin','Reuters','El','cryptocurrency','Salvador,'dollar','Illustration','Alex','Castro' and 'Verge'.

For Ethereum: 10 most common words were 'newsletter','cryptocurrency','million','Bitcoin','Ethereum','token','ethereum','Feb','Reuters', and '324'.


Here are the word clouds I created for each coin:
![Bitcoin Wordcloud](bitcoin_cloud.png)
![Ethereum Wordcloud](ethereum_cloud.png)

## 3 - Named Entity Recognition

Lastly, for this part I built a named entity recognition model for both coins and visualized the tags using SpaCy.
