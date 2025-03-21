# Text-Classification
Overview of the classical tools for Natural Language Processing in sentiment analysis.

In this project, we will load the IDMb dataset, consisting of text reviews of films, labeled by an appreciation : 1 if the review is positive, 0 if it is negative. 
The goal will, given the text, be to predict the label, which is producing a model that, given a text input, will decide whether the text is (semantically) positive or negative.

To do so, we will analyse the dataset before testing 2 kinds of word embeddings, and 2 models for each : 
- A TD-IDF embedding, that simply maps a text to a vector representing some frequency or absence of each word. We will use on it a naive MoE model and a logistic regression
- A word2vec embedding that maps each word to a vector capturing its "meaning", so each text to a matrix. We will use a CNN and a LSTM over this embedding.  
