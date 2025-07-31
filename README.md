# 📰 Fake News Detection on News Headlines

**Name**: Fathan Nabil Arrazani  
**Student ID**: 0102522024  

---

## 📌 Project Overview

This project aims to detect **fake news** based solely on **news headlines** using a multi-model approach. It explores:

- **Classical machine learning** models with **TF-IDF** features  
- **Deep learning** using **LSTM** with **GloVe** embeddings  
- **Transformer-based** architecture using **Tiny-BERT**

---

## 📂 Dataset

**Dataset**: ISOT Fake News Dataset  
- Source: Kaggle  
  🔗 [Dataset Link](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

- Two categories:
  - **Fake news**: Intentionally misleading content  
  - **Real news**: Legitimate news articles

> Only the `title` column is used in this project.

---

## 🧠 Models Used

### 1. TF-IDF + Classical ML  
- Logistic Regression  
- Multinomial Naive Bayes  
- Linear SVC  

### 2. Deep Learning  
- LSTM with pre-trained **GloVe** embeddings (100-dimensional)

### 3. Transformer-Based Model  
- Fine-tuned **Tiny-BERT** using HuggingFace Transformers

---

## 📊 Evaluation Metrics

- **Accuracy**  
- **Precision**, **Recall**, and **F1-Score**  
- **Confusion Matrix**  
- **ROC AUC** (where applicable)

---

## 🔧 Requirements

**Recommended:**
- Python ≥ 3.8  
- Jupyter Notebook / Google Colab  
- GPU support for deep learning models (LSTM & BERT)

---

## 💡 How to Run

1. Clone this repository  
2. Open the notebooks in Jupyter/Colab  
3. Run each cell sequentially to:
   - Preprocess the data  
   - Train the models  
   - Evaluate the results

---

## 🚀 Results Summary

| Model           | Accuracy | F1-Score |
|-----------------|----------|----------|
| TF-IDF + LR     | ~93%     | ~92%     |
| LSTM + GloVe    | ~95%     | ~94%     |
| Tiny-BERT       | ~97%     | ~96%     |

> 📌 *Note: Results may vary slightly depending on random seed and execution environment.*

---

## 📚 References

- [ISOT Fake News Dataset (Kaggle)](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)  
- [Tiny-BERT (HuggingFace)](https://huggingface.co/prajjwal1/bert-tiny)

---

## 👨‍💻 Author

**Fathan Nabil Arrazani**  
Informatics Student, Universitas Al Azhar Indonesia
