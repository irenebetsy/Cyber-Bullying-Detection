# 🛡️ Cyber Bullying Detection

## 📜 License

This project is licensed under the **Apache License 2.0**. See the [LICENSE](./LICENSE) file for more details.

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)

This project focuses on detecting cyberbullying across social media platforms, specifically **Twitter** and **Instagram**. It leverages state-of-the-art **Natural Language Processing (NLP)** techniques and **deep learning models** such as **BiLSTM** and **BERT** to classify text data for signs of cyberbullying.

---

## 📁 Project Structure

- `Cyber_Bullying_Detection.ipynb`: Main notebook containing the entire pipeline including data collection, preprocessing, model building, and evaluation.
- `LICENSE`: Apache 2.0 license file.

---

## 📌 Features

- ✅ Scraping Twitter tweets using **snscrape**
- ✅ Extracting Instagram comments using **Apify**
- ✅ Text preprocessing: cleaning, tokenization, lemmatization
- ✅ Sentiment analysis using **TextBlob** and **VADER** for polarity scoring
- ✅ Model training using:
  - **BiLSTM** (Bidirectional LSTM)
  - **BERT** (Transformer-based model)
- ✅ Evaluation metrics: Accuracy, F1-Score, Confusion Matrix

---

## 📊 Dataset

- **Twitter**: Scraped using `snscrape` for relevant bullying-related hashtags and keywords.
- **Instagram**: Scraped using `Apify` to collect post comments.

Each entry consists of:
- `Username`
- `Text Content`
- `Timestamp`
- `Source Platform`
- `Polarity Score`
- `Label` (Cyberbullying or Not)

---

## ⚙️ Preprocessing Techniques

- Removing special characters, mentions, hashtags, and URLs
- Lowercasing and whitespace normalization
- Tokenization and Lemmatization
- Stopword removal
- Polarity scoring using **TextBlob** and **VADER**

---

## 🧠 Models Used

| Model  | Description |
|--------|-------------|
| **BiLSTM** | Captures long-range dependencies in both forward and backward directions. |
| **BERT** | Fine-tuned transformer model with contextual embeddings for accurate classification. |

---

## 📈 Evaluation

- Used standard classification metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix
- Compared BiLSTM and BERT performances

---



---

## 🙌 Acknowledgements

- [snscrape](https://github.com/JustAnotherArchivist/snscrape) for Twitter data scraping  
- [Apify](https://www.apify.com/) for Instagram comment extraction  
- [TextBlob](https://textblob.readthedocs.io/) and [VADER](https://github.com/cjhutto/vaderSentiment) for sentiment analysis  
- [Transformers](https://huggingface.co/transformers/) by Hugging Face for BERT implementation  

---

## 👩‍💻 Author

  **Irene Betsy D** 
