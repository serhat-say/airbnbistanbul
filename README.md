# airbnbistanbul
Airbnb Istanbul dataset - opinion and ratings analysis

By looking at the ratings and comments which are belong to properties in Istanbul, exploring the opinions, ratings and relationship between them.

---

Data can be obtained by these links: 

http://data.insideairbnb.com/turkey/marmara/istanbul/2021-02-26/data/reviews.csv.gz

http://data.insideairbnb.com/turkey/marmara/istanbul/2021-02-26/data/listings.csv.gz

---

pandas used for dataset manipulation

matplotlib used for visualization

re used for identify regular expressions for preprocessing the text data

wordcloud is used for word visualization

from nltk.sentiment.vader SentimentIntensityAnalyzer used for analyzing sentiments

---

We always look at the comments on online processes like shopping, booking etc. Also, we look at the ratings all the time. However, are the comments always related and are the opinions always consistent with the ratings? For answering these questions, I constructed a three part project. In first part, opinions are mined. In second part, the ratings are examined and analyzed. Finally, the third part, opinions and ratings are compared for obtaining the relationship between them. In the end, it is seen that the opinions and ratings are positively correlated in high ratings. However, at lower points, there seems to be no correlation. 

---

README: readme file for project

Notebook: notebook file for analyze the data and run the sentiment analysis model
