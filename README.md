# 🤖 Transformer-Based Question Answering System

A complete NLP pipeline built with **Hugging Face Transformers**, fine-tuned on **SQuAD v1.1** to perform span-based question answering — just like modern AI assistants.

---

## Overview
This project uses transformer architectures (BERT, DistilBERT, RoBERTa) to extract precise answers from text passages. It includes:
- Model fine-tuning on SQuAD
- Evaluation (Exact Match & F1)
- Model comparison across architectures
- Streamlit-based web interface for real-time QA

---

## Tech Stack
- Python 🐍
- PyTorch
- Hugging Face Transformers
- Pandas
- Weights & Biases
- Streamlit

---

## 📊 Results
| Model        | Exact Match (EM) | F1 Score |
|---------------|------------------|-----------|
| BERT-base     | 82.3             | 88.9      |
| DistilBERT    | 79.5             | 86.1      |
| RoBERTa-base  | 83.8             | 89.4      |

*(sample results — update with your own after evaluation)*

---

##  Usage

###  Install dependencies
```bash
pip install -r requirements.txt
