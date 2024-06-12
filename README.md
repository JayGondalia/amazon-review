## Sentiment Analysis on Amazon Reviews

## Group Members:
Jay Gondalia (1196220)
Zeel Parekh (1196109)


## Description:
This project aims to perform sentiment analysis on Amazon reviews using various Natural Language Processing (NLP) techniques and machine learning models.

## Installation:
!pip install nltk
!pip install textblob
!pip install wordcloud


## Usage:
Clone the repository to your local machine.
Install the required dependencies mentioned in the "Installation" section.
Download the necessary NLTK resources by running the provided code snippet.
Ensure that your dataset (amazon_reviews.csv) is placed in the same directory as the code.
Run the code cells provided in the Jupyter Notebook or Python script.



## Contents:
amazon_reviews.csv: Dataset containing Amazon reviews.
sentiment_analysis.ipynb: Jupyter Notebook containing the code for sentiment analysis.
README.md: This file providing instructions and information about the project.


## Code Structure:
1. Data Preprocessing:
Normalizing text, removing punctuation, numbers, and stopwords.
Lemmatization of words.

2. Feature Generation:
Utilizing SpaCy for word embeddings and syntax tree construction.
Calculating term frequencies and generating word clouds.

3. Sentiment Analysis:
Using NLTK's SentimentIntensityAnalyzer and TextBlob for sentiment scoring.
Training machine learning models (Logistic Regression, Random Forest, SVM) for sentiment classification.

4. NLP with SpaCy:
Implementing text categorization with SpaCy's TextCategorizer.
Training a neural network for sentiment classification.

5. Evaluation:
Assessing model performance using accuracy metrics.


## Sample Usage:
Provide sample code snippets demonstrating how to use the trained models for sentiment analysis.


## Contributors:
Jay Gondalia
Zeel Parekh