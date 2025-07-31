# resume-classification

## Resume Categorization with TF-IDF and Logistic Regression

This repository provides a machine learning pipeline that classifies resumes into relevant job categories. The workflow includes text preprocessing, feature extraction using TF-IDF, and classification via Logistic Regression.

---

## Project Goal

Develop a system that leverages NLP and machine learning to automatically assign job categories to resume texts.

---

## Dataset Structure

The input dataset should be a CSV file containing:

- **`Category`**: The corresponding job title or category (e.g., "Data Science", "HR", "Marketing").
- **`Resume`**: The raw text of the resume.

Example:

| Category       | Resume                                               |
|----------------|------------------------------------------------------|
| Data Science   | "Experienced in Python, SQL and Machine Learning..." |
| HR             | "Handled recruitment and employee engagement..."     |

---

## Preprocessing Workflow

- Tokenize text
- Convert to lowercase
- Remove stopwords
- Lemmatize using NLTK

---

## Pipeline Overview

1. Clean and preprocess resume text (NLTK)
2. Transform text data into numerical vectors using TF-IDF
3. Split data into training and testing sets
4. Train a Logistic Regression classifier
5. Assess performance with accuracy metrics and classification report

---

## Prerequisites

Install the following Python packages:

```bash
pip install pandas nltk scikit-learn
```
---

## Execution Steps

1. Ensure your dataset is named resume-contents.csv and placed in the project folder.
2. Start Jupyter Notebook.
3. Open and execute the notebook: Task1_Ronick_NLP.ipynb.

---

## Model Performance

<img width="630" height="696" alt="image" src="https://github.com/user-attachments/assets/5f096051-0bbb-486c-bff8-24b392cdf109" />

---

## Potential Enhancements

- Experiment with other models (e.g., SVM, BERT)
- Integrate resume parsing and keyword extraction features
- Create a web portal for resume uploads
