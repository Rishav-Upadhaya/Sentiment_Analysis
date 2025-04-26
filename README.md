# IMDB Movie Review Sentiment Analysis

## Overview
This project implements a sentiment analysis model that classifies movie reviews as positive or negative using the IMDB Dataset. The model uses Natural Language Processing (NLP) techniques and machine learning to analyze text reviews and predict sentiment.

## Features
- Text preprocessing including HTML tag removal, punctuation removal, and stop word elimination
- TF-IDF vectorization for text feature extraction
- Logistic Regression model for binary classification
- Model evaluation with accuracy metrics, confusion matrix, and classification report
- Real-time prediction capability for new reviews

## Requirements
- Python 3.x
- Required libraries:
  - pandas
  - numpy
  - nltk
  - scikit-learn
  - joblib
  - re

## Project Structure
```
Sentiment_Analysis/
│
├── Sentiment_analysis.ipynb    # Main Jupyter notebook with implementation
├── .gitignore                 # Git ignore file
└── README.md                  # Project documentation
```

## Usage
1. Clone the repository
2. Install required dependencies:
   ```
   pip install pandas numpy nltk scikit-learn joblib
   ```
3. Download the IMDB Dataset and place it in the appropriate directory
4. Run the Jupyter notebook `Sentiment_analysis.ipynb`

## Model Performance
The model is trained on a large dataset of IMDB reviews and evaluated using:
- Accuracy score
- Confusion matrix
- Classification report showing precision, recall, and F1-score

## Example Usage
The notebook includes example code for making predictions on new movie reviews:
```python
new_reviews = [
    "This movie was absolutely fantastic!",
    "What a waste of time. Would not recommend.",
    "It was an okay movie, quite average."
]
```

## Contributing
Feel free to open issues and submit pull requests to improve the project.
