# Fake-News-Detection Web Application

## Overview

This project is an NLP and Machine Learning based web application that detects whether a news article is REAL or FAKE.

## Features

* NLP text preprocessing
* TF-IDF vectorization
* Machine learning prediction
* Interactive Streamlit dashboard
* Real-time fake news detection
* Confidence score display

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* spaCy
* Streamlit
* Matplotlib
* Seaborn

## Machine Learning Models

* Logistic Regression
* Passive Aggressive Classifier
* Naive Bayes

## How to Run

### Install libraries

pip install -r requirements.txt

### Download spaCy model

python -m spacy download en_core_web_sm

### Run dashboard

streamlit run app.py

## Project Structure

Fake-News-Detection/
│
├── app.py
├── model_training.py
├── data_cleaning.py
├── fake_news_model.pkl
├── tfidf_vectorizer.pkl
└── README.md

## Future Improvements

* BERT model integration
* News URL scraping
* Live news API
* User authentication
* Deployment on cloud
