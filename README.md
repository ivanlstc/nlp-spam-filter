# Spam Detection Filter

This project was created to allow me to develop skills involved in creating a basic NLP pipeline, such as tokenization, lemmatization, and vectorization.

I have general machine learning experience in both classification and regression problems, but never in the context of natural language processing. I recently finished a LinkedIn Learning course in June 2020 titled ['NLP with Python for Machine Learning Essential Training'](https://www.linkedin.com/learning/nlp-with-python-for-machine-learning-essential-training/), and was inspired to tackle a basic NLP problem first-hand, and explore the concepts discussed at a deeper level.

For this project I have chosen to divide the process into three major steps, and is split up across the three Jupyter notebooks included in this repository:
1. exploratory data analysis
2. preliminary machine learning training/testing
3. hyperparameter tuning and performance analysis of the best ML models

## Files Included
- *spam.csv*: a csv file of a dataset taken from [Kaggle](https://www.kaggle.com/uciml/sms-spam-collection-dataset), which has a collection of 5574 text messages labelled as either 'spam' or 'ham' (not spam)
- *spam_updated.csv* a csv file of the same dataset, but with included features such as the length of each text message, the ratio of capital letters in each message, and the ratio of punctuation characters in each message
- *spam-filter.ipynb*: a Jupyter notebook that includes preliminiary exploratory data analysis on the Kaggle dataset, and the process of building a data cleaning function that is used later in the pipeline
- *spam-filter-ml.ipynb*: a Jupyter notebook that explores the vectorization process in the NLP pipeline, and conducts preliminary training and testing for a multitude of different machine learning algorithms
- *spam-filter-gridsearch.ipynb*: a Jupyter notebook that goes through the hyperparameter tuning process to optimise machine learning models, and discusses the performance of the best models through the examination of different performance metrics

## Usage
This repository is created purely for educational purposes. For reference, the following list includes the relevant packages and modules used throughout the project: [NumPy](https://numpy.org/), [Pandas](https://pandas.pydata.org/), [Seaborn](https://seaborn.pydata.org/), [Scikit-learn](https://scikit-learn.org/stable/), and [Natural Language Toolkit (NLTK)](https://www.nltk.org/). `re` and `string` are also imported to provide access to Python regular expressions and a list of punctuation.

## Author
* [Ivan Li](https://www.linkedin.com/in/ivanli-sc/) - MSci Physics Graduate at Imperial College London