# Phishing Email Detection Using Machine Learning 📧🔐

### Project Overview 🔭
This project focuses on building a machine learning model to detect phishing emails based on text analysis. The goal is to preprocess email text data, apply classification algorithms, and evaluate their effectiveness in identifying phishing emails. 

The analysis includes:
- Text preprocessing using **TF-IDF** vectorization.
- Training machine learning models to classify phishing and legitimate emails.
- Evaluating model performance using metrics like accuracy score, F1-score, and feature importance.

Accuracy Score: It calculates the percentage of correctly classified instances.
F1 Score: 
**Precision**: Of all the predictions the model made for a certain class (like phishing emails), how many of those predictions were correct?
**Recall**: Out of all the actual positive cases (real phishing emails), how many did the model correctly identify?
The F1 Score provides a **harmonic mean** of precision and recall, meaning it gives a balanced measure.
### F1 Score Formula:
$$
F1 = 2 \times \frac{\text{Precision} \times \text{Recall}}{\text{Precision} + \text{Recall}}
$$

### Dataset 📊
The dataset used for this project is sourced from [Kaggle: Phishing Emails Dataset](https://www.kaggle.com/datasets/subhajournal/phishingemails/data). It contains a collection of email texts labeled as either **Phishing** or **Legitimate** (Ham). The dataset is used to train and evaluate the machine learning models.

