# Hate Speech Detection Project

## Overview
This project focuses on detecting hate speech in text data using two different models: Support Vector Machine (SVM) and Random Forest. The project utilizes techniques such as word embedding and TF-IDF vectorization for feature representation.

## Dependencies
- pandas
- scikit-learn
- gensim

## Usage

### Step 1: Data Loading and Preprocessing
1. Load your training data from a CSV file.
2. Preprocess the data by tokenizing the text and converting it to lowercase.

### Step 2: Train Word Embedding Model
1. Train a Word2Vec model using the tokenized comments.
2. Transform each comment into a vector representation by averaging word vectors.

### Step 3: Train SVM Classifier
1. Split the data into training and testing sets.
2. Train an SVM classifier using the word vector representations.

### Step 4: Evaluate SVM Classifier
1. Evaluate the classifier using metrics such as accuracy score and classification report.

### Step 5: Train Random Forest Classifier
1. Vectorize the text data using TF-IDF representation.
2. Train a Random Forest classifier on the TF-IDF vectors.

### Step 6: Evaluate Random Forest Classifier
1. Evaluate the Random Forest classifier using accuracy score and classification report.
