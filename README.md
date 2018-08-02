# Spam Classification 

In this project, we will explore text message data and create models to predict if a message is spam or not. We obtained the data set from https://www.kaggle.com/uciml/sms-spam-collection-dataset. This is a Supervised Text Classification problem. The dataset can be found in the same directory spam.csv and includes following features:

**Steps Involved:**

-  **Data Cleaning**: Dealing with incorrect encodings, removing unnecessary/invalid features
-  **Data Exploration**: Find high frequency words for spam vs not spam messages, explore features such as average length of document, average no. of digits per document and average no. of non-words per document
-  **Data Preprocessing**: Converting the text features into vectors using TFIDF vectorizer
-  **Feature Engineering**: Adding additionally created features to training and test datasets
-  **Model Training**: Training different classification models-**Multinomial Naive Bayes**, **SVM** and **Logistic Regression**
-  **Evaluation**: Comparing the accuracy and recall scores for different models to select the most suitable one
-  **Conclusions**: Choosing the best model with appropriate reasons

**Dependencies:**

-  pandas
-  numpy
-  sklearn
-  scipy
-  wordcloud
-  sklearn
