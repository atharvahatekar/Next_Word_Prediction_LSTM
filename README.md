# Next Word Prediction Using LSTM

## Overview
This project develops a deep learning model for next-word prediction using Long-Short-Term Memory (LSTM) networks. The model is trained on Shakespeare's "Hamlet," making it a robust application of natural language processing (NLP) and deep learning.

## Features
- **Text-based next-word prediction** using LSTM networks
- **Trained on Shakespeare's "Hamlet"** for complex language understanding
- **Streamlit web application** for real-time predictions
- **Early stopping** to prevent overfitting

## Project Workflow
### 1. Data Collection
- Uses **Shakespeare's "Hamlet"** as the dataset.

### 2. Data Preprocessing
- Tokenization, sequence generation, and padding for uniform input length.
- Splitting data into **training and testing sets**.

### 3. Model Building
- **Embedding layer** for word representations.
- **Two LSTM layers** to capture sequential dependencies.
- **Dense output layer** with **softmax activation** for word prediction.

### 4. Model Training
- Uses **early stopping** to monitor validation loss and stop training when improvement stagnates.

### 5. Model Evaluation
- Evaluates accuracy by testing with example sentences.

### 6. Deployment
- A **Streamlit web app** allows users to input a sequence and predict the next word in real time.
