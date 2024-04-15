# Exploratory Data Analysis (EDA)

## Overview
In this EDA, we explore the distribution of text data and various features relevant to hate speech detection. We utilize word clouds, bar plots, and box plots to visualize the data.

## Word Clouds
We generate word clouds to visualize the most frequent words in the text data. This helps us understand the common themes and topics present in the dataset.

## Bar Plots
We use bar plots to visualize the distribution of categorical variables such as hate speech labels. This provides insights into the class balance and distribution of hate speech instances.

## Box Plots
Box plots are employed to visualize the distribution of continuous variables or features such as text length. This helps us identify outliers and understand the spread of feature values.

---

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
