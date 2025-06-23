# 📱 SMS Spam Detector using Machine Learning

A complete end-to-end machine learning project that detects spam messages using Natural Language Processing techniques.

## 💡 Project Overview

This project trains a classifier to detect whether an SMS message is spam or not. It includes text preprocessing (tokenization, stopword removal, stemming), vectorization with TF-IDF, and training with Multinomial Naive Bayes.

## 🚀 Tools Used
- Python
- Pandas, NLTK, Scikit-learn
- TF-IDF Vectorizer
- Multinomial Naive Bayes

## 📊 Model Performance

| Metric        | Score   |
|---------------|---------|
| Accuracy      | 96.6%   |
| Precision     | 100%    |
| Recall        | 74.7%   |
| F1 Score      | 85.5%   |

✅ Excellent spam detection precision. Balanced F1-score despite class imbalance.

## 📦 Features
- Clean and stem raw SMS text
- Visualize data distribution
- Make real-time predictions using interactive input
- Evaluate using accuracy, precision, recall, F1, and confusion matrix

## 🔮 Sample Predictions

> "Congratulations! You've won a free iPhone!" → `Spam`  
> "Hey, are we still meeting later?" → `Ham`

📌 Built this project as part of my machine learning learning journey.



## 🧠 Conclusion & Reflection

This project gave me hands-on experience with end-to-end NLP pipelines — from raw text to predictions. I learned how to:
- Clean and preprocess real-world SMS messages
- Convert text to numerical features using TF-IDF
- Build and evaluate a machine learning model for spam detection
- Handle class imbalance and interpret model metrics

The high precision indicates that the model rarely misclassifies a legitimate message as spam, while recall can be improved to catch more spam.

Overall, this project boosted my confidence in working with real-world text data and using traditional ML techniques to solve practical problems.



## 🙋 Author 

👤 **Emmanuel J. Generale**  




## 📄 License
This project is licensed under the MIT License.
