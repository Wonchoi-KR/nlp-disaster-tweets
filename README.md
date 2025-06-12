# NLP Disaster Tweets

This is a two-week deep dive into Kaggle’s ["Natural Language Processing with Disaster Tweets"](https://www.kaggle.com/competitions/nlp-getting-started) competition.

This project follows a structured learning path:
- Week 1: EDA, text cleaning, TF-IDF, Logistic Regression, CV
- Week 2: Transformer fine-tuning (DistilBERT), error analysis, ensembling
- Goal: Build a NLP pipeline from scratch

## Project overview
- **Objective** 
  - Classify tweets as "disaster" vs. "non-disaster"
- **Data** 
   - `train.csv` (7,613 tweets, 5 columns: `id`, `text`, `location`, `keyword`, `target`)  
   - `test.csv` (3,263 tweets)  
- **Learning Schedule**  
  - Day 1: EDA & Feature Exploration
  - Day 2: Comparing three different data cleaning pipelines; TF-IDF + Logistic Regression model; baseline LB 0.79711
  - Day 3: Hyperparameter tuning and error analysis; LB score of 0.79037
  - Day 4: Implemented 5-fold stratified CV; blended predictions for new LB score of 0.80110
  - Day 5: Set up Transformer fine-tuning pipeline (DistilBERT); validated setup on a 10% split (Val F1: 0.792).