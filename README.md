# Text-based Emotion Detection AI

This project detects emotions from text input using Natural Language Processing (NLP) and machine learning. It classifies emotions such as happy, sad, angry, and others by analyzing the text content.

## Features

- Detects multiple emotions from user-provided text
- Uses NLP techniques for text preprocessing and cleaning
- Implements machine learning models for emotion classification
- Runs completely locally without relying on external APIs
- Provides a demo and working model saved for reuse

## Technologies Used

- Python  
- NumPy  
- Seaborn (for visualization)  
- NeatText (for text cleaning and preprocessing)  
- Scikit-learn (for training and evaluating ML models)  
- Joblib (for saving/loading trained models)  
- Jupyter Notebook / Google Colab

## Dataset

The dataset used for training contains labeled text samples categorized by emotions such as happy, sad, angry, surprise, fear, and neutral. The text data is cleaned and preprocessed using NeatText before model training.

## How It Works

1. Text data is preprocessed: removing stopwords, special characters, and noise.
2. Features are extracted from the cleaned text (e.g., TF-IDF or Count Vectorizer).
3. A machine learning classifier (such as Random Forest, SVM, or Logistic Regression) is trained on the labeled dataset.
4. The trained model is saved using joblib for later use.
5. Users can input text to predict the corresponding emotion based on the model.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Iqra2003/Emotion-Detection-AI.git
