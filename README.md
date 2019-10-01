# Bi-Directional-LSTM-NLP
Bi-directional LSTM used on Hotel Reviews from TripAdvisor for NLP analysis.

# Data files
hotel reviews - https://zenodo.org/record/1219899#.XY-QDlB7l0s
GloVe embeddings - https://www.kaggle.com/rtatman/glove-global-vectors-for-word-representation/download

# Code files
HotelSentimentAnalysis.ipynb

# Analysis
I used nltk, a bi-directional long short term memory (LSTM) neural network and 100 dimensional GloVe embeddings to achieve 90%
accuracy for the data set of ~20,000 hotel reviews. I furthered my study by using Keras' CountVectorizer and logistic 
regression in order to determine which were the 10 most common words in a positive review and the top 10 most common words 
in a negative review. 

# A positive review was determined to be 3 stars or more
# A negative review was determined to be 2 stars or less

Thank you and enjoy. Please leave any feedback, questions or ways to improve my algorithm. :D
