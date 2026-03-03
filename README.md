📧 Smart Email Spam Detection System

A Machine Learning based web application that classifies emails as Spam, Not Spam, or Suspicious using confidence levels.
Built with Streamlit and Scikit-Learn.

Features

Predicts whether an email is Spam or Not Spam
Shows prediction confidence (probability scores)
Displays visual progress bars
Handles low-confidence cases as "Suspicious"
Simple and user-friendly interface

🧠 Model Details

Algorithm: Machine Learning Classifier
Text Vectorization: TF-IDF
Confidence Thresholds:
Spam > 0.7
Not Spam < 0.3
Between 0.3–0.7 → Suspicious

📂 Project Structure

Email_spam_detection/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── model/
│   ├── spam_model.pkl
│   └── vectorizer.pkl
│
└── data/  (not uploaded)    dataset link: https://www.kaggle.com/datasets/purusinghvi/email-spam-classification-dataset

⚙ Installation

1️⃣ Clone Repository
git clone https://github.com/codex-anish/Email_spam_detection.git
cd Email_spam_detection

3️⃣ Install Dependencies
pip install -r requirements.txt

▶ Run the Application
streamlit run app.py

App will open in your browser.

📊 Requirements

Python 3.10
streamlit
scikit-learn
joblib
