
# **Discrimination Detector**

![alt text](https://images.everydayhealth.com/images/young-people-experience-frequent-discrimination-behavioral-mental-problems-1440x810.jpg?w=1110)

## Problem 
Discrimination is one of the most important problems in social media. Solutions generally does not include discrimination towards health and mental health.
Studies showed that;
_"Young adults ages 18 to 28 years old who have experienced frequent discrimination have a higher risk of short-term and long-term behavioral and mental health problems, according to a new UCLA study."_ (https://www.everydayhealth.com/emotional-health/young-people-who-experience-frequent-discrimination-more-likely-to-have-behavioral-and-mental-problems/)

### Aim:
Discrimination Detection uses natural language processing (NLP) to analyse text from social media and provide feedback to users on the level of discrimination in their text, along with suggestions for how to rewrite it.

### Dataset
- Twitter Webscraping with Snscrape (https://github.com/JustAnotherArchivist/snscrape)
- 105.210 discriminatory tweets
- 100.000 control group (without specific discriminatory word, random tweets)

### Analysis:
1. Discrimination level detection & suggestions
2. Sentiment Analysis (negative - neutral - positive)
  2.1. Number of likes and retweets between tweets that are negative - neutral - positive
  2.2. Analysis of most liked and retweeted tweets

## Roadmap
1. Scrap a diverse dataset of discriminatory language from Twitter covering gender, race, ethnicity, sexual orientation, mental health, and health related keywords.
2. Clean the data by removing unnecessary words, urls, emoji and characters.
3. Extract key features from text to train ML models, using approaches bag of words, TF-IDF.
4. Sentiment Analysis with the dataset ( for both discriminatory and control groups)
5. Train ML models on extracted features to classify given text by discrimination level and give suggestion based on that level.
6. Evaluate the performance of the model using various metrics such as accuracy, precision, recall, and F1-score. 
7. Use cross-validation techniques to ensure the model does not overfit the training data.
8. Develop an user interface that allows users to input text and receive feedback on the level of discrimination in their writing, along with suggestions.
9. Present the project.

Future Step 1 - Gather feedback from users and apply it to enhance the machine learning model and user interface over time. 
Future Step 2 - Regularly update the model with new data and capabilities to ensure it stays current with the latest trends and language used on social media.


