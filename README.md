# NLP Projects
This repository contains projects related to Natural Language Processing. The projects include • Language Modelling  • Text Classification  • Information Extraction  • Topic Modelling  • Information Retrieval  • Text Summarization  • Question Answering  • Machine Translation  • Conversational Agents. 

## NLP Getting Started
This folder contains the notebook files containing basic operations related to data acquisition, web scrapping and reading text from pdf. It also contains the code related to common data cleaning techniques, spell checker codes, tokenization, stemming, lemmatization, contraction, POS tagging, entity recognition, and coreference resolution. These files mainly serve as the toolbox that can provide the code snippets when working with complex projects.

## Feature Extraction
This folder contains the notebook file with the codes related to extracting features from text. It includes filtering based on word frequency, creating Bag of Words model and finding TF-IDF values. These code snippets can be used with any NLP projects for extracting important feature from the text.

## Knowledge Extraction
### Project: Prescription Parser
This project is for the healthcare system where the AI model will analyze the prescription of the doctor and analyze different styles of writing to identify the method, quantity, duration, frequency, time etc. for taking medicines. This prescription parser can be used by any pharmacy to provide medicines as per the prescriptions. It can also be used by pharmacies that sell online medicines.

## Recommender System
### Project: Movier Recommender
This project takes the Netflix movie data of 100k movies and their ratings and recommend movies based on different recommendation system. It provides the content based recommendation and ratings based recommendation using cosine similarities. It uses TFIDF Vectorizer and TruncatedSVD for feature extraction. The code can process the data of 20M movies with GPU.

## Text Classification
### Project: News Topic Modelling
This project uses text classification techniques to predict the topic of the content with given text. It uses the dataset 'fetch_20newsgroup' from sklearn. The uploaded notebook contains the classification using the articles for only 2 topics considering the available computational resources. It uses countvectorizer, word2vec and doc2vec for feature extraction and compare the accuracies between all 3 methods. It also compares multiple ML algorithms and generates the table to compare the accuracies and find best algorithm with the most suitable feature extraction method.

## Summarization
This notebook takes a sample data from a web page and compares different summarizers available. It calculates Flesch-Kincaid Grade Level and ARI (Automated Readability Index) to select the best summarizer for intended age group of the readers and it calculates rouge score for all summarizer to compare it with a human summarized text.
