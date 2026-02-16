# 📰 Fake News Detection System  
### Machine Learning + Gemini AI Powered News Verification

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Flask](https://img.shields.io/badge/Framework-Flask-black?logo=flask)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![Google Gemini](https://img.shields.io/badge/AI-Gemini-purple)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Overview

A Machine Learning based Fake News Detection Web Application that classifies news as **Fake** or **Real** using multiple ML models combined with **Google Gemini AI verification** and explanation system.

The final result is generated using an **Ensemble Voting Mechanism** for improved reliability and accuracy.

---

## 🎯 Project Motivation

With the rapid growth of digital media, misinformation spreads quickly and influences public perception.

This project aims to:
- Detect fake news using ML models
- Improve reliability through ensemble voting
- Provide AI-based explanation
- Create a simple and interactive web interface

---

## 🧠 Models Used

- Logistic Regression  
- Random Forest  
- Gradient Boosting  
- Decision Tree  
- Google Gemini AI (Additional Verification)

📌 Feature Extraction: **TF-IDF Vectorization**

📌 Final Decision: **Majority Voting (5 total votes)**

---

## 📊 Model Accuracy

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 95% |
| Random Forest | 96% |
| Gradient Boosting | 95% |
| Decision Tree | 94% |
| Final Ensemble Accuracy | 95% |


---

## 📁 Dataset

The dataset used for training is available here:

🔗 [Download Dataset (CSV)](https://drive.google.com/drive/folders/1NQLass_h1b9LKdduAsI1DISm91s7hzJO?usp=sharing)


Dataset contains:
- News Title
- News Text
- Label (Fake / Real)

---

## ⚙️ How It Works

1. User enters news text.
2. Text cleaning & preprocessing.
3. TF-IDF vectorization.
4. ML models make predictions.
5. Gemini AI verifies content.
6. Final result generated using voting.
7. Confidence score displayed.

---

