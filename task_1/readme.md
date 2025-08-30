Task 2 - Sentiment Analysis
1. Problem Statement

In today’s digital era, social media platforms like X (formerly Twitter) generate vast amounts of text data where individuals express their opinions freely. Analyzing this content helps in understanding public emotions and opinions. This project focuses on performing sentiment analysis on tweets using VADER (Valence Aware Dictionary for Sentiment Reasoning) to classify them into Positive, Negative, or Neutral sentiments.

2. Overview

The goal of this project is to:

Analyze tweets and categorize them into sentiment classes.

Visualize the overall sentiment distribution.

Identify frequently used words associated with each sentiment category.

By doing so, we uncover trends in public perception and highlight key emotional triggers in online discussions.

3. Tech Stack / Tools Used
Python Libraries

pandas → Data preprocessing and handling the dataset

matplotlib → Visualization of sentiment distribution

WordCloud → Generate word clouds for Positive, Negative, and Neutral sentiments

VADER (NLTK SentimentIntensityAnalyzer) → Sentiment classification of tweets

Dataset

CSV file (x_sentiment_scored.csv) containing tweets and their sentiment scores

4. Methodology

Data Cleaning

Removed missing values

Kept only valid tweet text entries

Sentiment Classification

Applied VADER SentimentIntensityAnalyzer

Classified each tweet into Positive, Negative, Neutral

Visualization

Plotted sentiment distribution using matplotlib

Generated word clouds for each sentiment category

Word Frequency Analysis

Extracted top words for each sentiment (Positive, Negative, Neutral)

5. Results & Insights

Majority of tweets were Positive, indicating an optimistic trend.

Positive tweets → common words included love, good, happy, thanks

Negative tweets → common words included bad, hate, worst, sad

Neutral tweets → contained general non-emotional words.

Word clouds confirmed the dominance of emotionally charged words in Positive and Negative tweets.

6. Applications

Business → Analyzing customer reviews & product feedback

Politics → Understanding public opinion on policies

Healthcare → Tracking mental health-related discussions

Marketing → Measuring customer sentiment and brand perception

7. Conclusion

This project demonstrated how VADER Sentiment Analysis can effectively classify and analyze sentiments in tweets. With visualizations and word frequency analysis, we gained a clearer understanding of public opinion. Overall, the dataset showed a higher proportion of positive sentiments, reflecting a generally favorable discussion trend.

Questions & Answers

Q1. What categories of sentiments were analyzed?
→ Positive, Negative, Neutral

Q2. Which sentiment had the highest number of tweets?
→ Positive sentiment dominated the dataset

Q3. What are the most common words in positive tweets?
→ love, great, good, happy, thanks

Q4. What are the most common words in negative tweets?
→ bad, hate, worst, problem, sad

Q5. How balanced was the dataset?
→ Slightly imbalanced, with more Positive tweets compared to Neutral and Negative.
