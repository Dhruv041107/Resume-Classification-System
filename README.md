# 🧠 Resume Classification System using Machine Learning

This project is a **Resume Classification System** that automatically predicts a candidate’s job domain (like *Engineer*, *Designer*, *HR*, *Finance*, etc.) from the text content of their resume using **Natural Language Processing (NLP)** and a **Random Forest Classifier**.  
It’s built and trained in Google Colab using a dataset of resumes and their respective job categories.

---

## 🚀 Overview

The goal of this project is to help recruiters or automated systems quickly identify the most relevant job domain of a resume by analyzing its text content.  
It leverages text vectorization (TF-IDF) and a tuned Random Forest model to achieve high accuracy on multi-class classification.

---

## 🧩 Features

- Cleans and preprocesses raw resume text data  
- Balances dataset across all job categories using upsampling  
- Converts text into numerical features using **TF-IDF Vectorization**  
- Trains a **Random Forest Classifier** with hyperparameter tuning via `RandomizedSearchCV`  
- Achieves an optimized accuracy of **≈ 85%**  
- Allows prediction of job category for any given resume text  
- Visualizes **feature importance** and **confusion matrix**

---

## 🗂️ Dataset

- **File used:** `clean_resume_data.csv`  
- **Columns:**
  - `ID`: Unique identifier for each resume
  - `Category`: Job domain (target label)
  - `Feature`: Resume text content  

- After balancing, there are ~2,800 records across 24 categories such as:
