## Sentiment_analysis

COMPANY : CODTECH IT SOLUTIONS

NAME : SHREYA YADAV

INTERN ID : CT04DG3452

DOMAIN : MACHINE LEARNING

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH


# 📂 Sentiment Analysis on Flipkart Product Reviews

This project applies Natural Language Processing (NLP) techniques to perform sentiment classification on real-world product reviews from Flipkart. The goal is to determine whether a customer’s review is positive or negative based on the text content, providing valuable insights into customer satisfaction and product perception. By using standard NLP preprocessing, TF-IDF vectorization, and a Logistic Regression classifier, the project highlights how even simple models can produce powerful results with the right data preparation.

📂 Dataset Overview
The dataset used in this project is sourced from Kaggle:
👉 Flipkart Product Reviews Dataset : https://www.kaggle.com/datasets/hrithiqgupta/flipkart-product-reviews-for-sentient-analysis

It contains multiple features including:

ProductName
Price
Rate (numerical product rating)
Review (detailed user text)
Summary (short text summary of the review)
For sentiment classification, the Rate column is used to derive the target sentiment:

Ratings of 4 and 5 are labeled as Positive (1)
Ratings of 1 and 2 are labeled as Negative (0)
Rating 3 is considered neutral and optionally filtered out to maintain binary classification balance.
🔧 Techniques Used
To prepare the data for machine learning, several text preprocessing techniques were applied:

Lowercasing all text for uniformity
Removing punctuation and numbers to reduce noise
Stopword removal to eliminate irrelevant words
Tokenization for structured text input
The cleaned text was transformed into numerical vectors using TF-IDF (Term Frequency–Inverse Document Frequency), a widely-used method to quantify text importance in NLP tasks. This sparse representation feeds into the Logistic Regression classifier, a simple yet effective model for binary sentiment classification.

The dataset was split into training and test sets using stratified sampling, ensuring balanced class distribution. Evaluation of the model included:

Accuracy score
Precision, Recall, and F1-score using Scikit-learn’s classification_report
Confusion Matrix visualized with Seaborn heatmap to see false positives/negatives clearly
📈 Output & Results
Depending on the dataset split and preprocessing, the Logistic Regression model achieved a strong accuracy of around 85–90%. The confusion matrix provided a visual understanding of where the model performs well and where it might confuse sentiments.

The classification report further detailed how well the model balances precision and recall, which is important in sentiment analysis to avoid mislabeling customer feedback.

💡 Key Learnings
Even basic algorithms like Logistic Regression can perform very well with clean and well-preprocessed data
TF-IDF remains one of the most powerful feature extraction tools in NLP for transforming raw text into meaningful numerical data
Balancing the dataset (removing neutral reviews or handling class imbalance) significantly impacts model performance
Visualization through confusion matrices helps identify misclassifications and improve model tuning
📎 Resources
🗂️ Kaggle Dataset: Flipkart Product Reviews(https://www.kaggle.com/datasets/hrithiqgupta/flipkart-product-reviews-for-sentient-analysis)
📘 Scikit-learn Docs: Logistic Regression (https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)


