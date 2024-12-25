# Fake News Detection Using Machine Learning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1yOeUYRcHKMlGihIGiIUkl35Mm0_PNGwZ?usp=sharing)

This notebook demonstrates how to build a machine-learning model to detect fake news articles. 

## Overview & Introduction

The notebook uses a dataset of news articles labeled as real or fake. It preprocesses the text data, extracts features using TF-IDF, trains a Logistic Regression model, and evaluates its performance.

## Steps

1. **Data Acquisition:**
   - Download the `train.csv` dataset from the following link:
     [https://www.kaggle.com/c/fake-news/data?select=train.csv](https://www.kaggle.com/c/fake-news/data?select=train.csv)
   - Upload the downloaded `train.csv` file to your Colab environment.

2. **Data Loading and Preprocessing:**
   - Loads the news dataset from the CSV file.
   - Handles missing values.
   - Combines author and title for content.
   - Applies stemming to reduce words to their root form.

3. **Feature Extraction:**
   - Converts text data to numerical features using TF-IDF.

4. **Model Training:**
   - Splits the data into training and testing sets.
   - Trains a Logistic Regression model on the training data.

5. **Evaluation:**
   - Calculates the accuracy of the model on both training and testing data.

6. **Prediction:**
   - Demonstrates how to use the trained model to predict whether a new news article is real or fake.

## Dependencies

- Python 3
- Libraries: numpy, pandas, re, nltk, sklearn

## Usage

1. Follow the instructions in the "Data Acquisition" step to download and upload the dataset.
2. Run all the cells in the notebook sequentially.
3. Observe the accuracy scores and prediction results.

## Note

- The model's accuracy is indicative of its performance on the given dataset.
- Further improvements can be explored by using different models, feature engineering techniques, and hyperparameter tuning.
