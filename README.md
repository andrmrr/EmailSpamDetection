# Spam/Phishing detection
The goal of this project is to train a machine learning model for **anomaly detection**, more precisely for detecting **spam/phishing** emails. 
This project was done in a team of two people as an assignment for the *Advanced Machine Learning* master's course.
Several ML models were tested, namely **Logistic Regression** as a baseline model, **Multi-layer Perceptron** and **SVM** with different kernels.
The data cleaning process included *tokenization*, *removing stopwords*, *lemmatization* and *url handling* etc. 
Nonetheless, the feature engieering was the most challenging part. The raw data included only the raw text of the emails, so we had complete freedom of extracting **NLP** features from the text.
We tried many ideas, such as *bigrams* and *trigrams*, text features like *tfidf*, counts of specific types of words and text length. However, using only (cleaned) tokens brought the best 
classification results.
