# SENTIMENT-ANALYSIS

COMPANY:CODTECH IT SOLUTIONS

NAME :BANOTH KAVYA

INTERN ID :CT06DK441

DOMAIN: DATA ANALYTICS

DURATION:6 WEEKS

MENTOR:NEELA SANTHOSH

**Twitter Sentiment Analysis using NLP & Naive Bayes**

This project performs sentiment classification on tweet text data using Natural Language Processing (NLP) techniques and the Multinomial Naive Bayes algorithm. The model predicts whether a tweet has a positive (1) or negative (0) sentiment.

**📌 Project Overview**

This project covers an end-to-end pipeline for sentiment analysis:

Data preprocessing and text cleaning

Exploratory Data Analysis (EDA)

Feature extraction using Bag of Words (CountVectorizer)

Training and evaluating a Naive Bayes classifier

Visualizing most frequent positive/negative words with bar plots and word clouds

**📂 Dataset**

The dataset used is a CSV file named train.csv, containing two columns:

label: Sentiment class (0 = negative, 1 = positive)

tweet: Raw tweet text

**⚙️ Tech Stack**

Python

Libraries: pandas, NumPy, Matplotlib, Seaborn, NLTK, Scikit-learn, WordCloud

**📈 Workflow**

**1.Load & Inspect Data**

Preview structure and class distribution

Visualize sentiment labels using countplot

**2.Text Preprocessing**

Lowercasing, removing URLs, mentions, punctuation

Stopword removal and stemming using NLTK

**3.Vectorization**

Use CountVectorizer to convert cleaned text to numerical feature vectors

**4.Model Training**

Split data into training and test sets (80/20 split)

Train a Multinomial Naive Bayes model

**5.Model Evaluation**

Calculate accuracy, generate classification report, and visualize confusion matrix

**6.Insights**

Generate word clouds for positive and negative sentiments

Display top 10 frequent words for both classes using bar plots

**📊 Sample Results**

Accuracy: ~ (as per your run)

Top Words:

Positive: love, thank, happi, good, etc.

Negative: hate, worst, sick, problem, etc.

**📁 Output Visuals**

task4_label_plot.jpg – Sentiment distribution

task4_con_matrix.jpg – Confusion matrix

task4_pos_word.jpg – Word cloud for positive tweets

task4_neg_word.jpg – Word cloud for negative tweets

task4_negative.jpg – Bar plots of most common words

**✅ Conclusion**

This project demonstrates how basic NLP techniques combined with classical ML algorithms like Naive Bayes can be used to build effective text classifiers. It's lightweight, fast, and easy to deploy for social media sentiment monitoring.

**Output Picture**

![Image](https://github.com/user-attachments/assets/7e4d61c4-57c4-4068-87aa-b71864c0ac3c)
![Image](https://github.com/user-attachments/assets/fd813d2d-c625-4c8c-95f0-9d558ce465e5)
![Image](https://github.com/user-attachments/assets/9a7ec1c3-19b2-4f41-ba2e-1595aeb76ebb)
![Image](https://github.com/user-attachments/assets/22866cdc-8ea5-4b6d-9250-5c9c57ac1d33)
![Image](https://github.com/user-attachments/assets/02649739-1a49-4408-a96c-4cf14bf081be)
