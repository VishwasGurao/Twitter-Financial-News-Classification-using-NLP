# Twitter Financial News Classification using NLP

## 📌 Project Overview
This project focuses on building an end-to-end Natural Language Processing (NLP)
pipeline to classify Twitter financial news into multiple financial categories.
The emphasis is on practical feature engineering, model comparison, and
real-world decision-making under limited computational resources.

---

## 🎯 Objective
- Classify financial news tweets into predefined categories
- Perform exploratory data analysis to understand data distribution
- Compare multiple classical machine learning models
- Select an efficient and reliable model based on performance and practicality

---

## 📂 Dataset Overview
- Twitter posts related to financial markets and events
- Multi-class classification problem
- Real-world class imbalance across categories
- Short and noisy text typical of social media platforms

---

## 📊 Exploratory Data Analysis (EDA)
Key insights from EDA:
- Strong class imbalance across financial categories
- Significant variation in tweet length by category
- Majority classes dominate overall distribution
- Minority classes contain limited but meaningful information

---

## 🛠 Feature Engineering
- Text cleaning and normalization
- Removal of low-information samples
- TF-IDF vectorization with unigrams and bigrams
- Feature dimensionality control for efficiency

---

## 🤖 Models Implemented

### 1. Logistic Regression (Baseline)
- Served as the primary benchmark model
- Stable and interpretable performance
- Applied class weighting to handle imbalance

### 2. Multinomial Naive Bayes
- Fast and computationally efficient
- Performed well on majority classes
- Sensitive to class imbalance

### 3. Linear Support Vector Machine (SVM)
- Best overall classical model
- Strong performance on high-dimensional sparse text
- Improved separation between similar categories

---

## 📈 Model Evaluation
- Fair comparison using identical preprocessing and TF-IDF features
- Stratified train–test split
- Confusion matrix and classification metrics used for evaluation
- Linear SVM selected as the final classical model

---

## 🧠 Deep Learning Exploration (BERT)
A BERT-based model was initiated to explore deep learning approaches.
However, due to CPU-only hardware constraints and long training time,
the model was intentionally stopped.

This reflects a practical engineering trade-off between model complexity,
computational resources, and project timelines.

---

## ✅ Final Outcome
- End-to-end NLP pipeline successfully implemented
- Multiple models evaluated and compared
- Linear SVM identified as the most effective classical approach
- Project completed with strong practical insights

---

## 🚀 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Natural Language Processing (NLP)

---

## 📌 Project Status
**Completed** – Interview-ready and GitHub-ready NLP project
