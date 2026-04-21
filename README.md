# 📰 NLP Text Classification using WELFake Dataset

## 📌 Overview

This project implements Natural Language Processing (NLP) techniques to classify news articles as **Fake (0)** or **Real (1)** using machine learning. The system performs preprocessing, vectorization, model training, and evaluation.

---

## 🎯 Objective

* Apply NLP preprocessing techniques
* Convert text into numerical features
* Build a machine learning classification model
* Evaluate model performance using standard metrics

---

## 📊 Dataset

* **Dataset Name:** WELFake Dataset
* **Source:** Kaggle
* **Link:** https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification

### 📁 Dataset Description

* Contains **~72,000+ news articles**
* Balanced dataset:

  * Fake News (0)
  * Real News (1)

### 🧾 Features:

* `title` → News headline
* `text` → Full article
* `label` → Target variable

---

## 🧠 NLP Preprocessing Techniques

The following preprocessing steps were applied:

* ✅ Tokenization
* ✅ Stopword Removal
* ✅ Stemming (Porter Stemmer)
* ✅ Lemmatization (WordNet)
* ✅ Lowercasing
* ✅ Removal of non-alphabetic characters

---

## 🔢 Text Vectorization

Two methods were used:

### 1️⃣ TF-IDF Vectorizer

* Converts text into weighted numerical features
* Reduces importance of common words

### 2️⃣ CountVectorizer

* Converts text into frequency-based features

---

## 🤖 Machine Learning Model

* **Model Used:** Logistic Regression
* Efficient and suitable for text classification tasks

---

## 📈 Model Evaluation

### 🔹 Metrics Used:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

---

## 📊 Results

| Method          | Accuracy   |
| --------------- | ---------- |
| CountVectorizer | **0.9399** |
| TF-IDF          | 0.9412     |

👉 TF-IDF generally performs better due to better feature weighting.

---

## 🧪 Sample Prediction

Input:

```
Breaking news: Government announces new policy.
```

Output:

```
Prediction: Real (1)
```

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib

---

## 🚀 How to Run the Project

```bash
pip install pandas numpy nltk scikit-learn matplotlib kagglehub
```

```python
import kagglehub
path = kagglehub.dataset_download("saurabhshahane/fake-news-classification")
```

Run the script or notebook step-by-step.

---

## 📌 Conclusion

* NLP preprocessing significantly improves text quality
* TF-IDF provides better feature representation
* Logistic Regression performs well for classification
* Model achieved high accuracy on real-world dataset

---

## 🙋‍♂️ Author

**Sarvesh Pandey**

