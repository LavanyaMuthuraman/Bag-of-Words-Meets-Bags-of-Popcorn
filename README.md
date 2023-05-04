# Bag of Words Meets Bags of Popcorn

### **Description**
The objective of the [Bag of Words Meets Bags of Popcorn](https://www.kaggle.com/c/word2vec-nlp-tutorial/details/part-1-for-beginners-bag-of-words) Kaggle project is to develop a machine learning model that can accurately **classify movie reviews as either positive or negative.** The dataset for this project consists of movie reviews from the popular movie review website **IMDb**, and the task is to predict the sentiment of each review based on its text content. 

This project is an example of a natural language processing (NLP) task, which involves using machine learning algorithms to analyze and understand human language. The name `Bag of Words` refers to a common technique used in NLP to represent text data as a simple list of word frequencies, which is a useful feature representation for many machine learning models. The reference to `Bags of Popcorn` in the project name is a playful nod to the movie review theme of the project.

### **Data Set**
The [Dataset](https://www.kaggle.com/competitions/word2vec-nlp-tutorial/data) of 50,000 movie reviews from IMDb, where each review is labeled as either positive or negative. The dataset is split into two sets, a training set of 25,000 reviews and a test set of 25,000 reviews. The training set is further divided into a labeled set of 12,500 positive reviews and 12,500 negative reviews. The test set is unlabeled and used for evaluating the performance of machine learning models.

**Data fields**
- `id` - Unique ID of each review
- `sentiment` - Sentiment of the review; 1 for positive reviews and 0 for negative reviews
- `review` - Text of the review

This project focuses on building a text classification model to classify movie reviews of a given text using the Bag-of-Words approach. The project is divided into several sections, data cleaning and text preprocessing, creating features from a bag of words, modularizing the cleaning process, loading and cleaning test data, and finally building and evaluating models, including Random Forest and XG Boost. 

**The results of the project show that the Random Forest model outperformed the XG Boost model with a score of 0.84628 without stemming and 0.84476 with stemming.** Overall, the project demonstrates a practical approach to text classification using the Bag-of-Words method and machine learning techniques.

![pop2](https://user-images.githubusercontent.com/109660074/236332120-d2a8bae3-240e-4fdf-a44c-28e7ff9648b0.jpg)

 
