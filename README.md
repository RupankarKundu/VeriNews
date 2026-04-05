# VeriNews
VeriNews is an AI-powered fake news detection system that analyzes text and news article URLs using NLP and a machine learning model to classify content as real or fake, providing confidence scores and probability insights through a user-friendly web interface.
# 🧠 VeriNews — Fake News Detection System

> AI-powered system to detect whether news is **REAL or FAKE** using Machine Learning and NLP.

---

## 🚀 Overview

**VeriNews** is a full-stack application that analyzes news content from:
- 📝 Text input (headlines, paragraphs)
- 🌐 URLs (automatic article extraction)

It uses Machine Learning to provide:
- Prediction (REAL / FAKE)
- Confidence score
- Probability breakdown

---

## 🏗️ Project Structure
VeriNews/
│
├── app.py # Flask backend API
├── predict.py # Prediction logic
├── train.py # Model training script
├── index.html # Frontend UI
├── requirements.txt # Dependencies
├── models/ # Generated after training
└── WELFake_Dataset.csv # Dataset

---

## ⚙️ Requirements

- Python 3.8+
- pip

---

## 📥 Setup Instructions

### 1️⃣ Clone the Repository

```bash
Download dataset from:

https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification

Place this file in the project folder:

WELFake_Dataset.csv
🧠 Train the Model
python train.py

This will generate:

models/pipeline.pkl
models/meta.json
▶️ Run the Application
python app.py
If you like this project, give it a ⭐
