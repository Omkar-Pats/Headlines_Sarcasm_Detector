# Headlines_Sarcasm_Detector

 * Used labelled Dataset from Huff. post and theonion.com
 * Used NLTK and Spacy for pre-processing
 * Trained a deeplearning Bi directional LSTM model using GloVe 
 * Pickled the model
 * Created a Flask API Endpoint to classify descriptions using the saved model
 
 # Resources used
 
Python: v3.10
Libraries: pandas, numpy, sklearn, nltk, matplotlib, flask, flask_bootstrap, pickle, tensorflow, WordCloud, re, seaborn

# Class distribution
![Counts of each class](https://github.com/Omkar-Pats/Headlines_Sarcasm_Detector/blob/main/Data%20count.png)

0 represents Non-Sarcatic

1 represents Sarcastic

# Word Cloud
![Generated word cloud](https://github.com/Omkar-Pats/Headlines_Sarcasm_Detector/blob/main/wordcloud.png)

# Model performance

The Bi directional model delivered an accuracy of 86% on the test data.

# Deployment

A flask API endpoint hosted on local server was built. The input text was cleaned, tokenized and padded in order to fit the requirements of the model and 
evaluate the result

![Webpages](https://github.com/Omkar-Pats/Headlines_Sarcasm_Detector/blob/main/Webpage.png)
![Predictions](https://github.com/Omkar-Pats/Headlines_Sarcasm_Detector/blob/main/Prediction.png)
