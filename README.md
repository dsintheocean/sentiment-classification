# NLP Comments Sentiment Classification

## Project Description

It is necessary to create a tool to assess the toxicity of comments in order to automatically send them for moderation.  
The task is to train a model to classify comments as positive or negative.  
There is a dataset with labels indicating toxicity.  

## Key Findings
The task of binary classification with natural language processing has been solved.  
Tokenization was performed using Spacy, and text cleaning was done using regular expressions.  
Features were generated from the original text using the TF-IDF vectorizer.  
The target F1 score of 0.74 was achieved using the CatBoost model.  

## Additional Information
Toolkit: Pandas, re, Spacy, TF-IDF, Python, Data Preprocessing, CatBoost, Scikit-learn.
