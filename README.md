# README

**Name:** P. MOHAN KUMAR  
**Company:** CODTECH IT SOLUTIONS  
**ID:** CT12DS2585  
**Domain:** Deep Learning  
**Duration:** Dec 2024 – Jan 2025  
**Mentor:** NEELA SANTHOSH  

## Overview of the Project  

### Project: SENTIMENT ANALYSIS USING LSTM ON IMDB DATASET  
![Screenshot](https://github.com/MOHAN1665/CODTECH-Task2/blob/main/image.png)

### Objective  
The objective of this project is to build a Long Short-Term Memory (LSTM) model for sentiment analysis on the IMDB movie reviews dataset. The model predicts whether a review is positive or negative based on the textual input.  

### Key Activities  
- **Data Preprocessing**:  
  - Limited vocabulary to the top 10,000 most common words.  
  - Padded sequences to a fixed length of 500 for uniform input.  
- **Model Architecture**:  
  - Embedding layer to represent words in a dense vector space.  
  - LSTM layer for capturing sequential patterns in text.  
  - Dense layer with a sigmoid activation for binary classification.  
- **Model Training**: Trained for 5 epochs with a batch size of 64.  
- **Evaluation**: Assessed model accuracy on the test set.  

### Technologies Used  
- **Python**: Primary programming language for implementation.  
- **Keras**: Deep learning framework for building and training the LSTM model.  
  - **Embedding Layer**: To convert words into dense vector representations.  
  - **LSTM**: For capturing sequential relationships in text data.  
  - **Binary Cross-Entropy Loss**: For binary classification tasks.  

### Results  
- **Accuracy**: Achieved high accuracy on the IMDB test dataset, demonstrating the effectiveness of LSTM for sentiment analysis.  

### Key Insights  
- **Sequence Length**: Padding sequences to a fixed length ensures consistent input dimensions for the LSTM.  
- **Vocabulary Limitation**: Restricting to the top 10,000 words balances computational efficiency and model performance.  
- **Model Performance**: LSTM captures temporal dependencies, making it effective for text classification tasks.  

This project highlights the power of LSTM networks in handling sequential data and showcases how deep learning can be applied for sentiment analysis in real-world datasets.  
