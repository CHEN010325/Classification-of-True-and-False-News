# 📰 Fake News Classifier

## 📌 Project Overview

### 🎯 Objective
The goal of this project is to detect fake news articles based on their content. This is a text classification task that involves distinguishing between real and fake news using natural language processing (NLP) techniques.

### 💡 Motivation
With the rapid development of artificial intelligence and digital media, the spread of misinformation and fake news has become a significant social problem. These fake stories can be deliberately used to manipulate public opinion, disrupt social harmony, and affect democratic processes.

This project aims to leverage NLP models to build an effective tool for detecting and classifying fake news articles automatically.

---

## 📂 Dataset Description

The dataset used in this project consists of two CSV files:

- `Fake.csv` – contains **23,502** fake news articles  
- `True.csv` – contains **21,417** real news articles  

Each file contains the following columns:

- **Title**: The headline of the article  
- **Text**: The full body of the article  
- **Subject**: The topic category of the article  
- **Date**: The publication date  

🔗 You can access the dataset here: [insert link]

---

## 📈 Model Performance

Our fake news classifier achieved an **accuracy close to 100%** on the test set, demonstrating its high effectiveness in distinguishing between real and fake news articles.

To ensure the reliability of this result, we:
- Properly shuffled and split the dataset to avoid data leakage
- Evaluated additional metrics such as **precision**, **recall**, and **F1-score**
- Analyzed the **confusion matrix** to ensure balanced classification performance

While the results are promising, further evaluation on external datasets is recommended to validate generalization performance.

---
## 🛠️ GloVe download address
https://nlp.stanford.edu/data/glove.6B.zip

## 🛠️ Download the specified repository to replicate the results

- numpy==1.23.3
- pandas==2.2.3
- tensorflow==2.10.0
- scikit-learn==1.6.1
- nltk==3.9.1
- seaborn==0.13.2
- matplotlib==3.9.4
- wordcloud==1.9.4

---

## 🚀 How to Run

run to real-vs-fake-news-100-accuracy.ipynb

## Result

Train Accuracy : 99.86 %
Test Accuracy  : 99.88 %
![image](https://github.com/user-attachments/assets/1748a3d8-f88e-4a2b-a5e0-c40ec06fd296)
