# Sentiment-analysis
Sentiment analysis using count vectorizer and multinomial naive bias.
# Sentiment Analysis using Naive Bayes (NLP Project)

## Project Overview

This project implements a **Sentiment Analysis system** using Natural Language Processing (NLP).
The goal of the model is to classify text messages into **Positive, Negative, or Neutral sentiment**.

The project demonstrates the complete **NLP pipeline**, including data exploration, text vectorization, model training, and evaluation using machine learning techniques.
## Dataset
* Total samples: **585**
* Columns: **2**

  * `message` – text input
  * `sentiment` – target label (Positive / Negative / Neutral)

### Sentiment Distribution

* Positive: 259
* Negative: 178
* Neutral: 167
* 
## Technologies Used

* Python
* Jupyter Notebook
* Scikit-learn
* Pandas
* NumPy

## Project Workflow

### 1. Data Exploration

* Analyzed sentiment distribution
* Checked for missing values
* Observed common patterns in text data

### 2. Text Vectorization

Used **CountVectorizer** to convert text into numerical features using the Bag-of-Words approach.

### 3. Label Encoding

Used **LabelEncoder** to convert sentiment labels into numeric values so they can be used by the machine learning model.

### 4. Train-Test Split

Split the dataset into:

* **80% training data**
* **20% testing data**

### 5. Model Training

Trained a **Multinomial Naive Bayes classifier**, which works well for text classification tasks with word frequency features.

### 6. Model Evaluation

Evaluated the model using:

* Accuracy

  
## Results

* Model: **Multinomial Naive Bayes**
* Accuracy: **~86%**

The model performs well considering the **small dataset size** and simple feature representation.

## Key Concepts Used

* Natural Language Processing (NLP)
* Bag of Words
* Count Vectorization
* Label Encoding
* Naive Bayes Classification
* Train/Test Split
  
Created as part of an **NLP learning project** to understand text preprocessing, vectorization, and sentiment classification using machine learning.
