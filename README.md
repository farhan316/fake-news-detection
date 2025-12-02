Fake News Detection using Machine Learning

This project detects whether a news article is Real or Fake using TF-IDF vectorization and ML models (Logistic Regression & SVM).

👨‍💻 Team Members

Muhammad Farhan
📚 Dataset
**ISOT Fake News Dataset**

~45,000 Articles

Balanced dataset

Columns: title, text, label

**🛠 Tech Stack**

Python

Scikit-Learn

NLTK

TF-IDF

SHAP

Matplotlib / Seaborn

Google Colab

**🔧 Preprocessing**

Lowercase

Stopword removal

Lemmatization

Punctuation removal

TF-IDF vectorization (5000 features)

Future Improvements

Use BERT / Transformers

Real-time fake news detector

Multi-class misinformation classification

Logistic Regression

SVM (LinearSVC)

Train/Test Split → 80/20

📊 Results
Model	Accuracy	F1 Score
Logistic Regression	~98%	~98%
SVM (LinearSVC)	~98%	~98%
🧠 Explainability

SHAP used for identifying the most influential words

Wordclouds for Real & Fake news

Confusion Matrix visualizations

**📌 Project Structure**
/fake-news-detection
│── fake_news.ipynb
│── report.pdf
│── README.md
│── images/
│     ├── confusion_matrix.png
│     ├── wordcloud_real.png
│     ├── wordcloud_fake.png
│     └── shap_words.png
│── requirements.txt

Future Improvements

Use BERT / Transformers

Real-time fake news detector

Multi-class misinformation classification
