# masterthesisdatascienceuvt
This is my master thesis project for the Master in Data Science Tilburg University, The Netherlands. 
This is a supervised task where the aim was to predict conspiratorial content of transcripts of Youtube. 
The code details all the steps considered in a Data Science project: collecting of data (API from Youtube), 
labeling of data, pre-processing, cleaning, vectorization, modelling and evaluation. 
This is a small data set and is highly unbalanced. To tackle that, I suggest to use regularizers and drop outs
in the classifier in order to prevent overfitting.
For vectorization I used TF IDF and Word2vec. For the classifiers I used SVM as baseline and 
Convolutional Neural Network, as the classifier that given properties of word2vec might outperform SVM

