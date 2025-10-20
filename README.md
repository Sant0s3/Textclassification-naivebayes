# Text Classification with Multinomial Naive Bayes

This project implements a **text classification system** using **Multinomial Naive Bayes** combined with a **CountVectorizer** for feature extraction. The model predicts categories for text data based on n-grams.

---

## Features

- Converts text into **bag-of-words** representation using `CountVectorizer`.
- Supports **unigrams and bigrams** (ngram_range = 1,2) to capture word sequences.
- Trains a **Multinomial Naive Bayes** classifier on labeled text data.
- Evaluates performance with a **classification report** including precision, recall, and F1-score.
- Can save and load the trained model for reuse.

---# 📰 News Category Classification with Multinomial Naive Bayes

This project implements a **text classification system** to predict news categories based on headlines using the **News Category Dataset** from Kaggle.

---

## 📊 Dataset Overview

The dataset contains approximately **210,000 news headlines** from 2012 to 2022, sourced from HuffPost. It includes 41 categories such as:

- World
- Politics
- Technology
- Sports
- Entertainment
- Science
- Health

Each entry comprises:

- `headline`: The news headline.
- `category`: The corresponding news category.

Dataset link: [News Category Dataset on Kaggle](https://www.kaggle.com/datasets/rmisra/news-category-dataset)

---

## ⚙️ Requirements

Install the required Python libraries:

```bash
pip install scikit-learn pandas joblib


## Requirements

- Python 3.8+
- Libraries:
```bash
pip install scikit-learn pandas joblib
