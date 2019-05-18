# Is Deep Learning Hype? Sentiment Analysis Comparing Deep Learning and Non-Deep Learning Methods

## Executive Summary

This analysis uses various Natural Language Processing (NLP) tools to analyze sentiment in Internet Movie Database (IMDB) reviews. First, the data is cleaned and preprocessed, followed by some Exploratory Data Analysis (EDA). Then, various techniques are used to compare deep learning and non-deep learning methods. The final production model is then tested by submitting the results to a Kaggle competition, producing an accuracy score of 85.7%. A final conclusion wraps up with lessons learned and plans for future analyses.

## Link to Technical Report



## Conclusion and Future Steps

While the final production model utilizing deep learning performed slightly worse than the non-deep learning methods, the difference was negligible (just over one percent). I believe the biggest reason for this is the scale of the data. 25,000 examples to train on is pretty small for a neural network. In the future, I would like to train Word2Vec and my LSTM model with a lot more text, as deep learning generally requires massive amounts of data to improve performance. Google's state-of-the-art results with similar techniques are based on a corpus of more than a billion words. I would also like to try some newer tools that have only recently been developed, such as Sent2Vec and Doc2Vec, which utilize paragraph embeddings and other advanced techniques to better learn context and the meaning of words.

Ultimately, is deep learning hype? Well, that depends on the scale of your data. If you are working with small datasets, traditional methods will likely be faster, and in some cases, more accurate (not to mention more interpretable). However, big data is the future, and the flexibility of neural networks makes them poised to be evermore important for data science as we generate more and more data.

