# Amazon Product Sentiment Analysis & Recommendation System

## Overview
This project analyzes customer reviews for the **Huawei Mate 2** to understand user satisfaction. It uses `TextBlob` for NLP and compares its predictions with actual user ratings.

## Key Features
- **Sentiment Scoring:** Classifies reviews into Positive, Negative, and Neutral.
- **Accuracy Check:** Compares TextBlob polarity with the `True_Sentiment` derived from star ratings.
- **Root Cause Analysis:** Extracts frequent keywords from negative reviews (e.g., battery, screen, software).
- **Automated Recommendations:** Suggests improvements based on identified issues.

## Visualization
The project includes a bar chart showing the distribution of sentiments for the selected product.

## Dataset
The dataset used in this project is the **Amazon Unlocked Mobile Reviews**, which contains over 400,000 reviews.
- You can download it from Kaggle: (https://www.kaggle.com/datasets/PromptCloudHQ/amazon-reviews-unlocked-mobile-phones)
