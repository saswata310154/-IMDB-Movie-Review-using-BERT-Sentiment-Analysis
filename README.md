# -IMDB-Movie-Review-using-BERT-Sentiment-Analysis
NLP project on   IMDB  Movie Review using BERT-Sentiment-Analysis 
# BERT Sentiment Analysis on Movie Reviews

This project implements a **BERT-based sentiment classifier** fine-tuned on the IMDb movie review dataset using Hugging Face Transformers.

## 📌 Project Objective
To classify movie reviews as **positive or negative** using a pre-trained BERT model and understand the complete fine-tuning pipeline.

## 🧠 Model Used
- bert-base-uncased
- Binary classification (Positive / Negative)

## 📂 Dataset
- IMDb Movie Reviews (Hugging Face)
- 500 sampled reviews for fast training

## ⚙️ Project Pipeline
1. Dataset loading
2. Text preprocessing
3. BERT tokenization
4. Train–validation split
5. Model fine-tuning
6. Evaluation (Accuracy, Confusion Matrix)

## 📊 Results
- Validation Accuracy: ~85–90%
- Stable loss convergence

## 🛠️ Technologies Used
- Python
- PyTorch
- Hugging Face Transformers
- Scikit-learn
- Google Colab

## ▶️ How to Run
```bash
pip install -r requirements.txt
