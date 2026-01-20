# Classification of News Headlines

This is a machine learning project for classifying news headlines into predefined categories using natural language processing (NLP) techniques and supervised learning models.

---

## Project Overview

The goal of this project is to build a text classification pipeline that automatically assigns a category to a given news headline. The project was completed as part of the CIS 5190 course and demonstrates an end-to-end NLP workflow, including data preprocessing, feature extraction, model training, and evaluation.

---

## Methodology

- Clean and preprocess raw headline text (lowercasing, tokenization, stop-word removal)
- Convert text into numerical representations using Bag-of-Words and TF-IDF
- Train supervised machine learning models such as Naive Bayes, Logistic Regression, and Support Vector Machines (SVM)
- Evaluate model performance using standard classification metrics

---

## Key Findings

- TF-IDF feature representations consistently outperformed simple Bag-of-Words features by better capturing the importance of informative words in headlines
- Linear models such as Logistic Regression and Support Vector Machines achieved higher and more stable performance than Naive Bayes across categories
- Model performance varied by category, with confusion occurring more frequently between semantically similar news topics
- Feature engineering and data preprocessing had a significant impact on final model performance, highlighting the importance of careful text normalization
