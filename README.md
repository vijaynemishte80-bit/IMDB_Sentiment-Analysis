IMDb Movie Review Sentiment Analysis Using RNN

Overview

This project performs Sentiment Analysis on IMDb movie reviews using a Recurrent Neural Network (RNN) built with PyTorch. The model classifies reviews as either Positive or Negative by learning patterns from preprocessed text data.

Dataset

- Dataset: IMDb Movie Reviews Dataset
- Total Reviews: 50,000
- Classes:
  - Positive
  - Negative

Technologies Used

- Python
- Pandas
- NLTK
- Scikit Learn
- PyTorch
- Deep Learning
- Natural Language Processing

Key Features

- Text cleaning and preprocessing
- URL removal
- HTML tag removal
- Punctuation removal
- Stopword removal
- Word stemming
- TF IDF feature extraction
- Label encoding
- RNN based sentiment classification
- Model training and evaluation

Project Workflow

1. Data Loading

- Load IMDb review dataset
- Remove duplicate reviews

2. Text Preprocessing

- Convert text to lowercase
- Remove URLs
- Remove HTML tags
- Remove punctuation
- Remove stopwords
- Apply Porter Stemming

3. Feature Engineering

- Convert text into numerical vectors using TF IDF
- Maximum Features: 5000

4. Data Preparation

- Train Test Split
- Convert data into PyTorch tensors
- Create DataLoader objects

5. Model Architecture

Recurrent Neural Network

- Input Layer
- RNN Layer
- Hidden Size: 128
- Fully Connected Layer
- Sigmoid Activation Function

Training Configuration

Parameter| Value
Model| RNN
Optimizer| Adam
Loss Function| Binary Cross Entropy Loss
Epochs| 10
Batch Size| 64
Hidden Size| 128

Evaluation

The model performance is evaluated using:

- Accuracy Score
- Binary Classification Prediction

Results

The RNN model successfully learns sentiment patterns from movie reviews and predicts whether a review expresses a positive or negative opinion.

Applications

- Movie Review Analysis
- Customer Feedback Classification
- Social Media Sentiment Analysis
- Product Review Analysis
- Opinion Mining

Future Improvements

- Replace RNN with LSTM or GRU
- Use Pretrained Word Embeddings
- Hyperparameter Tuning
- Deploy as a Web Application
- Use Transformer Based Models such as BERT

Author

Developed as a Natural Language Processing and Deep Learning Project using PyTorch.
