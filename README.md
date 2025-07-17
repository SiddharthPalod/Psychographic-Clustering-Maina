# 🧠 Psychographic Analysis of Mental Health App Reviews for Maina

This project performs deep **text and behavioral analysis** on user reviews from **mental health applications** in India. It uses NLP, sentiment analysis, topic modeling, and behavioral clustering to build **psychographic personas** based on large-scale review data.

---

## 📌 Objectives

- Clean and preprocess review data.
- Perform **Aspect-Based Sentiment Analysis (ABSA)**.
- Extract **keywords**, **entities**, and **behavioral traits**.
- Identify **psychographic categories** based on user feedback.
- Model **psychological triggers and personas** using NLP techniques.

---

## 🧪 Techniques Used

### ✅ Text Preprocessing
- Lowercasing, stopword removal, punctuation handling, lemmatization.

### ✅ Sentiment & Emotion Analysis
- VADER Sentiment Analyzer (V1).
- Behavioral Sentiment patterns (V2).

### ✅ Entity & Keyword Extraction
- TF-IDF-based keyword extraction.
- SpaCy Named Entity Recognition (NER).

### ✅ Topic Modeling & Clustering
- Latent Dirichlet Allocation (LDA) for topic modeling.
- Clustering users by sentiments, pain points, and psychological triggers.

---

## 🧬 Project Versions

### 🔹 V0 – Data Collection
- Identified top mental health apps in India.
- Scraped review data from Google Play Store.

### 🔹 V1 – NLP Pipeline (Baseline)
- Cleaned and normalized text data.
- Performed sentiment analysis using VADER.
- Extracted keywords (TF-IDF) and named entities (SpaCy).
- Categorized behavior using rule-based logic.

### 🔹 V2 – Behavioral & Psychographic Modeling
1. **Classified Reviews by Psychographic Categories**  
   → Used pretrained **DistilBERT** for trait prediction (e.g., emotional tone, personality).
2. **Behavioral Sentiment Analysis**  
   → Analyzed emotional support indicators and app trustworthiness.
3. **Topic Modeling for Psychological Triggers**  
   → LDA modeling with Gensim to identify underlying mental health themes.
4. **Persona Creation**  
   → Clustered users into psychographic groups based on themes, tone, and behavioral keywords.

---

## 🔍 Sample Topics (from LDA on 65,000 Reviews)

| Topic | Keywords |
|-------|----------|
| **0** | anxiety, wysa, feel, lot, thank, love, helped, really, help, app |
| **1** | money, great, therapy, pay, help, therapist, health, mental, free, app |
| **2** | im, like, message, didnt, people, dont, chat, time, app, listener |
| **3** | talking, good, ai, really, wysa, app, help, talk, feel, like |
| **4** | people, love, nice, easy, work, good, meditation, use, great, app |
| **5** | day, ive, im, far, good, thought, help, really, helpful, app |

---

## 📈 Dataset Size

- Initial run: **65,000 reviews**
- Expanded analysis: **160,000 reviews**

---

## 🧰 Tools & Libraries

- **Python**
- **SpaCy** – NER
- **NLTK** – Preprocessing, stopwords
- **VADER** – Sentiment analysis
- **Gensim** – LDA topic modeling
- **scikit-learn** – TF-IDF, clustering
- **Transformers (HuggingFace)** – DistilBERT-based personality prediction

---

## 📊 Applications

- Market analysis for mental health startups.
- Persona-based feature prioritization.
- User-centric mental health product design.
- Identifying unserved emotional needs and app trust gaps.

---

## 👤 Author

**Siddharth Palod**  
Focus: NLP, Behavioral Analytics, and Mental Health Tech

---

