# NLP_Item_classification
NLP for classifying items of an E-commerce platform 

## Intro

The company has a huge and varied amount of data from items, users, conversations, transactions, etc, and of all types: numerical, categorical, eventual, text and images. 

As part of a Product initiative, the Data Science team is asked to develop a solution to properly classify listings that fall between two categories: 0-Cellphones and 1-Computers. We could use a lot of data from existing items (title, description, images, price, and other fields and metadata), but as an MVP, we decide to implement a ML solution based only on text (the items title), and frame it as a binary classification problem.

This code gets data from a .json file containing text data and perform the classification. 

## Strategy

* Train a Random Forest (RF) algorithm using sklearn
* Build a RNN LSTM architecture with word embeddings using TensorFlow
* Discuss metrics and improvements on the dataset

