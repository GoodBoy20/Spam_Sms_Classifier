#  SMS Spam Classifier

## 🚀 Live Demo

**Live Application:** https://spamsmclassifier.streamlit.app

**GitHub Repository:** https://github.com/GoodBoy20/Spam_Sms_Classifier

A machine learning-powered web application that classifies SMS messages as **Spam** or **Not Spam** using Natural Language Processing (NLP) techniques and a Multinomial Naive Bayes classifier.

## Overview

Spam messages are a common problem in digital communication. This project uses NLP and machine learning to automatically identify spam messages with high accuracy.

The application processes user input, performs text preprocessing, converts text into numerical features using TF-IDF vectorization, and predicts whether the message is spam or legitimate.

##  Features

* Real-time SMS classification
* Interactive web interface built with Streamlit
* Text preprocessing using NLTK
* TF-IDF feature extraction
* Multinomial Naive Bayes classifier
* Lightweight and fast predictions
* Achieved **97% accuracy** on the SMS Spam Collection Dataset

##  Tech Stack

* Python
* Streamlit
* Scikit-Learn
* Pandas
* NumPy
* NLTK
* Pickle

##  Machine Learning Pipeline

### 1. Data Preprocessing

The input text undergoes several preprocessing steps:

* Convert text to lowercase
* Tokenization
* Removal of special characters
* Stopword removal
* Stemming using Porter Stemmer

### 2. Feature Engineering

Text is converted into numerical vectors using:

* **TF-IDF Vectorization**

### 3. Model Training

The classifier is trained using:

* **Multinomial Naive Bayes**

### 4. Prediction

The trained model predicts whether a given SMS is:

* Spam 
* Not Spam 

##  Performance

| Metric     | Score                   |
| ---------- | ----------------------- |
| Accuracy   | 97%                     |
| Algorithm  | Multinomial Naive Bayes |
| Vectorizer | TF-IDF                  |

##  Project Structure

```text
sms-spam-classifier/
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── spam.csv
├── SMS_Spam_Detection.ipynb
├── requirements.txt
└── README.md
```

##  Installation

### Clone the Repository

```bash
git clone <repository-url>
cd sms-spam-classifier
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

The application will open automatically in your browser.

##  Example Messages

### Spam

```text
Congratulations! You have won ₹50,000. Click here to claim your reward.
```

### Not Spam

```text
Hey, are we meeting for the project discussion at 5 PM?
```

##  Dataset

This project uses the SMS Spam Collection Dataset containing thousands of labeled SMS messages categorized as spam or ham (not spam).

##  Future Improvements

* Deploy on Streamlit Cloud
* Add probability/confidence scores
* Experiment with Logistic Regression and XGBoost
* Use Word Embeddings and Deep Learning models
* Support email spam detection

##  Author

**Lokesh**
