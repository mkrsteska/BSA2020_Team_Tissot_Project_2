# Real or Not? NLP with Disaster Tweets

Big-Scale Analytics 2020

Professor: Michalis Vlachos  <br /> 
Teaching Assistant: Ahmad Ajalloeian

## Overview ##

## Structure of the project ##
**In order to run the notebooks, please download the GloVe model from this link: https://drive.google.com/file/d/1jnyyMXLPUAY8Fh4cSXSeDzRnJHE-gKUz/view?usp=sharing and place it in the data folder.**

**In order to run the notebooks in Google Colab, please upload the file 'preprocess_tweets.py', that is placed in the code folder**

## Models ##

Embedding Layer from Keras and Dense Layer <br />

GloVe Embeddings and LSTM <br />
Glove Embeddings and Bidirectional LSTM <br />
Glove Embeddings and CNN LSTM <br />

Universal Sentence Encoder and Dense Layers <br />
Universal Sentence Encoder and CNN LSTM <br />
Universal Sentence Encoder and SVM <br />

Bidirectional Encoder Representations from Transformers <br /> 

## Dataset ##
**Files** <br />
train.csv - the training set <br />
test.csv - the test set <br />

**Columns** <br />
id - a unique identifier for each tweet <br />
text - the text of the tweet <br />
location - the location the tweet was sent from (may be blank) <br />
keyword - a particular keyword from the tweet (may be blank) <br />
target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0) <br />

## Current results ##
We achieved the best result with Universal Sentence Encoder and SVM: 0.82719. 
