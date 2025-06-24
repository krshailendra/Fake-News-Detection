# 📰 Fake News Classification using NLP, Machine Learning & Deep Learning (LSTM)

## 📌 Project Overview

Fake news refers to deliberately misleading or f# 📰 Fake News Classification using NLP, Machine Learning & Deep Learning (LSTM)

## 📌 Project Overview

Fake news refers to deliberately misleading or false information presented as news. This project focuses on detecting such fake news headlines using various Natural Language Processing (NLP) techniques, machine learning models, and deep learning architectures like Bi-directional LSTM.

The goal is to identify patterns in news headlines that can distinguish fake news (often clickbait) from genuine journalism. The project involves building models that learn from labeled data to automatically classify news headlines as real or fake.

---

## 🧠 Project Components

### 1. **Exploratory Data Analysis & Preprocessing**
Performed in the notebook `Fake_news_preprocessing.ipynb`, this step involves:
- Cleaning and standardizing text
- Visualizing word frequencies and class distributions
- Tokenization, stopword removal, and label encoding

### 2. **Analysis & Feature Engineering**
Detailed in `fake news Analysis.ipynb`, this section explores:
- N-gram patterns
- Word clouds for fake and real headlines
- Statistical feature extraction
- Insights into how fake and real headlines differ linguistically

### 3. **Deep Learning with LSTM**
Implemented in `fake news headline LSTM.ipynb`:
- A Bi-directional LSTM model is trained on the processed text
- Embedding layers and sequence padding used for input
- Model is evaluated using accuracy and confusion matrix

---

## 📁 Dataset Overview

The dataset used is the **ISOT Fake News Dataset**.  
You can download it from this link:  
🔗 [ISOT Fake News Dataset (Google Drive)](https://drive.google.com/file/d/1IoTRrJNDJqvaG3hnUpnHQyGvPAJbO8y3/view)

It consists of two CSV files:

- `True.csv`: Contains ~12,600 real articles from **Reuters.com**
- `Fake.csv`: Contains ~12,600 fake articles from unreliable sources listed by **PolitiFact** and **Wikipedia**

Each article includes:
- `title` (headline)
- `text` (article body)
- `label` (`True` or `Fake`)
- `date` (optional)

Most articles focus on political and world news.

---

## 🌐 Insights from Word Clouds

- **Fake News** frequently uses terms like: `Video`, `Obama`, `Hillary`, `Trump`, `Republican`
- **Real News** commonly includes: `Trump`, `White House`, `North Korea`, `China`

These patterns offer linguistic cues that assist in model classification.

---
alse information presented as news. This project focuses on detecting such fake news headlines using various Natural Language Processing (NLP) techniques, machine learning models, and deep learning architectures like Bi-directional LSTM.

The goal is to identify patterns in news headlines that can distinguish fake news (often clickbait) from genuine journalism. The project involves building models that learn from labeled data to automatically classify news headlines as real or fake.

Da

---

## 🧠 Project Components

### 1. **Exploratory Data Analysis & Preprocessing**
Performed in the notebook `Fake_news_preprocessing.ipynb`, this step involves:
- Cleaning and standardizing text
- Visualizing word frequencies and class distributions
- Tokenization, stopword removal, and label encoding

### 2. **Analysis & Feature Engineering**
Detailed in `fake news Analysis.ipynb`, this section explores:
- N-gram patterns
- Word clouds for fake and real headlines
- Statistical feature extraction
- Insights into how fake and real headlines differ linguistically

### 3. **Deep Learning with LSTM**
Implemented in `fake news headline LSTM.ipynb`:
- A Bi-directional LSTM model is trained on the processed text
- Embedding layers and sequence padding used for input
- Model is evaluated using accuracy and confusion matrix

---

## 📁 Dataset Overview

The dataset used is the **ISOT Fake News Dataset**, consisting of two CSV files:

- `True.csv`: Contains ~12,600 articles from **Reuters.com**
- `Fake.csv`: Contains ~12,600 articles from unreliable sources listed by **PolitiFact** and **Wikipedia**

Each article includes:
- `title` (headline)
- `text` (article body)
- `label` (`True` or `Fake`)
- `date` (optional)

Most articles focus on political and world news.

---

## 🌐 Insights from Word Clouds

- **Fake News** frequently uses terms like: `Video`, `Obama`, `Hillary`, `Trump`, `Republican`
- **Real News** commonly includes: `Trump`, `White House`, `North Korea`, `China`

These patterns offer linguistic cues that assist in model classification.

---

