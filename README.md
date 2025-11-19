# Fake News Classifier

A simple machine learning project for detecting fake vs. true news using a Jupyter Notebook.
This project includes data loading, preprocessing, feature extraction, model training, and evaluation.

---

## 📁 Project Structure

```
fake-news-classifier/
│
├── data/                         # Dataset folder (not uploaded to GitHub)
│   ├── Fake.csv                  # Fake news articles
│   ├── True.csv                  # True news articles
│
├── notebooks/
│   └── fake_news_classifier.ipynb   # Main Jupyter notebook
│
├── requirements.txt              # Python dependencies
├── .gitignore                    # Files/folders to ignore in Git
└── README.md                     # Project documentation
```

---

## ▶️ Usage

1. Place **Fake.csv** and **True.csv** inside the `data/` folder.
2. Open the notebook:

```
jupyter notebook notebooks/fake_news_classifier.ipynb
```

3. Run all cells in order.

---

## 🔧 Requirements

Install all dependencies:

```
pip install -r requirements.txt
```

---

## 📌 Notes

- The dataset is not included in GitHub because of its size.
- The notebook will automatically download required NLTK resources.

---

## 📜 License

This project is free to use for learning and educational purposes.