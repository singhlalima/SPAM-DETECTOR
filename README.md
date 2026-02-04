#  Spam Email Detection using NLP & Machine Learning

An end-to-end Natural Language Processing (NLP) project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using Machine Learning techniques.

This project demonstrates text preprocessing, feature engineering, and model building using Scikit-learn.

---

##  Features

- Text preprocessing (tokenization, cleaning, stopword removal)
- TF-IDF vectorization for feature extraction
- Naive Bayes & Logistic Regression models
- Train–test split and performance evaluation
- End-to-end ML pipeline implementation

---

##  Dataset

- 5,500+ SMS messages
- Labels: Spam / Ham
- Format: TSV (Tab Separated Values)

---

##  Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

##  Workflow

1. Load dataset
2. Clean and preprocess text
3. Convert text → numerical vectors (TF-IDF)
4. Train classification model
5. Evaluate accuracy
6. Predict new messages

---

##  Results

- Achieved **96–98% accuracy** on unseen test data
- Generated 8,000+ textual features using TF-IDF
- Automated spam detection, reducing manual filtering effort

---

##  Project Structure

SPAM-DETECTOR/
│── spam_email_classifier.ipynb
│── sms.tsv
│── README.md


---

##  How to Run

```bash
pip install pandas numpy scikit-learn matplotlib
jupyter notebook

spam_email_classifier.ipynb

Run all cells.

