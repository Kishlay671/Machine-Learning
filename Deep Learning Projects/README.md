# IMDB Reviews Sentiment Analysis using LSTM

This project performs sentiment analysis on the IMDB movie reviews dataset using an LSTM-based neural network in TensorFlow/Keras.

## Project Overview

The objective of this project is to classify IMDB movie reviews as positive or negative using deep learning (LSTM model).

## Dataset

- Dataset used: **IMDB Reviews** from TensorFlow Datasets.
- Preprocessed and tokenized using `Tokenizer` from Keras.

## Model Architecture

- **Embedding Layer**: Converts words to dense vectors.
- **LSTM Layer**: Learns long-term dependencies in text.
- **Dense Output Layer**: Uses sigmoid activation for binary classification.

## Training

- **Loss Function**: Binary Crossentropy
- **Optimizer**: Adam
- **Metrics**: Accuracy
- Trained over multiple epochs with validation split.

## Results

- The model achieves reasonable accuracy on test data, capable of distinguishing between positive and negative reviews.

## Requirements

- Python
- TensorFlow
- Keras
- Matplotlib

## How to Run

1. Install the required libraries.
2. Open the notebook: `DL_Pro_10_IMDB_reviews_Sentiment_Analysis_LSTM.ipynb`
3. Run the cells sequentially to train and evaluate the model.

## Author

Generated automatically based on the Jupyter Notebook.

