# 🎬 Movie Review Sentiment Analysis (NLP & Deep Learning)

### 📌 Project Overview
This project focuses on **Natural Language Processing (NLP)** to classify IMDB movie reviews as either **Positive** or **Negative**. It utilizes **Deep Learning** techniques, specifically **Long Short-Term Memory (LSTM)** networks, to understand the context and sequence of words in text data.

### 🛠️ Tech Stack
* **Deep Learning:** TensorFlow, Keras (LSTM, Embedding, Bidirectional layers)
* **Data Processing:** Pandas, NumPy, Regular Expressions (Regex)
* **Visualization:** Matplotlib, Seaborn
* **Preprocessing:** Tokenization, Padding Sequences, Stopword Removal

### 🧠 Model Architecture
* **Embedding Layer:** Converts words into dense vectors of fixed size.
* **Bidirectional LSTM:** Captures context from both past and future words in the sequence.
* **Dense Layers:** Fully connected layers with ReLU and Sigmoid activation for binary classification.
* **Optimization:** Adam Optimizer with Early Stopping to prevent overfitting.

### 📊 Key Results
* **Accuracy:** Achieved **83% accuracy** on the validation dataset.
* **F1-Score:** 0.83 (Balanced precision and recall).
* **Dataset:** Trained on 50,000 IMDB movie reviews (Balanced dataset).
