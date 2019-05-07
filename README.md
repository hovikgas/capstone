# Internet Movie Database Review Sentiment Analysis

## Problem Statement

Sentiment analysis is a challenging subject in machine learning. People express their emotions in language that is often obscured by sarcasm, ambiguity, and plays on words, all of which can be very misleading for both humans and computers alike. 

## Executive Summary

This analysis uses various Natural Language Processing (NLP) tools to analyze sentiment in Internet Movie Database (IMDB) reviews. Various techniques are used, comparing deep learning and non-deep learning methods. The final production model is then tested on a completely new movie review dataset from Rotten Tomatoes to test the robustness of the model. 

### Data Overview

The labeled data set consists of 50,000 IMDB movie reviews. The sentiment is coded as a binary variable, where a rating less than five results in a sentiment score of zero, and ratings greater than or equal to 7 have a sentiment score of 1. All movies have less than 30 reviews. The 25,000 review labeled training set does not include any of the same movies as the 25,000 review test set. In addition, there are another 50,000 IMDB reviews without any rating labels against which my various models are tested. Finally, a completely different dataset of 150,000 reviews from Rotten Tomatoes is used as a robustness check to see how the model fares with drastically different data. 

### Key Performance Indicators (KPIs)

* Accuracy Score
> How many reviews were correctly identified
* Net Promoter Score
> Description of NPS
* F-Score
> Harmonic mean of precision and recall

## Analysis

Compare the various KPIs across the various models and various datasets.

## Conclusion

In conclusion, deep learning can be a rabbit hole. If you take the red pill, you can see how deep it really goes. 

<img src="https://cdn-images-1.medium.com/max/1600/1*3wVYz3cetZqy2GughF9Obw.png" />
