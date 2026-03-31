# 📧 Email Spam Detection using Machine Learning

## 🚀 Project Overview

Developed a machine learning-based **email spam classification system** that accurately distinguishes between spam and legitimate messages using Natural Language Processing (NLP) techniques.

The project demonstrates a complete **end-to-end ML workflow**, including data preprocessing, feature extraction, model training, and evaluation.

---

## 📊 Dataset

* **Source:** Kaggle – SMS Spam Collection Dataset
* Contains labeled messages as **spam** or **ham (not spam)**
* Real-world dataset widely used for NLP classification tasks

---

## 🧠 Approach & Methodology

### 1. Data Preprocessing

* Text cleaning (removal of punctuation, special characters)
* Lowercasing and tokenization
* Stopword removal using NLP techniques

### 2. Feature Extraction

* Converted text into numerical form using:

  * **TF-IDF Vectorization**
* Captures importance of words across documents

### 3. Model Building

* Implemented **Logistic Regression** for classification
* Trained on labeled dataset using supervised learning

### 4. Evaluation

* Evaluated using:

  * Accuracy
  * Precision & Recall
  * Confusion Matrix
  * Classification Report

---

## 📈 Results

* Achieved high classification accuracy on test data
* Effective in distinguishing spam messages with minimal false positives

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** Pandas, NumPy, scikit-learn
* **NLP Tools:** NLTK, TF-IDF
* **Visualization:** Matplotlib, Seaborn

---

## 📁 Project Structure

```
Email-Spam-Detection/
│── email_spam_detection.py   # Main ML script
│── EMAIL_SPAM_DETECTION.ipynb # Experimentation notebook
│── MNB.pkl                   # Naive Bayes model
│── RFC.pkl                   # Random Forest model
│── DTC.pkl                   # Decision Tree model
│── README.md
```

---

## 🔬 Key Learnings

* Practical implementation of **NLP in classification problems**
* Importance of **feature engineering in text data**
* Model comparison across multiple classifiers
* Understanding evaluation metrics for classification tasks

---

## ⭐ Highlights for Recruiters

✔ End-to-end NLP-based ML pipeline
✔ Hands-on experience with text preprocessing and TF-IDF
✔ Multiple model experimentation (LR, NB, RF, DT)
✔ Strong understanding of classification metrics
✔ Clean and modular implementation

---

## 👤 Author

**Kartikey Chaturvedi**
B.Tech (IT) | Machine Learning Enthusiast

GitHub: https://github.com/Kartikeyji17

---

## ⚠️ Note

This project is developed for educational purposes and demonstrates applied machine learning concepts in spam detection.
