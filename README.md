# Fake News Detection Using LSTM

## Team Members
- **Abhishek Kumar** - 21BCE0846
- **G.Divakar Reddy** - 21BCE3417
- **Sayan Mitra** - 21BCE0384

## Aim
This project aims to develop a fake news detection system using Long Short-Term Memory (LSTM) deep learning techniques. It analyzes news article texts and headlines to classify them as fake or real.

---

## Abstract
In today's technology-driven world, the spread of false information has become a critical issue. The proliferation of misinformation through social media platforms has led to public confusion, political polarization, and health crises. This project leverages LSTM networks to address these challenges by accurately identifying fake news.

The LSTM model processes text sequences to detect subtle linguistic cues and patterns, achieving a **94% accuracy** in classifying news articles. This research provides a robust tool for combating misinformation and highlights the potential of deep learning in fake news detection.

---

## Introduction
The rise of fake news poses significant risks, including:
- **Political manipulation**
- **Societal polarization**
- **Public health crises**

Traditional detection methods, such as manual fact-checking and heuristic rules, struggle to handle the massive volume of content shared online. LSTM networks, with their ability to capture long-term dependencies in text, offer a promising solution.

### Why LSTM?
- Captures **contextual relationships** over long text sequences.
- Overcomes the **vanishing gradient problem** in traditional RNNs.
- Effective in detecting subtle linguistic and structural patterns.

---

## Methodologies

### 1. Data Collection
We utilized the following datasets:
- [LIAR Dataset](https://example.com): 12,800 short claims labeled as true, false, or other categories.
- [FakeNewsNet Dataset](https://example.com): News articles with metadata and social context.
- [Kaggle Fake News Detection Dataset](https://www.kaggle.com): Headlines and article content labeled as real or fake.

### 2. Data Preprocessing
Steps include:
- **Text Cleaning**: Removing punctuation, special characters, and HTML tags.
- **Tokenization**: Splitting text into tokens.
- **Stopword Removal**: Eliminating common words like "and" and "the".
- **Padding**: Ensuring uniform input sequence length.

### 3. Feature Extraction
- **Word Embeddings**: Using pre-trained embeddings like Word2Vec, GloVe, or FastText.
- **TF-IDF**: Calculating term importance, though embeddings are preferred.

### 4. LSTM Model Design
Architecture:
- **Input Layer**: Padded word sequences.
- **Embedding Layer**: Converts words into dense vectors.
- **LSTM Layer**: Captures long-term dependencies.
- **Dense Layer**: Outputs probabilities for classification.
- **Output Layer**: Binary classification (real or fake).

### 5. Model Training
- **Loss Function**: Binary cross-entropy.
- **Optimizer**: Adam or RMSprop.
- **Metrics**: Accuracy, Precision, Recall, F1-Score.

### 6. Evaluation Metrics
- **Accuracy**: Overall correctness.
- **Precision**: Accuracy of fake news predictions.
- **Recall**: Model's ability to detect fake news.
- **F1-Score**: Balance of precision and recall.
- **AUC-ROC Curve**: Distinguishing capability between classes.

### 7. Baseline Model Comparison
We compared LSTM with:
- Logistic Regression
- Support Vector Machines (SVM)
- Naive Bayes

---

## Results
The LSTM model achieved:
- **94% accuracy**
- Superior performance compared to baseline models.

---

## Conclusion
Our LSTM-based fake news detection system provides an effective solution to combat misinformation. Future work includes:
- Extending the model to social media posts.
- Enhancing performance with larger datasets.

---

## References
- [LIAR Dataset](https://example.com)
- [FakeNewsNet Dataset](https://example.com)
- [Kaggle Dataset](https://www.kaggle.com)

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repository.git

2. Clone the repository:
   ```bash
   pip install -r requirements.txt

