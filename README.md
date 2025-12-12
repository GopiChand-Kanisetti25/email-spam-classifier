# Project Structure
email-spam-classifier/
│
├── email_spam_classifier.ipynb   # Main Jupyter Notebook
├── requirements.txt              # Dependencies
└── dataset/                      # Dataset used (optional)

🔍 # Project Overview
The goal of this project is to detect whether an email is Spam or Ham using ML + NLP.

✔️ # Steps Involved
Data Cleaning & Preprocessing

Converting text into vectors using TF-IDF

Training ML models

Evaluating performance

Predicting spam/ham for new messages

🧹 # Text Preprocessing Includes
Lowercasing

Removing punctuation & special characters

Stopword removal

Tokenization

Stemming/Lemmatization (optional)

🧠 # Models Used

Logistic Regression

Multinomial Naive Bayes

Models are evaluated using:

Accuracy

Precision

Recall

F1-Score

📈 # Example Prediction
model.predict(["Congratulations! You won a free iPhone!"])
# Output → ['spam']

▶️ # How to Run
Install Dependencies:
pip install -r requirements.txt
# Run Notebook:
jupyter notebook email_spam_classifier.ipynb

📦 # Requirements
numpy
pandas
scikit-learn
nltk

🙋 Author
Gopi Chand
Aspiring Machine Learning & AI Engineer


