# Netflix-Content-Recommendation-Engine
Netflix Recommendation Engine using different ML Models and giving movie recommendations with a great accuracy

## Overview

This project aims to build a recommendation system for Netflix content based on various models, including SVM with TF-IDF, K Nearest Neighbors, and a hybrid model combining SVM with Cosine Similarity and TF-IDF. The recommendation system helps users discover content similar to their preferences.

## Dataset

The dataset used for this project is sourced from Netflix and contains information about various titles, including their type, director, cast, rating, listed genres, and descriptions. Initial exploratory data analysis (EDA) and feature engineering are performed to understand and preprocess the data.

## Models Implemented

1. **Cosine Similarity & TF-IDF :**
   - Using TF-IDF features based on Cosine similarity values the model is trained.
   - Evaluation metrics such as accuracy and classification report are provided.

2. **Hybrid Model - SVM with Cosine Similarity & TF-IDF:**
   - Combining SVM with Cosine Similarity and TF-IDF for improved recommendations.
   - Evaluation metrics and recommended items are displayed.

3. **K Nearest Neighbors (KNN) with Cosine Similarity:**
   - A KNN classifier is used for recommendation based on cosine similarity.
   - The classification report and accuracy score are presented.

4. **Nearest Neighbors with Cosine Similarity (Unsupervised):**
   - Using unsupervised nearest neighbors to provide recommendations.
   - Classification report, accuracy, F1 score, and recommended items are presented.

5. **Comparison of Models:**
   - Similarity scores for different models are calculated and compared.
   - Models include SVM with TF-IDF, SVM with Cosine Similarity and TF-IDF, KNN, and unsupervised nearest neighbors.

## Requirements

- Python 3.x
- Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn, wordcloud

## Results
The project achieves accurate recommendations by utilizing various models. The comparison section provides insights into the performance of each model, helping to understand their strengths and limitations. The performance of Cosine Similarity & TF-IDF and the Hybrid Model - SVM with Cosine Similarity & TF-IDF was very high in terms of acuuracy as well the similarity of the items recommended.
