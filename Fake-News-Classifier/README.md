# Fake-News-Classifier
This model can be used to classify  whether news is Fake or Real. It is using various NLP models like Bag of Words, TF-IDF, LSTM etc.
This is Natural Language Processing problem.


# Problem Statement

This problem is to identify whether a given news is fake or real. The independent feature can be title of news or news lines themselves.
In the above notebooks, I have tried four different ways to solve this problem.
These four models are Bag of Words, TF-IDF, RNN LSTM and Bidirectional RNN LSTM.

# Dataset

The dataset for news is taken from Kaggle https://www.kaggle.com/c/fake-news/. The dataset is quite huge containing thousands of rows. We expect our model to be highly accurate. You can refer to the link given for dataset.

# Accuracy Score of different model

* Bag of Words using Stemming : 0.9026
* TF-IDF using Lemmatization  : 0.8814
* RNN LSTM                    : 0.9133

# Conclusion

We can see that RNN LSTM gave a greater accuracy than Bag of Words, TF-IDF and LSTM model. Hence, this model should be preferred over others.
