✅

📰 Fake News Detection Using Machine Learning
📌 Project Summary
This project focuses on detecting fake news articles using various machine learning algorithms. The dataset used consists of 20,000 labeled news articles, each classified as either "fake" or "real". The objective was to build a robust classifier that can accurately distinguish between misleading and authentic news content.

📊 Dataset Overview
Total Rows: 20,000 news articles

Columns: title, text, label (target)

Classes:

fake – News that is false or misleading

real – Legitimate news articles

🧪 Approach
Data Preprocessing:

Text cleaning (lowercasing, punctuation & stopword removal)

Label encoding

TF-IDF vectorization for feature extraction

Model Building:
Three different machine learning models were trained and evaluated:

✅ Naive Bayes

✅ Linear Support Vector Machine (SVM)

✅ XGBoost Classifier

Pipeline Creation:

A complete machine learning pipeline was built using scikit-learn to combine preprocessing and model training steps seamlessly.

Each model was trained and validated using the same pipeline to ensure fair comparison.

Model Evaluation:

All models were evaluated based on accuracy, precision, recall, and F1-score.

Based on the results, the best-performing model was selected for deployment.

