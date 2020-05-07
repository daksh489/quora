# Quora
    I have text data sets of quora questions and target variable denoting the sincerity of the question.
        Train Data Set Size: 1.3M
        Test Data Set Size: 375K
    
    The goal is to classify if the question is insincere from the text.
    
### Methods Used:
    Preprocessing and cleaning texts using word embeddings
    EDA
    Models:
        Base Model of Logistic Regression using TFIDF Matrix
        Neural Networks using Word embeddings
    Accuracy Metric: F1-score of target label '1'
    
### F1-Scores:
        Logistic: 0.59
        Keras: 0.66
### Kaggle link for data set and embeddings:
    https://www.kaggle.com/c/quora-insincere-questions-classification
