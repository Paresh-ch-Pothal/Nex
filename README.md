# 🧠 Next Word Predictor
The Next Word Predictor is a deep learning-based natural language processing (NLP) model designed to predict the most likely next word given a sequence of input words. This project demonstrates how sequence modeling and neural networks, particularly Recurrent Neural Networks (RNNs) or LSTM (Long Short-Term Memory) models, can be trained on a corpus of text to understand language patterns and generate coherent continuations.

🔍 Project Overview
This project takes a seed text input (e.g., "The sun is") and iteratively predicts the next word one by one to build a longer, meaningful sentence. It uses tokenization and padding to preprocess input text and leverages a trained deep learning model to generate predictions. The model is trained on a large corpus of text data to learn the statistical patterns of word sequences.

The key features include:

Text tokenization and sequence generation

Data preprocessing and padding for consistent input shape

Neural network-based model (e.g., LSTM or GRU)

Iterative prediction of next words based on seed input

Vocabulary mapping from word indices back to actual words

🧾 Dataset Used
The model is trained using the "Quora Questions Pairs" dataset, which contains over 400,000 question pairs from Quora. Although primarily designed for duplicate question detection, this dataset provides a rich variety of natural language structures suitable for language modeling.

📂 Kaggle Dataset Link:
https://www.kaggle.com/datasets/tusharpotdar/next-word-predictor-dataset?select=my_sentences_new.txt

📌 Applications
Text autocompletion tools

Chatbots and conversational AI

Writing assistants

Educational tools for language learning

Any system requiring predictive text generation

