# 🧠 Resume Matching AI

AI system for matching resumes with job descriptions using NLP techniques and machine learning.

---

## 🚀 Overview

This project automates candidate screening by analyzing resumes and ranking them based on their relevance to a job description.

It combines classical NLP (TF-IDF + SVM) with deep learning (DistilBERT) to improve matching accuracy.

---

## ⚙️ Features

- Resume preprocessing and cleaning  
- TF-IDF vectorization  
- SVM classification model  
- DistilBERT fine-tuning  
- Similarity scoring  
- Candidate ranking  

---

## 🏗️ Project Structure
projet_final/
│
├── dossier/
│ ├── web_app/
│ ├── cv_test/
│ └── script.ipynb
│
├── models/
│ ├── label_encoder.pkl
│ ├── svm_model.pkl
│ ├── tfidf_vectorizer.pkl
│ │
│ ├── distilbert-base-uncased/
│ └── distilbert_checkpoints/
│
└── README.md

---

## 🧠 Models

### 🔹 Classical ML
- TF-IDF Vectorizer
- Support Vector Machine (SVM)
- Label Encoder

### 🔹 Deep Learning
- DistilBERT (pretrained)
- Fine-tuned checkpoints

---

## 🛠️ Installation

```bash
git clone https://github.com/maryem2104/resume-matching-ai.git
cd resume-matching-ai
