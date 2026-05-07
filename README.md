# Public Sector Sentiment Analysis on Sri Lankan YouTube Comment Data (2020–2025)
---

## Overview

This research focuses on analyzing citizen sentiment related to Sri Lankan public sector issues using YouTube comment data collected between 2020 and 2025.

The study applies Natural Language Processing (NLP) and Machine Learning techniques to classify Sinhala and multilingual YouTube comments into positive, negative, and neutral sentiment categories. The research mainly investigates public opinion regarding government policies, fuel shortages, electricity supply, healthcare, taxation, transportation, education, and the economic crisis in Sri Lanka.

Using TF-IDF vectorization and Logistic Regression classification, the system evaluates citizen sentiment trends and explores the effectiveness of machine learning approaches in low-resource multilingual environments.

---

## Research Objectives

- Analyze citizen sentiment on Sri Lankan public sector issues
- Classify YouTube comments into positive, negative, and neutral sentiments
- Evaluate machine learning performance on Sinhala multilingual text
- Identify sentiment trends during the Sri Lankan economic crisis
- Study the impact of class imbalance in sentiment classification
- Support evidence-based governance research using social media analytics

---

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Scikit-learn | Machine learning model development |
| Pandas | Data preprocessing and handling |
| NumPy | Numerical operations |
| TF-IDF Vectorizer | Feature extraction |
| Logistic Regression | Sentiment classification |
| YouTube Data API v3 | Data collection |
| Matplotlib | Data visualization |
| Seaborn | Confusion matrix visualization |
| Joblib | Model serialization |
| Regex (re) | Text preprocessing |

---

## Dataset Information

- Source: Sri Lankan YouTube news and public affairs channels
- Time Period: 2020–2025
- Total Raw Comments: 7,000
- Cleaned Comments: 2,500
- Labeled Comments: 1,000
- Unlabeled Comments: 1,500

### Sentiment Categories

- Positive
- Negative
- Neutral

### Public Sector Topics

- Government policy
- Fuel shortages
- Electricity supply
- Taxation
- Economic crisis
- Healthcare
- Education
- Transportation

---

## Methodology

1. Data Collection using YouTube API
2. Data Cleaning and Preprocessing
3. Sinhala Text Filtering
4. Manual Data Annotation
5. TF-IDF Feature Extraction
6. Logistic Regression Model Training
7. Class Balancing
8. Model Evaluation
9. Sentiment Prediction
10. Data Visualization and Analysis

---

## Model Performance

| Metric | Baseline Model | Balanced Model |
|---|---|---|
| Accuracy | 61% | 65% |
| Neutral Recall | 0.11 | 0.39 |
| Positive Recall | 0.09 | 0.64 |
| Macro F1-Score | 0.36 | 0.60 |

---

## Overall Sentiment Distribution

| Sentiment | Percentage |
|---|---|
| Negative | 67.3% |
| Neutral | 27.1% |
| Positive | 5.6% |

---

## Key Findings

- Negative sentiment dominated discussions related to public sector issues during the economic crisis period.
- Logistic Regression showed moderate but meaningful performance for Sinhala sentiment classification.
- Class balancing significantly improved minority sentiment detection.
- Sinhala NLP presents challenges due to code-mixing, informal language, and limited resources.
- Social media sentiment analysis can support data-driven governance and policy evaluation.

---

## Applications

- Public opinion analysis
- Government policy monitoring
- Citizen feedback analysis
- Social media analytics
- Sinhala NLP research
- Smart governance systems
- Economic crisis sentiment tracking

---
## Demo Video

Project demonstration videos and related materials can be accessed here:

[View Demo Videos](https://drive.google.com/drive/folders/1HbTfLSImB3gkOSdrAXi-rOjJ-FwtVfiu?usp=sharing)

---

## Future Improvements

- Integrate transformer-based models such as mBERT and XLM-RoBERTa
- Add real-time sentiment monitoring dashboards
- Improve sarcasm and irony detection
- Expand multilingual support
- Increase labeled dataset size
- Apply deep learning approaches such as LSTM and Bi-LSTM

---

## Authors
- GGI Gamanayake
- Dulmi Subhashwaree
- JANI Jayawardhana

---

## License

This project is developed for academic and educational purposes only.
