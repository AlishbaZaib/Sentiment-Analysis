# Sentiment Analysis on Amazon Product Reviews

This project focuses on performing **sentiment analysis** using real-world customer reviews from Amazon. The goal is to classify each review as either **positive** or **negative** using **Natural Language Processing (NLP)** and **machine learning techniques**.



## Project Objectives

- Load and explore a real-world Amazon reviews dataset  
- Clean and preprocess text data for NLP tasks  
- Convert text into numerical features using **TF-IDF vectorization**  
- Build and evaluate classification models: **Logistic Regression** and **Naive Bayes**  
- Compare model performance using evaluation metrics  
- Visualize word frequency using **WordClouds**



## Dataset Details
 
- **Source**: [Kaggle – Consumer Reviews of Amazon Products](https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products)  
- **Key columns used**:  
  - `reviews.text`  
  - `reviews.rating`


## Models Used

- Logistic Regression  
- Multinomial Naive Bayes



## Tools & Technologies

- Python  
- Pandas, NumPy  
- NLTK (Natural Language Toolkit)  
- Scikit-learn  
- TF-IDF Vectorizer  
- Matplotlib  
- WordCloud  



## 📊 Results

- **Logistic Regression** achieved slightly higher accuracy and F1-score  
- **Naive Bayes** was faster and still performed well  
- **WordClouds** helped visualize frequently used words in both sentiment categories


