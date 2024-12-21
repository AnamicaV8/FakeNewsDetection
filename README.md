# FakeNewsDetection
Detecting and classifying fake news using advanced deep learning models.
# Fake News Detection and Classification

## Introduction
Fake news has become a global issue, influencing public opinion, polarizing society, and disrupting economic stability. This project leverages deep learning to identify and classify fake news effectively.

## Problem Statement
Misinformation spreads rapidly, manipulating emotions and contributing to societal and economic harm. Our goal is to develop an accurate and scalable system to detect fake news using advanced AI methods.

## Methods Used
1. **Data Preparation**: Text cleaning, feature engineering, tokenization, and splitting data into train, validation, and test sets.
2. **Models Implemented**:
   - Baseline: Multi-Layer Perceptron (Accuracy: 94.99%)
   - LSTM Model (Accuracy: 96.25%)
   - Transformer Encoder (Accuracy: 97.37%)
3. **Evaluation**: Models were compared based on accuracy and loss metrics.

## Results
The Transformer Encoder model achieved the highest accuracy, highlighting the importance of sequential dependencies for fake news detection.

## Future Directions
- Enhance dataset with edge cases to handle misclassifications.
- Integrate external features like publication sources.
- Improve interpretability using techniques like SHAP.
