# BTC_prediction_by_tweets

## Overview  
This project explores how social-media sentiment (specifically tweets) can be used to predict the price movement of Bitcoin (BTC). It combines sentiment analysis of tweet data with machine learning models to forecast whether BTC will move up or down (classification) or estimate its numeric value (regression).

## Objectives  
- Collect tweet data relevant to Bitcoin (e.g., keywords, hashtags, tweets from high-follower accounts)  
- Perform sentiment and feature extraction from the tweet dataset  
- Integrate the tweet-derived features with historical BTC price data  
- Build and evaluate machine learning models to:  
  - **Classify** future BTC price movement (up/down)  
  - **Regress** future BTC price values using sentiment features  
- Analyze the predictive value of social sentiment relative to standard market features  

## Structure  
- `DataSet.ipynb` — Data collection and preprocessing (tweet fetching, cleaning, feature engineering)  
- `dataset_with_high_followers.ipynb` — Variant of preprocessing focusing on tweets from high-follower accounts  
- `Regression_with_vader.ipynb` — Regression modelling using VADER sentiment or similar sentiment tools  
- `Binary_Classification.ipynb` — Classification modelling of BTC direction (up/down)  
- `README.md` — This file  

## Usage  
1. Clone the repository:  
   ```bash
   git clone https://github.com/robinjmf/BTC_prediction_by_tweets.git
