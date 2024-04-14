# Hate Speech Detection

This project focuses on detecting hate speech from text data and classifying it into specific categories like Misogyny, Sexism, Body Shaming, and Rape. The text data has been cleaned and preprocessed using NLTK (Natural Language Toolkit) for tasks like tokenization and lemmatization. The final classification involves determining if a given text contains hate speech and then further categorizing it into one of the identified types.

## Data Cleaning and Preprocessing

The data preprocessing steps include:
- *Text Cleaning:* Removing unnecessary characters, punctuation, and special symbols.
- *Tokenization:* Splitting text into words or tokens.
- *Lemmatization:* Converting words to their base or root form (e.g., "running" to "run").

## Hate Speech Classification

After preprocessing, the data is classified as either hate speech or non-hate speech. For texts classified as hate speech, further categorization is performed based on the specific type of hate speech detected:

- *Misogyny:* Hate speech targeting women or expressions of misogyny.
- *Sexism:* Discriminatory or prejudiced attitudes or behavior based on a person's sex or gender.
- *Body Shaming:* Negative statements or attitudes towards a person's body or appearance.
- *Rape:* Speech involving references or implications related to sexual assault.

## Project Structure

The project is structured as follows:
- data/: Contains the raw and processed datasets.
- src/: Includes Python scripts for data preprocessing, classification, and model training.
- models/: Stores trained machine learning or deep learning models.
- README.md: This file providing an overview of the project.

## Getting Started

1. *Clone the Repository*
   ```bash
   git clone https://github.com/yourusername/hate_speech_detection.git 
