# Twitter-Sentiment-Analysis

This project involves building a machine learning model to analyze and classify the sentiment of tweets as either positive or negative.

## Table of Contents

- [Overview](#overview)
- [Usage](#usage)
- [Model](#model)
- [Evaluation](#evaluation)


## Overview

The objective of this project is to analyze the sentiment of tweets using a logistic regression model. The dataset used contains labeled tweets indicating positive or negative sentiment. The project includes data preprocessing, model training, evaluation, and saving the trained model for future use.

## Usage

- Load the dataset and preprocess the data by running the Jupyter notebook Twitter_Sentiment_Analysis.ipynb.
- Train the logistic regression model and evaluate its performance.
- Save the trained model using Pickle for future use.

## Model

The logistic regression model is used for sentiment classification. Key steps include:

- Data preprocessing (tokenization, stop-word removal, TF-IDF vectorization)
- Model training using the logistic regression algorithm
- Model evaluation on training and test datasets

## Evaluation

The model achieved an accuracy of:

- Training data: **81%**
- Test data: **77.76%**
