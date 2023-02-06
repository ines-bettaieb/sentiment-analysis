# sentiment-analysis

# Objective
**What is Sentiment Analysis?**

Sentiment analysis (also known as opinion mining) is one of the many applications of Natural Language Processing. It is a set of methods and techniques used for extracting subjective information from text or speech, such as opinions or attitudes. In simple terms, it involves classifying a piece of text as positive, negative or neutral.
This project will be divide into 2 parts : 
- First part will be devoted to analyse our tweet dataset along with some data cleaning and preprocessing steps. 
We will apply then standards methods (e.g. Bag of words (BOW) and tf-idf) to convert our tweets into  

The objective of this project is to guide an airline company to determine the important factors that influences customer's satisfaction.
Customer satisfaction plays a major role in affecting the business of a company therefore analysing and improving the factors that are closely related to customer satisfaction is important for the growth and reputation of a company.
## Project Structure 

```bash
AirlinePassengerSatisfaction
└── Utilis
    └── __init__.py
    └── utilis.py
└── Datasets
    └── test.csv
    └── train.csv
└── satisfaction.ipynb
└── readme.md
```
## Project Overview
The dataset for this project is obtained from Kaggle which contains the data sourced from a survey conducted by airlines on the satisfaction level of passengers/customers based on various factors. 
The dataset consists of 25 columns such as Age, Gender, Travel class, Arrival and Departure delays and also features that influences customer satisfaction level such as On-board service, Cleanliness, Seat comfort, Baggage handling etc.
Our target variable ‘satisfaction’ describes the overall satisfaction level of the customer. It has two values, ‘neutral or dissatisfied’ and ‘satisfied’.
The dataset consists of 103904 and 25976 records in train and test respectively.

## Methodology
This notebook is structured as follows :
- Part 1 : EDA with analysis of missing data, data cleaning, uni and bi-variate analysis and data preprocessing
- Part 2 : Baseline model using 3 classifiers (Random Forest, Logistic regression and Gradient Boosting)
- Part 3 : Hyperparameter tuning and feature selection
- Part 4 : Final model selection using the most significant features
- Part 5 : Error Analysis 

## Conclusion
Random Forest classifier achieved the best results in terms of accuracy (93.3%), precision (~94.0%) and recall (91.0%).
Among the 22 variables, only 6 play a significant role on customer's satisfaction : 'Class','Inflight entertainment','Seat comfort','Online boarding','Inflight wifi service' and 'Type of Travel'.
