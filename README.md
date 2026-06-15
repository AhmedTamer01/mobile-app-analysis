# Multilingual Mobile App Review Analysis 📱💬

A comprehensive data analysis pipeline built to extract actionable insights from multilingual mobile app reviews, completed as part of the Samsung Innovation Campus (SIC) Capstone Project.

## 🚀 Project Overview

Understanding user feedback is critical for app developers. However, analyzing global applications means dealing with reviews written in dozens of different languages. This project tackles the challenge of parsing, translating, and analyzing a massive dataset of multilingual app reviews to uncover user sentiment and feature requests.

## ⚙️ Methodology

1. **Data Cleaning & Preprocessing**: 
   - Loaded the `multilingual_mobile_app_reviews_2025.csv` dataset.
   - Dropped irrelevant identifiers (like `user_id` and `review_id`) to focus purely on the text and metadata.
   - Cleaned text using regex to remove emojis, URLs, and special characters.
2. **Translation Pipeline**:
   - Implemented an automated translation layer utilizing `deep-translator` to convert all non-English reviews into a unified English format for consistent NLP processing.
3. **Sentiment Analysis & NLP**:
   - Counted word frequencies using `collections.Counter` to identify the most common user complaints and praises.
   - Analyzed correlations between app ratings and specific keywords (e.g., "crash", "slow", "amazing").
4. **Data Visualization**:
   - Built highly visual dashboards using Seaborn and Matplotlib to present the sentiment distributions, rating trends, and common phrases.

## 🛠️ Tech Stack & Libraries Used

- **Data Handling:** Pandas, NumPy
- **Natural Language Processing:** Deep-Translator, Regex (`re`), NLTK
- **Data Visualization:** Matplotlib, Seaborn

## 📈 Key Outcomes

- Successfully mapped user sentiment across multiple languages to unified metrics.
- Identified the core features driving 1-star vs 5-star reviews.
- Provided actionable data-driven recommendations for app developers to improve user retention.

---
*This repository is part of my AI Engineer / Data Scientist Portfolio.*
