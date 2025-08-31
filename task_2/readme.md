# Task 2 - Sentiment Analysis

## 📌 Sentiment Analysis Report

### 1. Problem Statement
In today’s digital world, social media platforms generate vast amounts of user opinions daily. Understanding these opinions is crucial for businesses, policymakers, and researchers to gauge public perception.  
This project focuses on performing sentiment analysis on tweets to categorize them into **Positive, Negative, or Neutral sentiments** and identify the most frequent words associated with each sentiment.

---

### 2. Overview
The objective of this project is to analyze tweets, classify them based on sentiment, and visualize the common keywords using word clouds and statistical techniques.  
By doing so, we can uncover insights about **public opinion** and identify patterns in online discussions.

---

### 3. Tech Stack & Tools Used

#### 🔹 Programming Language
- Python  

#### 🔹 Libraries & Frameworks
- **pandas** → Data preprocessing and cleaning  
- **matplotlib** → Visualization of sentiment distribution   
- **VADER (Valence Aware Dictionary for Sentiment Reasoning)** → Sentiment classification  

#### 🔹 Dataset
- CSV file containing tweets and sentiment labels  

---

### 4. Methodology
1. **Data Cleaning** → Removed missing values and ensured only valid text entries were analyzed.  
2. **Sentiment Classification** → Used VADER Sentiment Analyzer to classify text into *Positive, Negative, and Neutral* categories.  
3. **Visualization** →  
   - Plotted distribution of sentiments.  
---

### 5. Results & Insights
- Most tweets were **Positive**, showing an overall optimistic sentiment trend.  
- **Positive tweets** focused on words like *love, great, good, thanks*.  
- **Negative tweets** were dominated by words such as *bad, hate, problem, worst*.  
- **Neutral tweets** contained general words with less emotional intensity.  
---

### 6. Conclusion
This project successfully demonstrated how sentiment analysis can extract meaningful insights from social media data.  
The combination of **VADER sentiment analysis, visualization techniques** provided a clear understanding of the dataset.  

Overall, the analysis revealed that **Positive sentiments outweighed Negative ones**, indicating a generally favorable online environment in the dataset.

---

## ❓ Questions and Answers

**Q1. What categories of sentiments were analyzed?**  
➡️ Positive, Negative, and Neutral.  

**Q2. Which sentiment had the highest number of tweets?**  
➡️ Positive tweets were the majority, followed by Neutral, then Negative.  

**Q3. What are the most common words used in positive tweets?**  
➡️ Words like *good, love, great, happy, thanks*.  

**Q4. How balanced is the dataset in terms of sentiment distribution?**  
➡️ Slightly imbalanced → Positive tweets dominate, Neutral in the middle, and Negative the least.  

**Q5. What are the most common words used in negative tweets?**  
➡️ Words like *bad, hate, worst, sad, problem*.  
