# Covid19 top-tweets exploration
The aim of this project is to explore and analyze data related to the 2019-2020 coronavirus pandemic. We have collected all of the twitter's daily top-tweets, related with coronavirus most common hashtags (313591 tweets) until the last week of April. We analyze the most commonly used words and hashtags per week and we implement a sentiment analysis to approximate the percentage of optimistic and pessimistic tweets per week

### Data Collection
For the purpose of this project, we collected all of the daily tweets that twitter has marked as “top-tweets” from the first week of 2020 (30/12/2019- 05/01/2020), until the last week of April (27/04/2020-03/05/2020). Twitter, defines “top tweets”, as the most relevant tweets to a search, based on the popularity of a tweet (e.g., when a lot of people are interacting with or sharing via Retweets and replies), the keywords it contains, and other factors. The data were collected on May 10th, so that tweets made at the end of April, would still have some time to be considered as “top-tweets”, from Twitter’s algorithm.

![collected-tweets](https://anjelo.ml/github-images/covid19-top-tweets-exploration/collected-tweets.png)

### Repository files
- **top-tweets-data directory:** it contains all the tweets and hashtags collected, in csv files per week.
- **2way-classifier:** sci-kit learn classifier object to classify new tweets as positive or negative.
- **3way-classifier:** sci-kit learn classifier object to classify new tweets as positive, negative or neutral.
- **covid19-tweets-exploration.ipynb:** Jupyter notebook containing the code used (python 3).
- **project-report:** PDF file, describing the whole project and it's conclusions.

### Python Dependences
numpy, Pandas, collections, time, ftfy, re, GetOldTweets3, datetime, wordcloud, matplotlib, seaborn, nltk, joblib, sklearn.
