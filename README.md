# **Discrimination Detector**

## Dataset
    - Twitter Webscraping with Snscrape (https://github.com/JustAnotherArchivist/snscrape)
    - 105.210 discriminatory tweets -> 104.029 after duplicates
    - Around 50.000 control group (without specific discriminatory word, random tweets)
    - 46.017 tweet from a dataset could also be added (https://www.kaggle.com/code/vinayak4444/cyberbullying-detection-using-nlp/data)

## Problem 
    - Discrimination is one of the most important problems in the internet.
    - Solutions generally does not include discrimination towards health and mental health.
    - Discrimination Detection uses natural language processing (NLP) to analyse text from social media and provide feedback to users on the level of discrimination in their text, along with suggestions for how to rewrite it.
        - Number of likes and retweets between tweets that are neutral, positive and discriminatory
        - analysis of most liked and retweeted tweets
        - discrimination level detection
        - non-discrimination suggestion
        - industries based
## Roadmap
    1. Scrap a diverse dataset of discriminatory language from Twitter covering gender, race, ethnicity, sexual orientation, mental health, and other sensitive topics.
    2. Clean the data by removing unnecessary words, punctuation, and characters.
    3. Extract key features from text to train ML models, using approaches like TF-IDF.
    4. Train ML models on extracted features to classify text by discrimination level.
    5. Evaluate the performance of the model using various metrics such as accuracy, precision, recall, and F1-score. Use cross-validation techniques to ensure the model does not overfit the training data.
    6. Develop an user interface that allows users to input text and receive feedback on the level of discrimination in their writing, along with suggestions.
    7. Present the project.
    8. Gather feedback from users and apply it to enhance the machine learning model and user interface over time. Regularly update the model with new data and capabilities to ensure it stays current with the latest trends and language used on social media.