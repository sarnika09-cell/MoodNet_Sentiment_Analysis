# MoodNet – Sentiment Analysis using LSTM & Machine Learning

## 📌 Overview
MoodNet is a sentiment analysis project that classifies text data (tweets) into positive or negative sentiments using both traditional Machine Learning and Deep Learning models.

---

## 🎯 Objective
- Analyze user sentiment from social media text
- Compare performance of Machine Learning vs Deep Learning models
- Understand how sequential models (LSTM) improve NLP tasks

---

## 📊 Dataset
- Sentiment140 Dataset (Twitter data)
- Contains real-world noisy text data
- Labels:
  - 0 → Negative
  - 4 → Positive

---

## ⚙️ Technologies Used
- Python
- pandas, numpy
- scikit-learn
- TensorFlow / Keras
- Matplotlib

---

## 🧠 Models Implemented

### 1. Logistic Regression (Baseline Model)
- Used TF-IDF for feature extraction
- Fast and efficient baseline model

### 2. LSTM (Deep Learning Model)
- Used Embedding + LSTM layers
- Captures sequential dependencies in text
- Improved performance over traditional ML

---

## 🔄 Data Preprocessing
- Removed URLs, mentions, and special characters
- Converted text to lowercase
- Tokenization and padding for LSTM
- TF-IDF vectorization for ML model

---

## 📈 Results

| Model | Accuracy |
|------|--------|
| Logistic Regression | ~72% |
| LSTM | ~75% |

👉 LSTM performed better due to its ability to understand context and word sequence.

---

## 📊 Visualizations
- Model accuracy comparison graph
- Training vs validation accuracy plot
- Confusion matrix

---

## 🚀 Conclusion
- Deep learning models like LSTM outperform traditional ML in NLP tasks
- Logistic Regression provides a strong baseline
- Proper preprocessing significantly improves model performance

---

## 🔮 Future Work
- Use pre-trained embeddings (Word2Vec, GloVe)
- Try advanced models like BERT
- Deploy using Streamlit

---

## 📸 Screenshots
(Add your graphs here)

---

## 🔗 GitHub
(Add your repository link here)
