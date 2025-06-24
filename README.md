# 📰 Fake News Detection using Semantic Processing

A machine learning project to detect fake news articles using semantic text preprocessing and traditional classifiers like Linear Regression, Decision Tree, and Random Forest.

---

## 📁 Dataset
- Files: `True.csv`, `Fake.csv`
- Total Articles: 44,919 (Real: 21,417 | Fake: 23,502)

---

## 🔧 Preprocessing

Custom `wordopt()` function used to:
- Lowercase text
- Remove URLs, HTML, punctuation, digits
- Normalize whitespace

---

## 🧠 Models & Results

| Model            | Accuracy | Precision | Recall | F1-Score |
|------------------|----------|-----------|--------|----------|
| Linear Regression| 0.99     | 0.985     | 0.985  | 0.985    |
| Decision Tree    | 1.00     | 0.995     | 0.995  | 1.00     |
| Random Forest    | 0.99     | 0.99      | 0.99   | 0.99     |

📊 Visual charts in `/visuals/`

---

## 📦 Installation

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
