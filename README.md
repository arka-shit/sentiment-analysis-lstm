# sentiment-analysis-lstm
Sentiment Analysis using Word Embedding and LSTM (Long short-term memory)

View this notebook on nbviewer to see the interactive plotly plots

https://nbviewer.org/github/arka-shit/sentiment-analysis-lstm/blob/main/sentiment_analysis_lstm.ipynb

Developed a Neural Network based model with LSTM Layers for Sentiment Analysis. I have used the Yelp Dataset to train and validate the model. First mapped the star ratings to sentiment. Done the analysis on 3 sentiment levels: negative, neutral and positive. Preprocessed the text by lowering it, removing punctuations, deaccentizing, tokenizing, lemmatizing, creating a vocabulary and doing vocab transform. Also fixed the class imbalance issue in the data by under-sampling majority classes. Defined a neural network having embedding, LSTM and fully connected layers. I have used Cross Entropy Loss as the loss function and Adam as the optimizer. Trained and tested the model in batches for multiple epochs. Also tuned the hyperparameters of the model. Finally, I was able to achieve 77% accuracy through the model.