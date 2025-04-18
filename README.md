# SHL Grammar Scoring Engine - Model Development Notebook

Overview:
This notebook addresses the SHL Intern Hiring Assessment competition task of building a Grammar Scoring Engine. The goal is to predict MOS Likert Grammar Scores (0-5 range) based on spoken English audio samples. 

Approach:
1. Load and explore the dataset.
2. Extract features from .wav audio files (MFCC, Chroma, Spectral Contrast, Tonnetz).
3. Train a regression model (LightGBM) on the features.
4. Evaluate the model using RMSE and Pearson Correlation.
5. Predict on the test data and prepare a submission file.

Author: DHRUV JAIN
Date: 18-04-2025
