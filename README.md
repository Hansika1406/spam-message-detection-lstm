# Spam Message Detection Using LSTM

## Project Overview
This project uses Natural Language Processing (NLP) and an LSTM neural network to classify SMS messages as spam or legitimate (ham).

## Objectives
- Analyze and preprocess SMS messages.
- Convert text into numerical sequences using tokenization and padding.
- Build and train an LSTM neural network.
- Evaluate the model using accuracy, precision, recall, F1-score, and a confusion matrix.
- Predict whether new SMS messages are spam or ham.

## Technologies Used
- Python
- Jupyter Notebook
- TensorFlow / Keras
- Pandas and NumPy
- Matplotlib
- Scikit-learn

## Dataset
SMS Spam Collection Dataset  
Source: https://archive.ics.uci.edu/dataset/228/sms+spam+collection

## Results
The current model achieved **97.68% test accuracy** on 1,034 test messages. Spam recall was approximately 83.2%.

## How to Run
1. Install dependencies from `requirements.txt`.
2. Open `spam_detection_lstm.ipynb` in Jupyter Notebook.
3. Run the notebook cells in order.

