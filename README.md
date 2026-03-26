# BERT-Based-Sentiment-Analysis-using-NLP
This project implements a sentiment analysis system using the BERT model from HuggingFace Transformers. It is trained on the IMDB dataset to classify movie reviews as positive or negative. The system uses tokenization, fine-tuning of a pre-trained transformer model, and evaluation using accuracy metrics. 

# 📊 BERT Sentiment Analysis

> AI model that understands human language and predicts sentiment using BERT

---

## ⚡ Quick Stats

* 🧠 Model: BERT (bert-base-uncased)
* 📂 Dataset: IMDB (50K reviews)
* 🎯 Task: Binary Sentiment Classification
* 📈 Output: Positive / Negative

---

## 🔄 System Pipeline

```mermaid
graph LR
A[User Input Text] --> B[Tokenizer]
B --> C[BERT Encoder]
C --> D[Dense Layer]
D --> E[Prediction]
E --> F[Positive / Negative]
```

---

## 🧠 Model Architecture (Simplified)

```mermaid
flowchart LR
A[Text Input] --> B[Embedding Layer]
B --> C[Transformer Layers]
C --> D[CLS Token]
D --> E[Classifier Head]
E --> F[Output Label]
```

---

## 📊 Data Insight (Sample Distribution)

```mermaid
pie
    title IMDB Dataset Distribution
    "Positive Reviews" : 25000
    "Negative Reviews" : 25000
```

---

## 📉 Training Workflow

```mermaid
flowchart TD
A[Load Dataset] --> B[Tokenization]
B --> C[Train BERT Model]
C --> D[Validation]
D --> E[Accuracy Calculation]
E --> F[Save Model]
```

---

## 🚀 Inference Flow

```mermaid
graph TD
A[New Sentence] --> B[Preprocessing]
B --> C[Model Prediction]
C --> D[Sentiment Output]
```

---

## 🧪 Example Predictions

```python
classifier("This movie was absolutely amazing!")
# Positive

classifier("I regret watching this movie.")
# Negative
```

---

## 📁 Project Structure

```
BERT-Based-Sentiment-Analysis
 ┣ bert_nlp.ipynb
 ┣ README.md
```

---

## 👩‍💻 Contributors

* Tazub
* muskan

---

## 🌟 Future Enhancements

* 📊 Interactive Streamlit Dashboard
* 📈 Visualization of training metrics
* 🌐 Model deployment (web app)

---

## 💡 Key Idea

This project shows how **transformer-based models like BERT** can understand context and meaning in text, enabling accurate sentiment classification.

---

⭐ If you found this useful, give it a star!
