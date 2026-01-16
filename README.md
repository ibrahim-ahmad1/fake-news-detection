# Fake News Detection using Machine Learning

## 📌 Project Overview
This project is a Machine Learning–based Fake News Detection system that classifies news articles as **Fake** or **Real** using Natural Language Processing (NLP) techniques. The model learns patterns from news text and predicts the authenticity of unseen news articles.

---

## 🧠 Problem Statement
With the rapid spread of misinformation on social media and news platforms, it has become difficult to identify fake news manually. This project aims to automatically detect fake news using text-based machine learning techniques.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- TF-IDF Vectorizer
- Logistic Regression
- Matplotlib / Seaborn (for visualization)

---

## 📂 Dataset
Two datasets were used:
- **Fake News Dataset** → labeled as `0`
- **Real News Dataset** → labeled as `1`

Both datasets were merged and shuffled to create a single training dataset.

---

## ⚙️ Methodology
1. Loaded fake and real news datasets
2. Assigned labels (0 for Fake, 1 for Real)
3. Merged and shuffled the datasets
4. Cleaned text data (lowercasing, removing punctuation and symbols)
5. Converted text into numerical features using **TF-IDF Vectorizer**
6. Split data into training and testing sets
7. Trained a **Logistic Regression** classifier
8. Evaluated the model using accuracy and confusion matrix
9. Built a prediction function for new/unseen news

---

## 🧪 Model Used
- **Logistic Regression**
- Chosen for its simplicity, speed, and effectiveness in text classification tasks

---

## 📊 Performance
- **Accuracy:** ~99%
- The model performed exceptionally well after tuning TF-IDF parameters and balancing the dataset.


## 📈 Evaluation Metrics
- Accuracy Score
- Confusion Matrix


