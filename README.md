# Phishing & Spam Email Detection

An NLP and machine learning project for detecting phishing/spam emails and legitimate (ham) emails.

## Project Overview

Phishing and spam emails are common cybersecurity threats. This project uses Natural Language Processing (NLP) and machine learning techniques to classify emails as:

- Ham (legitimate email)
- Phishing/Spam

## Datasets

The project combines email datasets from:

- Enron
- Ling
- CEAS
- Nazario
- Nigerian Fraud
- SpamAssassin

The datasets are merged into a single dataset for classification.

## Methodology

The main steps are:

1. Load and combine multiple email datasets
2. Handle missing values
3. Combine email information such as sender, date, subject, and body
4. Clean and preprocess the text
5. Split the data into training and testing sets
6. Convert text into numerical features using TF-IDF
7. Train machine learning models
8. Evaluate model performance
9. Perform a robustness experiment

## Machine Learning Models

The project uses:

- Support Vector Machine (SVM)
- Multinomial Naive Bayes
- Random Forest

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- AUC-ROC
- Confusion Matrix

## Robustness Experiment

The project also tests how consistently the models classify emails when small changes are made to the text, including:

- Extra spaces
- Changes in capitalization
- Additional harmless words

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF
- Natural Language Processing (NLP)
- Google Colab

## Project File

- `phishing_spam_email_detection.py` — Main Python implementation.

## Author

**Fatima Hashimi**

Computer Science Student  
Asian University for Women (AUW)
