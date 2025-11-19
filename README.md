# Fake News Classifier (Machine Learning Project)

A complete machine-learning project for detecting **Fake** vs **True** news articles using NLP, TF-IDF vectorization, and multiple ML models. 
This repository includes a fully documented **Jupyter notebook**, clean project structure, and a Google Colab link for easy execution.

---

## 🔗 Run on Google Colab

Open the notebook directly in Google Colab:

https://colab.research.google.com/github/Naidi47/Fake_news_classifier_ML/blob/main/notebooks/fake_news_classifier.ipynb

---

## 📁 Project Structure

```
fake-news-classifier/
│
├── data/                         # Contains Fake.csv & True.csv (not uploaded)
│
├── notebooks/
│   └── fake_news_classifier.ipynb
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## ▶️ Usage

1. Clone or download the notebook (`fake_news_classifier.ipynb`).
2. Place **Fake.csv** and **True.csv** inside the `data/` folder.
3. Run the notebook:

```
jupyter notebook notebooks/fake_news_classifier.ipynb
```

The notebook will:

- Load and explore the dataset
- Preprocess text
- Train 6 ML models
- Compare performance
- Save the best model (`best_model.joblib`)

---

## 🔍 Methodology (Simple Explanation)

### **1. Exploratory Data Analysis (EDA)**
- Visualize class distribution  
- Analyze text length & word counts  
- Optional: Word clouds  

### **2. Text Preprocessing**
- Remove URLs, HTML tags, special characters  
- Lowercase  
- Tokenize words  
- Remove stopwords  
- Lemmatize words  

### **3. Feature Engineering**
- TF-IDF vectorizer (unigrams + bigrams)  
- Additional numeric features:
  - content_length  
  - word_count  
  - punct_count  

### **4. Models Trained**
- Linear Regression  
- Logistic Regression  
- Multinomial Naive Bayes  
- Random Forest  
- Linear SVM (calibrated)  
- Gradient Boosting  

### **5. Evaluation Metrics**
- Accuracy  
- Precision, Recall, F1-Score  
- ROC-AUC  
- Confusion Matrix  

### **6. Cross-Validation**
- Logistic Regression: 5-fold  
- Random Forest: 3-fold  

### **7. Model Comparison**
Creates a leaderboard and saves the best model.

---

## 🏆 Results Summary

| Model | Accuracy | AUC | Speed |
|-------|----------|------|--------|
| Logistic Regression | ~0.92 | ~0.95 | Fast |
| Random Forest | ~0.91 | ~0.94 | Medium |
| Linear SVM | ~0.90 | ~0.93 | Medium |
| Gradient Boosting | ~0.89 | ~0.92 | Slow |
| Naive Bayes | ~0.87 | ~0.90 | Very Fast |
| Linear Regression | ~0.85 | ~0.88 | Fast |

### **Key Insights**
- Fake news uses more sensational language  
- TF-IDF + Logistic Regression is the best balance of speed & accuracy  
- More complex models may improve accuracy slightly  

---

## 👤 Author

**M Brahmanaidu**  
Aspirant Data Science / AI & ML Developer  
GitHub: https://github.com/Naidi47  
LinkedIn: https://www.linkedin.com/in/brahmanaidu-muchukuntla-17a1a9242/  
Email: muchukuntlabrahmanaidu@gmail.com  

---

## 📜 License

This project is open for learning, research, and improvement.

