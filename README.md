# Analysing-User-Sentiments-using-movie-reviews
The objective of this project is to build a text classification model that analyses the user's sentiments based on their reviews in the IMDB database.
Sequential Models in NLP | Sentiment Classification 

The model uses a complex deep learning model to build an embedding layer followed by a classification algorithm to analyze the sentiment of the customers.
Dataset: The Dataset of 50,000 movie reviews from IMDB, labelled by sentiment (positive/negative). 

Reviews have been preprocessed, and each review is encoded as a sequence of word indexes (integers). 
The words are indexed by their frequency in the dataset, meaning the word for that has index 1 is the most frequent word. 
"0" does notstand for a specific word, but instead is used to encode any unknown word.
