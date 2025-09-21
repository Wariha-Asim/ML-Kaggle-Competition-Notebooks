
# 🎬 Sentiment Analysis on IMDB Movie Reviews

> **Note:** This is a Jupyter Notebook (`.ipynb`) file. You can open it in Jupyter, Colab, or directly on Kaggle.

## 📌 Project Overview
This project applies **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques to classify IMDB movie reviews as **Positive (1)** or **Negative (0)**.  

The pipeline includes **data preprocessing, feature extraction, multiple model training, performance evaluation, and visualization** to identify the best-performing sentiment classification model.

- **Kaggle Notebook:** [Sentiment Analysis on IMDB Movie Reviews](https://www.kaggle.com/code/waarihaasim/sentiment-analysis-on-imdb-movie-reviews)



## 📊 Dataset
- **Source:** [IMDB Movie Review Dataset]  
- **Size:** 50,000 labeled reviews  
- **Features:**  
  - `review`: text content of movie reviews  
  - `sentiment`: target label (0 = Negative, 1 = Positive)  


## ⚙️ Project Features

### 🔍 Data Preprocessing
- Removed **HTML tags, punctuation, numbers, and special characters**  
- Converted text to **lowercase**  
- Applied **tokenization, stopword removal, and lemmatization**  
- Balanced and shuffled dataset for fair training  

### 🧩 Feature Extraction
- **Bag-of-Words (CountVectorizer)**  
- **TF-IDF Vectorization** (for SVM model)  

### 🤖 Machine Learning Models
1. **Naïve Bayes**  
   - Quick baseline model with moderate accuracy  

2. **Logistic Regression**  
   - Strong linear model  
   - Balanced precision and recall  

3. **Support Vector Machine (SVM)**  
   - Implemented with TF-IDF features  
   - Tuned on sampled dataset (10,000 reviews)  
   - Best overall performance  


## 📊 Model Evaluation
- Metrics: **Accuracy, Precision, Recall, F1-Score, Confusion Matrix, ROC-AUC**  
- Side-by-side comparison of all models  
- Ranking based on key metrics  


## 📈 Visualizations
- **Confusion Matrix Heatmap** (best model)  
- **Word Clouds** for Positive & Negative reviews  
- **Histograms of Review Length** (Positive vs Negative)  
- **Bar Chart & Histogram of Review Length Distribution** by categories (Short, Medium, Long)  


## 🏆 Results & Best Model
- **Naïve Bayes** → Good baseline, fast but less accurate  
- **Logistic Regression** → Reliable, balanced performance  
- **SVM** → **Highest overall performance**  

✅ **Selected Best Model: Support Vector Machine (SVM)**  
- Accuracy: ~**86%**  
- Precision/Recall: High & consistent  
- ROC-AUC: Excellent  

## Project Structure:
🎬 Sentiment Analysis on IMDB Movie Reviews/
│
├── 🎬 Sentiment Analysis on IMDB Movie Reviews.ipynb
├── submission.csv


## 📌 Conclusion
This project demonstrates the power of **text preprocessing + ML models** in sentiment classification.  
The **SVM model with TF-IDF features** proved to be the best choice for analyzing IMDB reviews, achieving strong accuracy and robust evaluation metrics.



## 📂 Links
- **Kaggle Notebook:** [Sentiment Analysis on IMDB Movie Reviews](https://www.kaggle.com/code/waarihaasim/sentiment-analysis-on-imdb-movie-reviews)
