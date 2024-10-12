# Sentiment Analysis with Sentiment140 Dataset

This project implements sentiment analysis using the **Sentiment140 dataset**, which consists of labeled tweets for sentiment classification. The aim is to build machine learning models, including deep learning approaches like LSTM, to classify tweets as positive or negative.

## Repository Contents

1. **`Data_preprocessing.ipynb`**  
    - This notebook is dedicated to preparing the data for analysis. The following tasks are performed:
        - Loading the Sentiment140 dataset.
        - Cleaning the tweets by removing unnecessary elements such as URLs, emojis, and special characters.
        - Tokenizing and vectorizing the tweets to make them suitable for machine learning models.
        - Splitting the dataset into training and testing sets.

2. **`EDA_and_ML_models.ipynb`**  
    - This notebook covers exploratory data analysis (EDA) and initial model building:
        - Performing statistical and visual analysis of the dataset to understand patterns and trends.
        - Visualizing data distributions, word frequencies, and text length statistics.

3. **`Training_LSTM_model.ipynb`**  
    - This notebook focuses on building a Long Short-Term Memory (LSTM) neural network for text classification. Key steps include:
        - Preprocessing the text data for LSTM.
        - Creating an LSTM model using TensorFlow/Keras.
        - Training the LSTM model on the dataset and evaluating its performance.

## Dataset

The **Sentiment140** dataset contains 1.6 million tweets, each labeled as either:
- `0`: Negative sentiment
- `4`: Positive sentiment

More information on the dataset can be found [here](https://www.kaggle.com/datasets/kazanova/sentiment140).
