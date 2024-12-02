# Stock-Price-Prediction-Using-Sentiment-Analysis

This project uses social media sentiment analysis (Twitter, Reddit, Telegram) to predict stock price movements. It combines natural language processing (NLP) techniques with machine learning models.

Table of Contents
1.Features
2.Setup Requirements
3.Running the Code
4.Usage
5.Evaluation

Features:
->Scraping social media data for stock-related content.
->Sentiment analysis using NLP models.
->Predicting stock price movements using LSTMs.
->Visualizations of sentiment trends and predictions.

Setup Requirements:
Dependencies:
The project requires the following Python libraries:
->numpy
->pandas
->matplotlib
->seaborn
->tweepy
->scikit-learn
->tensorflow
->nltk
->beautifulsoup4
->PRAW (for Reddit scraping)
->telethon (for Telegram scraping)
Ensure Python version 3.8 or later is installed.

Running the Code:

Step 1: Data Scraping
python scrape_data.py

Step 2: Preprocessing
python preprocess_data.py

Step 3: Train the Model
python train_model.py

Step 4: Evaluate and Predict
python predict_stock.py

Usage:
->Collect social media data for specific stocks or markets.
->Process the data and train the LSTM model.
->Evaluate the model and analyze its performance.

Evaluation:
Metrics include accuracy, precision, recall, F1-score, and loss.
Visualization of results is saved in the repository.
