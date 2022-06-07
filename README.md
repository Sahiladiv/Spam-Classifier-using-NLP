# Spam-Classifier-using-NLP
Dataset of spam SMS: https://archive.ics.uci.edu/ml/machine-learning-databases/00228/smsspamcollection.zip

Steps executed for implementation:
1. Data cleaning and pre-processing:Using 're' and 'stopwords' of 'nltk.corpus' library the dataset is cleaned and pre-processed so that lemmatization can be performed.
2. Creating the TF-IDF model: TF-IDF is used for vectorising the words. Term Frequency (TF): (No. of repititions of words in sentence)/(No. of words in sentence) and Inverse Document Frequency = log[(No. of sentences)/(No. of sentences containing words)]
