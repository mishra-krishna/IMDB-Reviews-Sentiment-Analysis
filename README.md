# Sentiment Analysis of Movie Reviews

This project involves developing a sentiment analysis model to classify movie reviews as positive or negative. The model is built using Python and involves various steps including data preprocessing, feature extraction using Word2Vec, and model training using Logistic Regression with hyperparameter tuning.

## Project Overview

- **Preprocessing**: Tokenization and stopword removal from movie reviews.
- **Feature Extraction**: Training a Word2Vec model to generate word embeddings.
- **Model Training**: Using Logistic Regression with hyperparameter tuning (GridSearchCV).
- **Evaluation**: Classification report and confusion matrix to evaluate model performance.
- **Prediction**: Interactive sentiment prediction for user input.

## Dependencies

The following Python libraries are required to run this project:

- `numpy`
- `pandas`
- `nltk`
- `gensim`
- `scikit-learn`
- `matplotlib`

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/mishra-krishna/IMDB-Reviews-Sentiment-Analysis
    cd IMDB-Reviews-Sentiment-Analysis
    ```

2. Install the required libraries:
    ```sh
    pip install numpy pandas nltk gensim scikit-learn matplotlib
    ```

3. Download NLTK data:
    ```python
    import nltk
    nltk.download('punkt')
    ```

## Usage

1. Place your dataset (`movie.csv`) in the project directory. The dataset should have at least two columns: `text` (containing movie reviews) and `label` (containing sentiment labels, 0 for negative and 1 for positive).

2. Run the script:
    ```sh
    python sentiment_analysis.py
    ```

3. Follow the prompts to enter a sentence for sentiment prediction.

## Project Structure

- `movie.csv`: The dataset containing movie reviews and sentiment labels.
- `sentiment_analysis.py`: The main script containing the code for data preprocessing, model training, and prediction.
- `README.md`: This README file.
