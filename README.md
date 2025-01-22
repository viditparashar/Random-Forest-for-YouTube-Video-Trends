# YouTube Video Viewership Prediction

This project focuses on analyzing YouTube video data from prominent Indian news channels and predicting viewership using a Random Forest Regressor. R2 Score 0.94

## Table of Contents
- [Download Datasets](#Datasets)
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Results](#results)
- [Acknowledgements](#acknowledgements)
  
## Download Datasets
https://www.kaggle.com/datasets/vidivenivici/youtube-video-analytics-dataset

## Overview
The goal of this project is to understand the factors influencing YouTube video viewership. It involves data scraping, preprocessing, feature extraction, and building a predictive model with an R² score of 0.94 on the test set. There are 3 .ipynb files, FileOne and FileTwo contain a different approach and Final has the final model and output. R2, MAE, and MSE are used for metrics.

## Features
- Scraped video data using the YouTube API.
- Preprocessed text data using NLTK and Googletrans for translation.
- Extracted features with Sentence Transformers, TF-IDF, and sentiment analysis (TextBlob).
- Tried many models, XGBoost, CATBoost, LightGBM, RandomForrest was the best.
- Built a Random Forest Regressor and optimized it using GridSearchCV.
- Explained predictions with SHAP and LIME.
- Visualized insights using Seaborn and Matplotlib, with PCA for dimensionality reduction.

## Technologies Used
- **Programming Language**: Python  
- **Libraries**: pandas, NumPy, NLTK, TextBlob, SentenceTransformer, scikit-learn, SHAP, LIME, Seaborn, Matplotlib  
- **APIs**: YouTube Data API  
- **Tools**: PCA for dimensionality reduction  


## Technologies Used

- **R2 Score**: 0.94 (Test)
- **R2 Score**: 0.90 (Train)

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo.git

