# Sentiment Analysis of McDonald's Reviews

## Overview
This project implements sentiment analysis using Python to evaluate customer reviews for McDonald's, utilizing the VADER (Valence Aware Dictionary and sEntiment Reasoner) library. Sentiment analysis, a crucial part of Natural Language Processing (NLP), categorizes text into positive, negative, or neutral sentiments, providing insights into public opinion and customer feedback.

## Dataset
The analysis is based on the **McDonald_s_Reviews.csv** dataset from Kaggle, which contains various customer reviews, their ratings, and review timestamps.

## Steps Involved
1. **Library Import**: Required libraries, including VADER for sentiment analysis, are imported.
2. **Data Loading**: The dataset is loaded and inspected.
3. **Data Preparation**: A new DataFrame is created with the relevant columns: `review_time`, `review`, and `rating`.
4. **Data Cleaning**:
   - Special characters are removed from the reviews.
   - The `rating` column is converted to numerical values for analysis.
   - The `review_time` column is transformed into a datetime format for better analysis.
5. **Sentiment Analysis with VADER**:
   - VADER is applied to assess the sentiment of each review.
   - Sentiment scores (positive, negative, neutral, compound) are calculated.
   - Sentiment tags (Positive, Negative, Neutral) are assigned based on the compound score.

## Results
The analysis reveals that a significant majority of customers express positive sentiments regarding their experiences with McDonald's. While VADER's sentiment classification may not be 100% accurate, it demonstrates a high degree of reliability in predicting sentiment.

## Conclusion
This project showcases the effectiveness of sentiment analysis in understanding customer attitudes through unstructured textual data. The insights derived can be valuable for enhancing customer service and improving business strategies.

