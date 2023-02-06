# sentiment-analysis

# Objective
**What is Sentiment Analysis?**

**Sentiment analysis** (also known as opinion mining) is one of the many applications of Natural Language Processing. It is a set of methods and techniques used for extracting subjective information from text or speech, such as opinions or attitudes. In simple terms, it involves classifying a piece of text as positive, negative or neutral.
This tutorial is a series of two parts.

- Tutorial 1 (this part) : Getting familiar with NLP concepts like BOW, TFIDF, Word Embeddings, data cleaning and preprocessing,...
- Tutorial 2 : Apply advanced state-of-the-art model in NLP for sentiment analysis task. Our focus will be on BERT model.

## Project Structure 

```bash
└── Data
    └── tf.csv
    └── tf_test.csv
└── NLP_BOW_TFIDF_WORD2VEC.ipynb
└── readme.md
```
## Project Overview
The dataset for this project is obtained from Kaggle which contains the data sourced from a survey conducted by airlines on the satisfaction level of passengers/customers based on various factors. 
The dataset consists of 25 columns such as Age, Gender, Travel class, Arrival and Departure delays and also features that influences customer satisfaction level such as On-board service, Cleanliness, Seat comfort, Baggage handling etc.
Our target variable ‘satisfaction’ describes the overall satisfaction level of the customer. It has two values, ‘neutral or dissatisfied’ and ‘satisfied’.
The dataset consists of 103904 and 25976 records in train and test respectively.

## Methodology
This notebook is structured as follows :

- Part 1 :Tweet analysis (EDA, data cleaning, text normalisation,...)
- Part 2 : Modelisation with 3 classifiers (RF, LR, Naive Bayes) to predict the sentiment of a tweet. These approaches will mainly focus on uni-gram, bi-gram ,tri-gram and Word Embeddings using Gensim library.



