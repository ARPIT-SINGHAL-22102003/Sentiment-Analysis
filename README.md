# 🧠 AI-Driven Customer Feedback Analysis Pipeline

This project analyzes customer feedback using sentiment classification, keyword extraction, and insight generation. It helps teams identify pain points, highlight strengths, and make data-driven decisions to improve customer experience.

---

## 🚀 Features

- 🔍 Sentiment classification (positive, neutral, negative)
- 🧠 Keyword extraction for insight generation
- 📊 Category-level feedback aggregation
- ⚠️ Urgency detection via keyword flags
- 📈 Power BI dashboard integration (optional)
- 🧾 Auto-generated insights for reporting

---

## 🔧 What We Used

### 📦 Data Handling & Preprocessing
- `pandas` – for reading, cleaning, and transforming feedback data  
- `re` – for basic text normalization and keyword flagging  

### 🧠 NLP & Sentiment Analysis
- `transformers` – for sentiment classification using a pre-trained model (e.g., DistilBERT)  
- `scikit-learn` – for keyword extraction using `CountVectorizer`  
- Manual keyword flags – to detect urgency phrases like “ASAP”, “not working”, “immediately”

### 📊 Reporting & Visualization
- `matplotlib`, `seaborn` – for sentiment distribution and category-level charts  
- Markdown templates – for generating structured insights reports

---
