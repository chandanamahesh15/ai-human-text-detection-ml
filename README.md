# AI vs Human Text Detection

Machine learning project for detecting AI-generated vs human-written text using TF-IDF, BiLSTM, BERT, RoBERTa, and Qwen.

---

## Project Overview

This project compares multiple models for AI text detection and evaluates their performance on both internal and external datasets.

---

## Requirements Covered

- Load dataset  
- Define baseline models  
- Train models  
- Evaluate on withheld test set  
- Display results  

---

## Models Used

- Majority Class Baseline  
- Stratified Baseline  
- TF-IDF + Logistic Regression  
- BiLSTM (scratch embeddings)  
- BERT (fine-tuned)  
- RoBERTa (fine-tuned)  
- Qwen (frozen embeddings + LR)  

---

## Dataset

Expected file:

`AI_Human.csv.zip`

Columns:
- text  
- generated  

Labels:
- 0 → Human  
- 1 → AI  

---

## How to Run

1. Open notebook in Google Colab  
2. Upload dataset file  
3. Run all cells  
4. Results will be displayed  

---

## Results

- Internal accuracy ≈ 99%  
- External accuracy ≈ 82–89%  
- TF-IDF shows best generalization  

---

## Note

Notebook is fully executed. Outputs are visible.
