# Emotion-and-Sentiment-Analysis-of-Tweets

## Overview

This repository contains Python code for analyzing emotions and sentiments in tweets. Utilizing a Kaggle dataset as the foundation, our exploration is propelled by the advanced RoBERTa model, a transformer-based architecture recognized for its adeptness in sentiment and emotion classification. The resultant dataset is a finely annotated compilation, providing a nuanced perspective on emotions intertwined with sentiments. Rigorous pre-processing techniques ensure data integrity, while feature extraction methods such as CountVectorizer, TF-IDF, and GloVe embeddings contribute to a comprehensive analysis.

Machine learning models, including Naive Bayes, Logistic Regression, Decision Tree, Random Forest, SVM, and XGBoost, are employed alongside deep learning models like Word2Vec with LSTM, GloVe with LSTM, Word2Vec with CNN, GloVe with CNN, Word2Vec with GRU, and GloVe with GRU. Comparative evaluations based on metrics such as Accuracy, Precision, Recall, and F1 score lead to insights on model performance. This research aims to contribute valuable insights into the intricate tapestry of sentiments and emotions within the digital discourse, offering a deeper understanding of human expression in the contemporary age of social media.

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
