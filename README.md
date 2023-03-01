
# **Discrimination Detector**

![alt text](https://images.everydayhealth.com/images/young-people-experience-frequent-discrimination-behavioral-mental-problems-1440x810.jpg?w=1110)


## Dataset
- Twitter Webscraping with Snscrape (https://github.com/JustAnotherArchivist/snscrape)
- 105.210 discriminatory tweets
- 100.000 control group (without specific discriminatory word, random tweets)

## Problem 
Discrimination is one of the most important problems in the internet. Solutions generally does not include discrimination towards health and mental health.
Studies showed that;
_"Young adults ages 18 to 28 years old who have experienced frequent discrimination have a higher risk of short-term and long-term behavioral and mental health problems, according to a new UCLA study."_

### Aim:
Discrimination Detection uses natural language processing (NLP) to analyse text from social media and provide feedback to users on the level of discrimination in their text, along with suggestions for how to rewrite it.

### Analysis:
- Discrimination level detection & suggestions
- Number of likes and retweets between tweets that are neutral, positive and discriminatory
- Analysis of most liked and retweeted tweets

## Roadmap
1. Scrap a diverse dataset of discriminatory language from Twitter covering gender, race, ethnicity, sexual orientation, mental health, and health related keywords.
2. Clean the data by removing unnecessary words, urls, emoji and characters.
3. Extract key features from text to train ML models, using approaches bag of words, TF-IDF.
4. Train ML models on extracted features to classify given text by discrimination level and give suggestion based on that level.
5. Evaluate the performance of the model using various metrics such as accuracy, precision, recall, and F1-score. 
6. Use cross-validation techniques to ensure the model does not overfit the training data.
7. Develop an user interface that allows users to input text and receive feedback on the level of discrimination in their writing, along with suggestions.
8. Present the project.

Future Step 1 - Gather feedback from users and apply it to enhance the machine learning model and user interface over time. 
Future Step 2 - Regularly update the model with new data and capabilities to ensure it stays current with the latest trends and language used on social media.


