# twitter-sentiment-analysis
Machine learning project that classifies tweets as positive or negative using NLP, TF-IDF, and Logistic Regression.
# Twitter Sentiment Analysis

## Project Overview

This project uses Natural Language Processing (NLP) and Machine Learning to classify tweets as **Positive** or **Negative**.

It is an AI internship project completed as part of the Codec Technologies AI Internship.

## Objectives

* Analyze sentiment in Twitter data.
* Clean and preprocess text data.
* Convert text into numerical features using TF-IDF.
* Train a machine learning model to predict sentiment.

## Technologies Used

* Python
* NLTK
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

## Dataset

The project uses NLTK's built-in `twitter_samples` dataset, containing:

* 5,000 positive tweets
* 5,000 negative tweets

## Methodology

1. Load and explore the Twitter dataset.
2. Clean tweets by removing URLs, mentions, punctuation, and stopwords.
3. Convert text into numerical features using TF-IDF.
4. Split the dataset into training and testing sets.
5. Train a Logistic Regression model.
6. Evaluate the model using accuracy, classification report, and a confusion matrix.
7. Predict sentiment for new text.

## Machine Learning Model

**Logistic Regression** is used as the main classification model.

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required libraries if needed.
3. Run the notebook cells in order.
4. Enter your own text to predict its sentiment.

## Output

The model predicts whether the given text expresses positive or negative sentiment.

## Future Improvements

* Add neutral sentiment classification.
* Test additional machine learning models.
* Develop a web application for real-time sentiment prediction.

## Internship

Codec Technologies – AI Internship

## Disclaimer

This project is intended for educational purposes.
