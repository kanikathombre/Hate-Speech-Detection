# Hate Detection from Scraped Comments

## Overview
This project aims to detect hate speech from scraped comments gathered from online platforms. The process involves importing the dataset, preprocessing it, and implementing hate speech detection algorithms.

## Tasks Completed
- Imported the dataset containing scraped comments.
- Conducted preprocessing steps to clean the data:
  - Stopwords removal for both English and Hinglish languages.
  - Removal of special characters, emojis, and numbers.
  - Conversion of all tokens to lowercase.
- Implemented a function for lemmatization to further normalize the text data.

## Preprocessing Steps
### Stopwords Removal
Stopwords were removed from both English and Hinglish comments to eliminate common words that do not carry significant meaning.

### Removal of Special Characters, Emojis, and Numbers
Special characters, emojis, and numbers were removed from the comments to ensure that the text data consists only of relevant words.

### Conversion to Lowercase
All tokens in the comments were converted to lowercase to standardize the text data and avoid duplicate entries based on case differences.

### Lemmatization
Lemmatization was performed to reduce inflected words to their base or dictionary form, which helps in improving the accuracy of hate speech detection algorithms.

## Repository Structure
- `data/`: Directory containing the dataset files.
- `preprocessing.py`: Python script for data preprocessing tasks.
- `hate_detection.py`: Python script for hate speech detection algorithms.
- `README.md`: README file providing an overview of the project and instructions for usage.

## Contributing
Contributions to improve the preprocessing techniques or hate speech detection algorithms are welcome. Please open an issue or submit a pull request with your suggestions.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
