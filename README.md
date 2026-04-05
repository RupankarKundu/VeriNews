# VeriNews
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
└── WELFake_Dataset.csv # Dataset (you add this)


---

## ⚙️ Requirements

- Python 3.8+
- pip

---

## 📥 Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/RupankarKundu/VeriNews.git
cd VeriNews
2️⃣ (Optional but Recommended) Create Virtual Environment
python -m venv venv

Activate it:

venv\Scripts\activate   # Windows
source venv/bin/activate # Linux/Mac
3️⃣ Install Dependencies
pip install -r requirements.txt
📊 Dataset Setup (IMPORTANT)

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

Open browser:

http://127.0.0.1:5000
🔍 How It Works
User enters text or URL
If URL → article is extracted
Text is processed using NLP
ML model predicts:
REAL or FAKE
Confidence score
Result displayed in UI
🧩 Features
✔️ Fake news detection using ML
✔️ URL-based article extraction
✔️ Probability-based predictions
✔️ Clean web interface
✔️ Fast Flask API backend
📌 Notes
First run requires training the model
URL extraction may fail for some websites
In such cases, paste text manually
👨‍💻 Author

Rupankar Kundu
GitHub: https://github.com/RupankarKundu

⭐ Support

If you like this project, give it a ⭐

This will generate:

models/pipeline.pkl
models/meta.json
▶️ Run the Application
python app.py
If you like this project, give it a ⭐
