# Natural Language Processing for Disaster Tweets, Course Project
This repository is created for the Temple University CIS 5526 course project. 

In this project, I use NLP to classify tweets as disaster or non-disaster tweets. The goal is to determine as accurately as possible whether a tweet announces a real disaster like an earthquake and fire, or is a regular tweet that does not constitute an emergency. The dataset is from Kaggle’s “Natural Language Processing with Disaster Tweets” competition. It contains 7613 labeled training data and 3263 unlabeled test data of tweets. I employed several machine learning algorithms to classify the tweets and compared the results. Before training the models, I performed EDA and text processing on the training data to get more information and get the data ready for ML algorithms. 

Inside the notebooks:  

[Project_EDA notebook](https://github.com/altineri/NLP_Project/blob/main/Project_EDA.ipynb): Exploratory data analysis has been performed here. 
[Project-Models](https://github.com/altineri/NLP_Project/blob/main/Project-Models.ipynb): Text processing steps performed and models (except BERT) built and trained here.
[Project-BERT](https://github.com/altineri/NLP_Project/blob/main/Project-BERT.ipynb): BERT model has been built and trained here.

References: 

1. «Natural Language Processing with Disaster Tweets,» [Online]. Available: https://www.kaggle.com/competitions/nlp-getting-started/overview. [Accessed: November 2023].
2. J. Portilla, "Python for Machine Learning & Data Science Masterclass," Pierian Training, [Online]. Available: https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/learn/lecture/22992400?start=1#learning-tools.
3. "Guide to NLTK – Natural Language Toolkit for Python," Pierian Training, [Online]. Available: https://pieriantraining.com/guide-to-nltk-natural-language-toolkit-for-python/. [Accessed November 2023].
4. B. Bengfort, "Text Classification with NLTK and Scikit-Learn," [Online]. Available: https://bbengfort.github.io/2016/05/text-classification-nltk-sckit-learn/. [Accessed November 2023].
5. "Creating Visuals with NLTK’s FreqDist," [Online]. Available: https://dariuslfuller.medium.com/creating-visuals-with-nltks-freqdist-ac4e667e49f3. [Accessed November 2023].
6. D. Valeti, "Classification using Word2vec," [Online]. Available: https://medium.com/@dilip.voleti/classification-using-word2vec-b1d79d375381. [Accessed November 2023].
7. N. V. Otten, "Word2Vec for text classification," [Online]. Available: https://spotintelligence.com/2023/02/15/word2vec-for-text-classification/#Word2Vec_for_text_classification_example. [Accessed December 2023].
8. «word2vect,» [Online]. Available: https://www.tensorflow.org/text/tutorials/word2vec#vectorize_an_example_sentence. [Accessed: December 2023].
9. S. Vucetic, CIS 5526 Homework 6, Parts 3 & 4, 2023. 




