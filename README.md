# 📰 PyTorch NLP: Arabic News Classification (Hespress Dataset)

This project demonstrates **Arabic News Topic Classification** using **BERT** (`asafaya/bert-base-arabic`) with **PyTorch**.  
It involves **data cleaning, preprocessing, model training, and evaluation** using the **Hespress dataset** from Kaggle.

---

## 📚 Project Overview

The goal is to classify Arabic news articles into predefined topics such as **Politics**, **Economy**, **Sport**, etc.  
The workflow includes:
1. Downloading and loading the **Hespress dataset**.
2. Cleaning and preprocessing Arabic text.
3. Tokenizing data using a pre-trained **Arabic BERT model**.
4. Fine-tuning **BERT** for sequence classification.
5. Evaluating model performance on validation, test, and custom datasets.

---

## 📦 Dependencies

Make sure to install the following dependencies:

```bash
pip install torch transformers pandas matplotlib seaborn scikit-learn pyarabic pystemmer kaggle
