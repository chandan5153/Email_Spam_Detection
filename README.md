# Email_Spam_Detection
🚀 Email Spam Detection using NLP and Machine Learning models (Naïve Bayes, SVM, Random Forest) with 98% accuracy and optimized via hyperparameter tuning.
# 📧 Email Spam Detection using NLP and Machine Learning

A machine learning project that detects spam emails using Natural Language Processing (NLP) techniques like TF-IDF and classifiers such as Naïve Bayes, Support Vector Machine, and Random Forest. Achieved 98% accuracy and suggested the best performing model through evaluation and hyperparameter tuning.

---

## 🚀 Features

- Natural Language Processing with NLTK
- Text preprocessing (cleaning, stemming, stopword removal)
- Feature extraction using CountVectorizer
- Trained three models: Naïve Bayes, SVM, Random Forest
- Hyperparameter tuning for model optimization
- Achieved 98% classification accuracy
- Confusion matrix and classification reports
- Exported model using `pickle`

---

## 📦 Installation

Create a virtual environment and install the dependencies:

```bash
# Optional: create and activate virtual environment
python -m venv .venv
.venv\Scripts\activate  # On Windows
# source .venv/bin/activate  # On Linux/macOS

# Install required packages
!pip install numpy pandas matplotlib seaborn scikit-learn nltk
Add the spam.csv file to test the data.
Finally run all cells and you can get the best model.
