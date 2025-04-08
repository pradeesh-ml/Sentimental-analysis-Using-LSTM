# IMDB Sentiment Classification using LSTM

This project performs binary sentiment classification (positive/negative) on movie reviews from the IMDB dataset using an LSTM-based neural network.

## 📂 Dataset

- Dataset: [IMDB Movie Review Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)
- Format: `CSV` with two columns: `review` and `sentiment`

## ⚙️ Features

- Data cleaning (HTML tags, URLs, special characters, etc.)
- Stopword removal
- Lemmatization
- Tokenization & Padding
- LSTM model using TensorFlow/Keras
- Accuracy and Classification Report
- Real-time inference on new sentences

## 📦 Libraries Used

- `pandas`
- `scikit-learn`
- `nltk`
- `tensorflow` / `keras`

## 📊 Model Architecture

- Embedding Layer: 3000 vocab size, 100-dimensional vectors
- Bidirectional LSTM: 64 units
- Dense Layers: ReLU + Sigmoid
- Loss: Binary Crossentropy
- Optimizer: Adam
- Accuracy Metric

## 🧠 Model Architecture

- **Embedding Layer**: vocab size 3000, embedding dimension 100
- **Bidirectional LSTM Layer**: 64 units
- **Dense Layer**: 24 ReLU units
- **Output Layer**: 1 unit (Sigmoid activation)

## 📊 Evaluation Metrics

**Accuracy on test set: 0.87**

          precision    recall  f1-score   support

       0       0.91      0.82      0.86      4961
       1       0.84      0.92      0.88      5039

accuracy                           0.87     10000



