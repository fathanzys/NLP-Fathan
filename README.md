\

# 🎯 Sentiment Analysis on TikTok Comments – *"Kabur Aja Dulu" by Presiden Jokowi*

This repository contains a sentiment analysis project on TikTok comments related to President Jokowi’s popular phrase *"Kabur Aja Dulu"*. The goal is to classify public sentiment into **positive**, **neutral**, or **negative** using natural language processing (NLP) and machine learning techniques.

## 📁 Dataset

* Source: Scraped from TikTok comments (manually collected or from crawler – not included in repo).
* Format: `.csv` with a `text` column containing raw comments.

---

## 🧰 Libraries Used

* `pandas`, `numpy` – for data handling
* `matplotlib`, `seaborn` – for data visualization
* `scikit-learn` – for machine learning model (LinearSVC)
* `nltk`, `Sastrawi` – for text preprocessing and stemming (Indonesian)
* `wordcloud` – for visualizing frequent terms
* `indonesian-nlp` (optional) – for lexicon-based sentiment labeling

---

## ⚙️ Features

### 🔄 Text Preprocessing

* Lowercasing
* Removing URLs, mentions, special characters
* Stopword removal (customized to keep negation words)
* Stemming using **Sastrawi**

### 🔤 Sentiment Labeling

* If `indonesian-nlp` is available: uses prebuilt sentiment analyzer
* If not: fallback to a custom lexicon-based labeling method

### 🧠 Modeling

* TF-IDF vectorization
* Linear Support Vector Classifier (LinearSVC)
* Model training & evaluation (accuracy, confusion matrix, classification report)

### 📊 Visualizations

* Sentiment distribution (pie & bar charts)
* PCA for feature space visualization
* Word frequency charts (bar plots)
* Wordclouds for each sentiment class
* Boxplot for comment length vs. sentiment

---

## 📈 Results

* Model performance is evaluated using classification metrics.
* Provides insight into public opinion on President Jokowi’s viral moment using real social media data.

---

## 📌 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/nama-repo.git
   cd nama-repo
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   * Open `sentiment_analysis_jokowi.ipynb` in **Google Colab** or **Jupyter Notebook**
   * Make sure to upload your CSV file or update the file path

---

## 📂 Folder Structure

```
📦project-root
 ┣ 📄 sentiment_analysis_jokowi.ipynb
 ┣ 📄 README.md
 ┣ 📄 requirements.txt
 ┗ 📂 data
     ┗ 📄 data_scrapper_jokowi.csv
```

---

## 🤝 Contributions

Feel free to fork, open issues, or submit pull requests for improvements and features. Indonesian NLP is still growing and your input matters!

---

## 🧠 Credit

Created by \Fathan Nabil Arrazani – Informatics Student at Universitas Al Azhar Indonesia.

