# BERT Model: Masked Word Prediction and Sentiment Analysis 

This project demonstrates the use of **BERT** (Bidirectional Encoder Representations from Transformers) for tasks such as:
- Predicting masked words using the **fill-mask** pipeline.
- Performing sentiment analysis on input text using the **sentiment-analysis** pipeline.

---

## Features
- **Tokenization and Decoding**: Encode input text and decode tokens back to text.
- **Masked Word Prediction**: Predict the most likely candidates for masked words in a sentence.
- **Sentiment Analysis**: Analyze the sentiment (positive or negative) of a given text.

---

## Technologies Used
- **Python 3.9+**
- **Hugging Face Transformers Library**
- Pre-trained models:
  - `google-bert/bert-large-uncased-whole-word-masking` for masked word prediction.
  - Default model for sentiment analysis from Hugging Face.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rituraj-sys/Masked-Words-and-Sentiment-Analysis.git
   cd Masked-Words-and-Sentiment-Analysis
