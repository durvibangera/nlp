# Natural Language Processing

Overview: 
This repository contains multiple end‑to‑end NLP projects and foundational modules like:
1. Spam vs Ham classification
2. Kindle review sentiment analysis
3. NLP basics: stemming, lemmatization, tokenization, stopword removal, etc.

Project 1: Spam‑Ham Classification
- Goal: Build a binary classifier to distinguish spam from legitimate SMS (ham) messages.
- Preprocessing: tokenization, stopword removal, optional stemming/lemmatization
- Feature extraction: BoW, TF‑IDF
- Model: Naive Bayes (MultinomialNB)
- Evaluation metrics: accuracy, precision, recall, F1‑score
- Achieved accuracy: 98.2% with BoW, 83.67% with Tf-IDF

Project 2: Kindle Review Sentiment Analysis
- Goal: Predict sentiment from Kindle product reviews.
- Text preprocessing: cleaning, tokenization, lemmatization
- Vectorization: Bag‑of‑Words, TF‑IDF, Word2Vec embeddings
- Model(s): Naive Bayes (GaussianNB)
- Performance: 57% with BoW, 59% with Tf-IDF, 69% with Word2Vec

NLP Foundation Scripts
- Tokenization
- Stemming (PorterStemmer, SnowBallStemmer)
- Lemmatization (using POS‑tagging + WordNet)
