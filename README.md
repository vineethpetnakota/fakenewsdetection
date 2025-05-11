# 📰 Fake News Detection using Machine Learning

This project aims to detect fake news articles using machine learning models. With the rise of misinformation across digital platforms, especially social media, automating the detection of fake news has become essential for maintaining credible public discourse.

## 📌 Project Overview

The objective of this project is to develop and evaluate multiple machine learning models that classify news articles as **real** or **fake**. We explore different textual and metadata features to train these models for accurate prediction and comparison.

## 🧠 Models Used
- Logistic Regression
- Random Forest
- Gradient Boosting (XGBoost)
- Decision Tree Classifier

## 🗃️ Dataset
- Total articles: ~10,000
- Labels: `Real` or `Fake`
- Source: Kaggle dataset ([Fake News Detection](https://www.kaggle.com/code/therealsampat/fake-news-detection/notebook))

## ⚙️ Methodology

### 1. Data Preprocessing
- **Cleaning**: Removed duplicates and irrelevant columns
- **Feature Engineering**: Combined real and fake datasets; extracted word frequencies, sentiment, etc.
- **Vectorization**: Applied TF-IDF to convert text into numerical format
- **Splitting**: 90% training and 10% testing

### 2. Model Training and Testing
- Trained four ML models using supervised learning
- Evaluated based on **accuracy**, **precision**, **recall**, and **F1-score**

## 📈 Results

| Model              | Accuracy       |
|-------------------|----------------|
| Logistic Regression | 98.69%        |
| Random Forest       | 99.14%        |
| Gradient Boost      | 99.64%        |
| Decision Tree       | 99.64%        |

📌 **Best Performers**: Gradient Boost & Decision Tree

## 🔍 Future Enhancements
- Integrate **Named Entity Recognition (NER)** to analyze references and context
- Employ **Emotion Detection** to identify exaggerated sentiment
- Explore **LSTM** and **BERT** for advanced NLP understanding
- Apply real-time scraping and prediction of current news articles

## 🧾 References
1. Zhou & Zafarani (2020) - ACM Computing Surveys  
2. Conroy, Rubin, & Chen (2015) - ASIS&T  
3. [Kaggle Notebook: Fake News Detection](https://www.kaggle.com/code/therealsampat/fake-news-detection/notebook)  
4. Shu et al. (2017) - SIGKDD Explorations  
5. IEEE: Fake News Detection (2018)
