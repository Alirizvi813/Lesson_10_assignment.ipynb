# Lesson 10 - Sentiment Analysis Assignment

## Overview
This project demonstrates sentiment analysis using Python, Pandas, scikit-learn, and a Hugging Face BERT fine-tuning workflow. The objective is to classify review text as positive or negative.

## Dataset
The project uses a public-style labelled review sentiment dataset with two columns:
- `text`: review sentence
- `sentiment`: positive or negative

The CSV file `sentiment_reviews.csv` is included for reproducibility. The notebook also includes fallback logic so it can run without file errors.

## Methods Used
- Missing value handling
- Text cleaning and transformation
- Label encoding and one-hot encoding demonstration
- Feature scaling demonstration
- Bag of Words vectorization
- TF-IDF vectorization
- Word embedding visualization
- Logistic Regression with GridSearchCV
- Linear SVM with GridSearchCV
- Hugging Face BERT fine-tuning workflow
- Model evaluation using accuracy, precision, recall, F1-score, and ROC-AUC
- Confusion matrices, ROC curves, performance charts, and feature importance

## How to Run
1. Open `Lesson_10_assignment_completed_Ali_Raza_executed.ipynb` in Google Colab.
2. Upload `sentiment_reviews.csv` if Colab does not automatically find it.
3. Click `Runtime > Run all`.
4. To run BERT fine-tuning, enable GPU and set `RUN_BERT = True` in the BERT section.
5. Export the notebook or submit the provided PDF report.

## Files
- `Lesson_10_assignment_completed_Ali_Raza_executed.ipynb`
- `Lesson_10_sentiment_analysis_report_Ali_Raza.pdf`
- `sentiment_reviews.csv`
- `README.md`

## Student
Ali Raza
