# Twitter Sentiment Analysis

This repository contains a Python script for conducting sentiment analysis on Twitter data. The goal is to classify tweets as either positive or negative using machine learning techniques.

## Dataset

The dataset used for this analysis is the Sentiment140 dataset, which contains 1.6 million tweets. It can be downloaded from [Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140).

## Requirements

To run the code, you need the following Python libraries:
- numpy
- pandas
- re
- nltk
- scikit-learn
- kaggle

  ## Results and Insights
- Data Distribution: The dataset contains an equal number of positive and negative tweets, with 800,000 tweets in each category
- Model Accuracy: The logistic regression model achieved an accuracy of 77.8% on the test data.
- Usage: The trained model can classify new tweets as positive or negative.


You can install the required libraries using pip:
```sh
pip install numpy pandas nltk scikit-learn kaggle
