# Toxicity-Classification
This repository is based on the Toxic Comment Classification Challenge of kaggle. A toxicity classification model for wikipedia comments is built using Machine Learning and NLP. The entire code has been developed using Python programming language, utilizing its powerful text processing and machine learning modules.

## Installation
Along with Python 3, this project requires following libraries :
  * sklearn
  * pandas
  * numpy
  * matplotlib
  * nltk
  * bs4
  * keras
  
## Data 
  The data was taken from the kaggle competition <https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data>

  The data contains 159571 comments which are labelled on the basis of 6 labels-
  Category | Number of comments
  ---------|--------------------
  toxic | 15294
  severe_toxic | 1595
  obscene | 8449
  threat | 478
  insult | 7877
  identity_hate | 1405

  The data is split into train(80%) and test(20%) to fit into the model.

## Toxicity Classifier
  1. Data is preprocessed.
  2. sklearn feature_extraction libraries __CountVectorizer() and TfidfTransformer()__ (term frequency-inverse document frequency formula) is applied to our features. <br/>
  CountVectorizer is used to convert text to word count vectors whereas TfidTransformer is used to convert text to word frequency vecotrs, it defines the importance of a keyword or phrase within a document or a web page.
  3. The following algorithms are applied on the dataset- <br/>
      a) Naive-Bayes Classifier <br/>
      b) Logistic Regression <br/>
      c) LSTM model
      
## Results 
The models are compared on the basis of accuracy. 
The evaluation metircs is mentioned in the python notebooks attached.
