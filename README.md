# Fake News Detection on News Headlines

**Nama**: Fathan Nabil Arrazani
**NIM**: 0102522024

## 📌 Project Overview

This project focuses on detecting fake news based solely on news headlines using a multi-model approach. It explores traditional machine learning methods with TF-IDF features, deep learning with LSTM and GloVe embeddings, and a transformer-based model using Tiny-BERT.

## 📂 Dataset

**ISOT Fake News Dataset**

* Source: Kaggle ([link]([https://www.kaggle.com/datasets/shayanfazeli/isot-fake-news-dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)))
* Two classes:

  * **Fake news**: intentionally misleading content
  * **Real news**: legitimate news articles
* Only the `title` column is used for this project.

## 🧪 Models Used

1. **TF-IDF + Classical ML**

   * Logistic Regression
   * Multinomial Naive Bayes
   * Linear SVC

2. **Deep Learning**

   * LSTM with GloVe word embeddings (100D)

3. **Transformer-based**

   * Fine-tuned Tiny-BERT with HuggingFace Transformers

## 📝 Project Structure

```
├── data/                   # Folder for dataset
├── models/                 # Saved models
├── results/                # Evaluation reports and plots
├── tfidf_ml.ipynb          # Notebook for TF-IDF + ML models
├── lstm_glove.ipynb        # Notebook for LSTM + GloVe
├── tinybert_finetune.ipynb # Notebook for Tiny-BERT fine-tuning
└── README.md               # Project documentation
```

## 📊 Evaluation Metrics

* Accuracy
* Precision, Recall, F1-Score
* Confusion Matrix
* ROC AUC (where applicable)

## 🔧 Requirements

Install required libraries:

```bash
pip install -r requirements.txt
```

Recommended:

* Python 3.8+
* Jupyter Notebook
* GPU support for deep learning

## 💡 How to Run

1. Clone this repository
2. Open each notebook in Jupyter/Colab
3. Follow the cells to run preprocessing, training, and evaluation

## 🚀 Results Summary

| Model        | Accuracy | F1-Score |
| ------------ | -------- | -------- |
| TF-IDF + LR  | \~93%    | \~92%    |
| LSTM + GloVe | \~95%    | \~94%    |
| Tiny-BERT    | \~97%    | \~96%    |

> *Note: Metrics may vary depending on random seed and environment.*

## 📚 References

* [ISOT Fake News Dataset]([https://www.kaggle.com/datasets/shayanfazeli/isot-fake-news-dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset))
* Pennington et al. (2014) - GloVe: Global Vectors for Word Representation
* Devlin et al. (2018) - BERT: Pre-training of Deep Bidirectional Transformers

## 👨‍💻 Author

Fathan Nabil Arrazani
Informatics Student at Universitas Al-Azhar Indonesia
