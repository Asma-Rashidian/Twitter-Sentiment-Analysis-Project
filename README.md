# Twitter Sentiment Analysis Project

## Overview

This repository contains the code and documentation for a sentiment analysis project using Twitter data. The primary objective of this project is to classify text documents from the Twitter "Twitter dataset" according to the expressed sentiments, categorized into positive, negative, neutral, or irrelevant.

## Project Goals

The goal of this project is to leverage classification models to analyze and predict sentiments expressed in Twitter posts. Using a structured approach, the project aims to preprocess data, train sentiment analysis models, and evaluate their performance rigorously.

## Covered Topics
- Classification
- Text mining

## Dataset

The dataset, referred to as the "Ayaz dataset," comprises text documents each tagged with a specific sentiment. The dataset is divided into three parts:
- **Twitter-training** - Used for training the models.
- **Twitter-test** - Used for preliminary testing and model tuning.
- **Twitter-validation** - Used for final model validation and performance assessment.

### Data Columns
- **Your ID**: Unique identifier for each text document.
- **Existence**: Indicates entities in the text about which feelings are expressed.
- **Feeling**: Sentiment expressed in the text (positive, negative, neutral, or irrelevant).
- **The content of the website**: Actual text content of the Twitter post.

## Methodology

### 1. Data Preprocessing
The raw dataset undergoes several preprocessing steps to make it suitable for model training:
- Removal of special characters.
- Conversion of text to lowercase.
- Elimination of stop words.
- Stemming and lemmatization.
- Any additional necessary preprocessing steps.

### 2. Feature Selection
Features are extracted from the preprocessed text documents using common methods such as:
- Bag-of-Words
- TF-IDF
- Word embeddings (Word2Vec, GloVe)

### 3. Model Training
Multiple classification models are trained using the processed data. At least two models will be used:
- Naïve Bayes
- Support Vector Machine (SVM)

### 4. Model Evaluation
Models are evaluated using the Twitter-test dataset with metrics like:
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Accuracy

Performance results are documented and compared.

### 5. Model Validation and Reporting
The final model validation is performed using the Twitter-validation dataset. An Excel file is created for each tested model, with an additional column named "PredictedSentiment" to save the predicted sentiment tags.
