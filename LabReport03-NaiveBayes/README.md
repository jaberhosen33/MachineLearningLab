#  News Classification using Naïve Bayes

A simple Machine Learning project that classifies news articles into **Sports** and **Politics** using the **Naïve Bayes** algorithm.  
The project is implemented in **Python** and is fully **Google Colab compatible**.

---
##  Project Description

This project demonstrates how **Natural Language Processing (NLP)** techniques can be used to classify text data.  
A dataset of 100 news articles is preprocessed, vectorized using **TF-IDF**, and classified using **Multinomial Naïve Bayes**.

---

## Dataset

- **Total samples:** 100  
- **Sports news:** 50 (Label = 0)  
- **Politics news:** 50 (Label = 1)

### Dataset Format (`news_dataset.csv`)
```csv
text,label
The football team won the championship match,0
The government passed a new law,1
---
## Data Preprocessing

Convert text to lowercase

Remove punctuation and numbers

Remove stopwords

Apply stemming

Convert text into numerical form using TF-IDF

Split data into 80% training and 20% testing



