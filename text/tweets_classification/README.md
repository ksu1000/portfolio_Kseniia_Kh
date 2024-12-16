# Disaster Tweet Classification

## Overview
This project was developed as part of the Kaggle competition [NLP - Getting Started](https://www.kaggle.com/competitions/nlp-getting-started), where the goal is to predict whether a tweet is about a real disaster or not. This is a binary classification problem that uses textual data as input. The key evaluation metric is the **F1 score**.

**Rank**: As of writing this notebook, the model is ranked **58th out of 924** in the competition leaderboard.

## Highlights
- **Model**: Fine-tuned **DistilBERT Pretrained Model**
- **Techniques**:
  - Transfer learning using **transformers** from the Hugging Face library.
  - Using **Hidden States** from DistilBERT with **Logistic Regression** for comparison.

## Dataset
- **Features**: Text data with tweets.
- **Target**: Labels indicating whether the tweet is about a disaster (1) or not (0).

## Approach
- The text data was cleaned and tokenized using DistilBERT's tokenizer.
- Fine-tuning was performed on a pretrained **DistilBERT** model from the Hugging Face library for text classification.
- The F1 score was the primary evaluation metric, with a focus on improving recall for the minority class.

## Results
- **F1 Score**: 0.8436
- **Accuracy**: 85%
- **Leaderboard Position**: 58/924

## Experience
This is my first time working with Large Language Models (LLMs).
