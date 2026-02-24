# 📊 Sentiment Analysis 

## 🧾 Project Objective
The objective of this project is to perform Sentiment Analysis on textual data  using Natural Language Processing (NLP) techniques.  
The goal is to classify tweets as **Positive** or **Negative** and extract meaningful insights from user opinions.

---

## 📂 Dataset Used


## Dataset used
- <a href="https://github.com/SaiKumar77s/Sentiment-Analysis/blob/main/traning_data.csv">Dataset</a>


- Dataset: Sentiment140 (Twitter Sentiment Dataset)
- Total Records: 1.6 Million Tweets (Trimmed to 10K for faster processing)
- Target Classes:
  - 0 → Negative
  - 4 → Positive

---

## 🎯 Project Tasks (KPIs)

- Perform text preprocessing (cleaning, stopword removal, stemming)
- Convert text data into numerical format using TF-IDF
- Train Machine Learning model for sentiment classification
- Evaluate model performance using accuracy and confusion matrix
- Test model with custom user input
- Extract key insights from sentiment distribution

---

## ⚙️ Process

1. Loaded and explored dataset.
2. Cleaned text data:
   - Converted to lowercase
   - Removed URLs, mentions, special characters
   - Removed stopwords
   - Applied stemming
3. Performed Feature Extraction using TF-IDF Vectorizer.
4. Split dataset into Training and Testing sets (80/20).
5. Trained Logistic Regression model.
6. Evaluated model using:
   - Accuracy Score
   - Classification Report
   - Confusion Matrix
7. Built prediction function for real-time sentiment testing.

---

## 🛠 Tools & Technologies Used

- Python
- Google Colab
- Pandas
- NLTK
- Scikit-learn
- Matplotlib & Seaborn

---

## 📊 Model Performance

- Model Used: Logistic Regression
- Accuracy Achieved: ~80% to 85%
- Balanced performance on both Positive and Negative classes.

---

## 📌 Conclusion

- This project successfully performed Sentiment Analysis on Twitter data using NLP techniques. 
- After preprocessing and applying TF-IDF, a Logistic Regression model was trained to classify tweets as Positive or Negative. 
- The model achieved good accuracy and demonstrated how machine learning can be used to analyze public opinion and customer feedback effectively.


## 🔍 Key Insights

- Balanced dataset improves classification performance.
- Preprocessing significantly improves accuracy.
- TF-IDF effectively captures important textual features.
- Logistic Regression performs well for binary sentiment classification.
- Model can be extended using LSTM or BERT for better accuracy.

---

## 📌 Future Improvements

- Implement Deep Learning models (LSTM)
- Use Transformer-based models (BERT)
- Perform Multi-class Sentiment Analysis
- Deploy model as a Web Application

---

