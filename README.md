# ReviewInsights — Customer Review Sentiment Analysis

ReviewInsights is a simple project that analyzes Amazon food reviews to understand customer sentiment. It classifies reviews as positive, negative, or neutral using both a rule-based approach and a deep learning model.

## Dataset
Amazon Fine Food Reviews (Kaggle)

## Features
- Text preprocessing (tokenization, POS tagging, NER)
- Sentiment analysis using:
  - VADER (rule-based)
  - RoBERTa (fine-tuned model)
- Performance comparison between models

## Tech Stack
- Python
- NLTK
- Scikit-learn
- Hugging Face Transformers

## Setup

Clone the repository:
```bash
git clone https://github.com/Nabeel-Farooq/ReviewInsights.git
cd ReviewInsights
