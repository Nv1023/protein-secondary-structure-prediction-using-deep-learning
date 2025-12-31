![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
# 🧬 Protein Secondary Structure Prediction using Deep Learning

## 📌 Project Overview
Predicting the **secondary structure of proteins** is a fundamental problem in computational biology.  
The way a protein folds into **helices, sheets, and loops** directly influences its biological function, stability, and interactions.

This project is developed as part of a Kaggle deep learning challenge focused on **sequence-to-sequence prediction**, where the goal is to automatically infer protein secondary structure from amino acid sequences.

---

## 🎯 Problem Statement
Given an input **peptide sequence** (e.g., `"ACDEFGHIK"`), the task is to predict a corresponding **secondary structure sequence** of the same length.

Each amino acid in the sequence is mapped to a structural label under two annotation schemes:

- **Q8 (sst8)** – Eight-state secondary structure classification
- **Q3 (sst3)** – Simplified three-state classification

This makes the problem a **character-level sequence-to-sequence learning task**.

---

## 🧠 Approach

1. **Data Representation**
   - Encode amino acid sequences numerically
   - Handle variable-length peptide sequences
   - Align input and output sequences of equal length

2. **Model Architecture**
   - Embedding layer for amino acid representation
   - **Bidirectional sequence models** (BiLSTM / BiGRU)
   - Dense output layer for per-position classification

3. **Training Strategy**
   - Sequence-level categorical cross-entropy loss
   - Masking to handle padding tokens
   - Validation-based performance monitoring

4. **Prediction**
   - Predict secondary structure labels for each amino acid
   - Generate outputs compatible with Kaggle submission format

---

## 🛠️ Technologies Used

- **Python**
- **NumPy** – Numerical operations
- **Pandas** – Dataset handling
- **TensorFlow / Keras** – Deep learning framework
- **Scikit-learn** – Evaluation utilities
- **Matplotlib & Seaborn** – Training visualization
- **Jupyter Notebook**

---

## 📊 Results

Successfully modeled protein secondary structure as a sequence-to-sequence task

Generated predictions for both Q3 and Q8 annotation schemes

Demonstrated the effectiveness of bidirectional sequence models for biological sequences

---

## 📊 Results

Successfully modeled protein secondary structure as a sequence-to-sequence task

Generated predictions for both Q3 and Q8 annotation schemes

Demonstrated the effectiveness of bidirectional sequence models for biological sequences

---

## 👤 Author

Nagavengadeshwaran S
📧 Email: 24f1000802@ds.study.iitm.ac.in

🔗 GitHub: https://github.com/Nv1023

