# MoodNet – Sentiment Analysis using LSTM & Machine Learning

## Overview
MoodNet is a sentiment analysis project that classifies social media text (tweets) into positive or negative sentiments using both traditional Machine Learning and Deep Learning models.

---

## Objective
- Analyze user sentiment from real-world Twitter data
- Compare Machine Learning and Deep Learning approaches
- Understand how sequential models improve NLP performance

---

## Dataset
- Sentiment140 Dataset (Twitter data)
- Contains noisy, real-world text
- Labels:
  - 0 → Negative
  - 4 → Positive

---

## Technologies Used
- Python
- pandas, numpy
- scikit-learn
- TensorFlow / Keras
- Matplotlib

---

## Models Implemented

### Logistic Regression (Baseline Model)
- Used TF-IDF for feature extraction
- Fast and efficient
- Provides a strong baseline for comparison

### LSTM (Deep Learning Model)
- Used Embedding and LSTM layers
- Captures sequential dependencies in text
- Achieves better performance than traditional ML models

---

## Data Preprocessing
- Removed URLs, mentions (@user), and special characters
- Converted text to lowercase
- Tokenization and padding for LSTM model
- TF-IDF vectorization for Logistic Regression
- Balanced dataset and applied stratified train-test split

---

## Results

| Model | Accuracy |
|------|--------|
| Logistic Regression | ~72% |
| LSTM | ~75% |

* LSTM performs better due to its ability to understand context and word sequence.

---

## Visualizations

### Model Accuracy Comparison
![Model Comparison](PASTE_LINK_HERE)

### Training vs Validation Accuracy
![Training Graph](PASTE_LINK_HERE)

---

## Confusion Matrix

The confusion matrix is used to evaluate model performance by comparing actual and predicted values.

It provides:
- True Positives (TP)
- True Negatives (TN)
- False Positives (FP)
- False Negatives (FN)

### Interpretation
- High diagonal values indicate correct predictions
- Off-diagonal values indicate errors

The model demonstrates balanced performance in predicting both positive and negative sentiments.

### Visualization

<img width="476" height="455" alt="confusion " src="https://github.com/user-attachments/assets/23f3e079-2ee3-45b3-8e5c-0588660b9ae8" />


---

## Conclusion
- LSTM outperforms Logistic Regression in sentiment classification tasks
- Traditional ML models still provide strong baseline results
- Proper preprocessing significantly improves performance on noisy text data

---

## Future Work
- Use pre-trained embeddings (Word2Vec, GloVe)
- Implement advanced models like BERT
- Deploy the model using Streamlit

---

## Screenshots
<img width="969" height="632" alt="Screenshot 2026-04-07 at 9 58 11 PM" src="https://github.com/user-attachments/assets/e133c86e-0761-4aeb-b752-e69e2ae56627" />
<img width="1306" height="704" alt="Screenshot 2026-04-07 at 9 55 19 PM" src="https://github.com/user-attachments/assets/8148e3a4-5893-46ec-b7fd-c7bc74fa9bf6" />


---

## GitHub
https://github.com/sarnika09-cell
