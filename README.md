# Movie Genre Classification Model

This project implements a machine learning model to predict the genre of a movie based on its plot summary using Natural Language Processing (NLP) techniques like TF-IDF and classification algorithms such as Naive Bayes. The dataset includes movie titles, genres, and plot summaries.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Technologies Used](#technologies-used)
4. [Model Training](#model-training)
5. [Evaluation](#evaluation)

## Project Overview

This project predicts the genre of a movie using its plot summary. It leverages a dataset that includes movie titles, plot summaries, and genres. The text data is transformed using TF-IDF (Term Frequency-Inverse Document Frequency) and a Naive Bayes classifier is trained on this transformed data.

## Dataset

The dataset consists of three files:
- `train_data.txt`: Contains the training data with movie titles, genres, and plot summaries.
- `test_data.txt`: Contains the testing data with movie titles, genres, and plot summaries.
- `test_data_solution.txt`: Contains the true genre labels for the test data.

Each entry in the dataset follows this format: ID ::: Title ::: Genre ::: Plot Summary


## Technologies Used

- Python 3.x
- Scikit-learn
- Pandas
- TF-IDF Vectorizer
- Naive Bayes Classifier
- Logistic Regression (optional)

## Model Training

1. **Preprocessing**: 
   The dataset is preprocessed by extracting the plot summaries and their corresponding genres.

2. **TF-IDF Transformation**: 
   The plot summaries are converted into numerical features using TF-IDF.

3. **Classifier**: 
   The Naive Bayes classifier is trained on the TF-IDF vectors to learn the relationship between plots and genres.

4. **Evaluation**: 
   After training, the model is evaluated using test data and performance metrics like accuracy, precision, recall, and F1-score.
odel training script:


  
