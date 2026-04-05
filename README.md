# 🤖 SuperAI Engineer Season 6 — Mini Hackathon Projects

This repository contains all mini hackathon notebooks submitted as part of the **SuperAI Engineer Season 6** program by Patsapol (Student ID: 602903).

---

## 📁 Project Files

### Hackathon 1 — Thai Public Transport EDA
**File:** `hackathon1_thai_transport_eda.ipynb`

Exploratory Data Analysis on daily ridership data from Thailand's public transportation system, covering ~14 months of records from the Ministry of Transport. The analysis uncovers travel patterns and identifies key drivers of ridership volume.

**Tools:** Python, Pandas, Matplotlib

---

### Hackathon 2 — Thai Election OCR
**File:** `hackathon2_thai_election_ocr.ipynb`

An OCR pipeline that extracts vote count data from Thai election result documents (Form สส.6/1) using Gemini Vision. The system handles multi-page documents, supports both constituency and party-list ballot types, and includes ensemble cross-validation with resumable batch processing.

**Tools:** Python, Gemini Vision API, Pandas

---

### Hackathon 3 — FahMai RAG (Thai Electronics Q&A)
**Files:** `hackathon3_fahmai_rag.ipynb`

A Retrieval-Augmented Generation (RAG) system for a Thai-language multiple-choice Q&A challenge for FahMai, a fictional electronics store. Built and compared three retrieval strategies — Dense (MiniLM embeddings), Sparse (BM25), and Hybrid using Reciprocal Rank Fusion (RRF) — powered by the ThaiLLM API.
**Tools:** Python, Sentence Transformers, BM25, PyThaiNLP, ThaiLLM API

---

### Hackathon 4 — House Image Classification
**File:** `hackathon4_house_image_classification.ipynb`

Binary image classification to detect whether a house is present in an image (1) or not (0). Fine-tuned EfficientNet-B3 (pretrained on ImageNet) with Stratified K-Fold cross-validation, evaluated using Accuracy Score.

**Tools:** Python, PyTorch, timm, EfficientNet-B3

---

### Hackathon 4 — Heart Disease Prediction
**File:** `hackathon4_heart_disease_prediction.ipynb`

A classification model to predict whether a patient has a history of heart disease (Yes/No), trained on 223,084 records. Used FLAML AutoML for model selection and Optuna for hyperparameter tuning, optimized for F2-score (recall-weighted).

**Tools:** Python, FLAML, LightGBM, Optuna, Scikit-learn

---

## 👤 Author
**Patsapol** | Student ID: 602903
SuperAI Engineer Season 6
