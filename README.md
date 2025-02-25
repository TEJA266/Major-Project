# 🧠 Detection of Depression-Related Posts in Reddit Social Media Forum

This project focuses on detecting depression-related posts on Reddit using **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques. The goal is to classify user-generated posts as depression-indicative (`1`) or non-depression (`0`), aiding in early detection and intervention.

## 📂 Dataset

- **Reddit Dataset** (Inna Pirina et al.): Contains 1,293 depression-indicative posts and 548 standard posts.
- **Twitter Dataset** (Kaggle): Includes 5,235 depression-indicative tweets and 6,199 standard tweets.

🔗 **Download Datasets:**
- [Reddit Depression Dataset](https://zenodo.org/record/3408290)
- [Twitter Depression Dataset](https://www.kaggle.com/datasets)

## 🚀 What Was Done

- **Data Preprocessing:**
  - Removed URLs, mentions, punctuation, and stop words.
  - Applied stemming and lemmatization for text normalization.
  
- **Feature Extraction:**
  - Used **TF-IDF**, **LIWC**, and **LDA** for extracting relevant features.
  
- **Model Training:**
  - Built and trained the following machine learning models:
    - Logistic Regression (LR)
    - Support Vector Machine (SVM)
    - Random Forest (RF)
    - Adaptive Boosting (AdaBoost)
    - Multi-Layer Perceptron (MLP)
    
- **Model Evaluation Metrics:**
  - Accuracy
  - Precision
  - Recall
  - F1-score

## 📊 Results

- **Best Performing Model:** Multi-Layer Perceptron (MLP) with 92% accuracy.
- **Key Insight:** LIWC and LDA feature combinations led to better model performance.

## 🔮 Future Work

- Extend the model for multilingual datasets and cross-platform analysis (Facebook, Instagram).
- Implement real-time monitoring and alerts for early detection.
- Enhance the model using deep learning methods like BERT or Transformer-based models.
- Collect more diverse data to improve model generalization.

## 📬 Contact

📧 **Email:** madamanchit@gmail.com  

