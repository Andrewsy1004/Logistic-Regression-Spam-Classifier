# 📬 Logistic Regression Spam Classifier

This project implements a **Spam Email Classifier** using **Logistic Regression**, trained on a dataset of SMS messages. The model distinguishes between **ham** (non-spam) and **spam** messages. This project demonstrates how to process text data, apply machine learning, and evaluate model performance. 

## 🚀 Features:
- **Text Preprocessing**: The text data is cleaned and transformed using **TF-IDF Vectorization**, which converts the raw text into numerical feature vectors.
- **Model Training**: A **Logistic Regression** model is trained to classify SMS messages as either "ham" or "spam".
- **Model Evaluation**: Performance metrics such as **accuracy**, **precision**, **recall**, and **F1-score** are used to evaluate the model's effectiveness.

## 📊 Steps:
1. **Data Preprocessing**:
   - The dataset is cleaned by removing stop words and converting all text to lowercase.
   - The text is transformed into numerical features using the **TF-IDF** vectorizer.
   
2. **Training**:
   - The **Logistic Regression** model is trained on the processed data.
   
3. **Evaluation**:
   - The model is evaluated on both training and test datasets using multiple performance metrics (accuracy, precision, recall, F1-score).
   
## 📋 Dependencies:
- `pandas`: For data manipulation and handling.
- `numpy`: For numerical operations.
- `scikit-learn`: For machine learning models, including logistic regression and vectorization.

