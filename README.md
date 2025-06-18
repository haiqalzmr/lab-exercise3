# 🧠 Lab Exercise 3 – Supervised Machine Learning (Sentiment Analysis)

This project is part of **CDS-6344: Social Media Computing** coursework.

It addresses **Lab Exercise 3 – Question (c)**:  
> **Implementation of at least one supervised machine learning algorithm**  
> to classify sentiment from social media text.

---

## 📌 Objective

To build a **supervised machine learning model** that classifies **airline-related tweets** into one of three sentiment categories:
- **Positive**
- **Neutral**
- **Negative**

---

## 🗂 Dataset

**📊 Twitter US Airline Sentiment Dataset**  
Source: [Kaggle - crowdflower/twitter-airline-sentiment](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)  
Accessed in notebook via:

```python
!pip install kagglehub --quiet
import kagglehub

dataset_path = kagglehub.dataset_download("crowdflower/twitter-airline-sentiment")
