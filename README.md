# IMDB-using-NLP_RNN-with-adam-RMSprop
# IMDB Movie Review Sentiment Analysis using RNN with Adam and RMSprop Optimizers

This project aims to classify the sentiment of movie reviews from the IMDB dataset using a Recurrent Neural Network (RNN). Two different optimizers, Adam and RMSprop, are used to train the model.

## Overview

Sentiment analysis is a natural language processing (NLP) task that involves determining the sentiment expressed in a piece of text. In this project, we utilize the IMDB dataset, which contains movie reviews labeled as positive or negative.

The RNN architecture used for sentiment analysis consists of an embedding layer, an LSTM layer, and a dense output layer with a sigmoid activation function.

## Usage

1. **Dataset**: The IMDB dataset is pre-loaded using TensorFlow's `imdb.load_data()` function. It is split into training and testing sets.

2. **Preprocessing**: The dataset is preprocessed by padding sequences to a fixed length using `pad_sequences` from Keras.

3. **Model Architecture**: The RNN model architecture is defined using Keras Sequential API, consisting of an embedding layer, LSTM layer, and a dense output layer.

4. **Training**: The model is compiled with either the Adam or RMSprop optimizer and trained on the training data for a specified number of epochs and batch size.

5. **Evaluation**: After training, the model's performance is evaluated on the test set using binary cross-entropy loss and accuracy metrics.

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib (for visualization, optional)

## Installation

Clone the repository:

