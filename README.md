# Emotion-and-Sentiment-Analysis-of-Tweets

## Overview

This repository contains Python code for analyzing emotions and sentiments in tweets. The analysis includes exploratory data analysis (EDA), sentiment analysis using the RoBERTa model. The dataset used here 

## Prerequisites

1. Download the training.1600000.processed.noemoticon.csv dataset from kaggle, https://www.kaggle.com/datasets/utkarshx27/sentiment-analysis. This dataset is not required since the tweets_with_emotion csv file is provided which has emotion and sentiment tags.

2. Download and import the dataset, tweets_with_emotion csv which is provided. This dataset is tagged with emotion labels and sentiment labels. (Sufficient to perform data preprocessing, data analysis and model training)

3. Download the following glove embeddings glove.twitter.27B.zip. Unzip the folder and extract the glove.twitter.27B.100d.txt file. Upload this in drive in the following path
'/content/drive/MyDrive/Colab Notebooks/IST 664/Labs_Final/glove.twitter.27B.100d.txt'

## Uploading Code to Google Colab

To run the code in Google Colab, follow these steps:

1. Open Google Colab in your browser: [Google Colab](https://colab.research.google.com/).
2. Open the provided python notebook file (SentimentAnalysis.ipynb) in your Colab environment.

## Uploading Files in Colab

Upload the following files in Colab which is attached with the submission:

1. tweets_with_emotion.csv - Twitter Dataset with sentiment and emotion labels classified

The following files can be uploaded using the below python code:

```python
from google.colab import files
uploaded = files.upload()
```
