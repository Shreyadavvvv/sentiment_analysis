# sentiment_analysis

# Sentiment Analysis on Flipkart Product Reviews

This project uses **Natural Language Processing (NLP)** techniques to classify customer reviews on Flipkart as **positive** or **negative**. It demonstrates the use of **TF-IDF vectorization**, **Logistic Regression**, and **confusion matrix visualization** for sentiment prediction.

---

## 📂 Dataset

- Source: [Flipkart Product Reviews Dataset](https://www.kaggle.com/datasets/hrithiqgupta/flipkart-product-reviews-for-sentient-analysis)
- Features: `ProductName`, `Price`, `Rate`, `Review`, `Summary`
- Target: `Rate` (converted to Sentiment: 1 = Positive, 0 = Negative)

---

## 🔧 Techniques Used 

- Text Preprocessing (lowercasing, punctuation removal, stopwords)
- TF-IDF Vectorization
- Logistic Regression (for binary classification)
- Train-Test Split with Stratification
- Evaluation using:
  - Accuracy
  - Precision, Recall, F1-Score
  - Confusion Matrix (Seaborn heatmap)

---
## 📈 Output

Model Accuracy: ~85–90% (depending on data split)
Confusion matrix heatmap
Classification report printed
💡 Learnings

The power of simple models like Logistic Regression when paired with strong preprocessing
Importance of balanced data and neutral filtering in sentiment tasks
Hands-on with TF-IDF as a powerful feature extractor in NLP

##📎Resources

Kaggle Dataset : https://www.kaggle.com/datasets/hrithiqgupta/flipkart-product-reviews-for-sentient-analysis
Scikit-learn Docs : https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html

