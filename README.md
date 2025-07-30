# Financial News Headline Sentiment Analysis

This is an **NLP-based machine learning project** that focuses on classifying the **sentiment of financial news headlines** into three categories: **Positive, Negative, or Neutral**.

Understanding sentiment in financial news can provide valuable insights into market behavior and potential trends.

---

## 📌 Objective

To build a machine learning model that can accurately predict the **sentiment of financial news headlines**, which can assist in interpreting market sentiments and forecasting possible market movements.

---

## 🧰 Tools & Libraries Used

- Python  
- Pandas  
- NumPy  
- NLTK  
- Scikit-learn  
- VADER Sentiment Analyzer  
- Matplotlib & Seaborn  
- Imbalanced-learn (SMOTE)

---

## 🔍 Workflow Summary

### 1. **Data Exploration**
- Loaded and analyzed the dataset from **kaggle**.
- Checked for null values, class distribution, and headline lengths.

### 2. **Text Preprocessing**
- Handled non-string entries.
- Removed punctuation & special characters (kept numbers).
- Lowercased the text.
- Tokenized and lemmatized.
- Stopwords were retained due to contextual relevance.

### 3. **Feature Engineering**
- **TF-IDF Vectorization**  
- **Custom features** such as:
  - Cleaned word count  
  - Average word length  
  - VADER sentiment scores  
  - Positive/Negative word counts (based on Opinion Lexicon)

### 4. **Handling Class Imbalance**
- Applied **SMOTE** to balance the training dataset due to a dominance of neutral headlines.

### 5. **Model Training**
- Tried multiple models — finalized on **Logistic Regression**.
- Trained on SMOTE-resampled data.
- Achieved **~75% accuracy** on test data.

### 6. **Real-world Testing**
- Tested on actual financial news headlines.
- The model was able to predict the sentiment with consistent results.

---

## ✅ Results

The Logistic Regression model trained with engineered features and balanced data achieved **approximately 75% accuracy**, showing good potential for real-world applications.

---


## 📌 Conclusion

This project is a demonstration of using **Natural Language Processing (NLP)** techniques in the financial domain to extract meaningful sentiment from textual data. It combines traditional ML techniques with domain-specific feature engineering for better performance.

---

## 🔗 Connect with Me

📧 [Amit Dubey – LinkedIn](https://www.linkedin.com/in/amit-dubey-analytics/)  
📁 [More Projects on GitHub](https://github.com/amitdubey4)

