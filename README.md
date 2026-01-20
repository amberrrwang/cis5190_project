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

- **Final Model: BERT**  
  RoBERTa showed signs of overfitting despite high training accuracy. BERT was chosen for its more stable test performance and stronger generalization.

- **SVM vs BERT Trade-off**  
  With extensive feature engineering, SVM achieved accuracy comparable to BERT, but its performance was highly sensitive to vectorization and feature choices.

- **Robustness of Contextual Embeddings**  
  BERT’s contextual embeddings capture semantic differences across varying text inputs, making it more robust for headline classification tasks with high linguistic variability.

- **Interpretability vs Stability**  
  SVM provides greater interpretability through explicit features, while BERT reduces manual preprocessing and offers more consistent performance.
