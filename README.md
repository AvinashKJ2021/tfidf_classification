# TF-IDF Text Classification

This repository contains a Python implementation of a **text classification pipeline** using **TF-IDF (Term Frequency-Inverse Document Frequency)** features and machine learning models for supervised classification.  
TF-IDF is a widely-used technique in natural language processing to convert text data into numerical representations that are suitable for machine learning models. :contentReference[oaicite:0]{index=0}

## 📌 Overview

This project demonstrates:

- Preprocessing of text data including cleaning and tokenization
- Generation of TF-IDF features from raw text
- Training and evaluation of two classifiers:
  - **Multinomial Naive Bayes**
  - **Random Forest**
- Model comparison and interpretation of results

The goal is to showcase how traditional machine learning approaches can be applied to textual data classification using TF-IDF representations. :contentReference[oaicite:1]{index=1}

## 🧠 Features

- Converts raw text into TF-IDF vectors
- Handles preprocessing like lowercasing, stopword removal, and tokenization
- Trains and tests models to classify text into target categories
- Evaluation with metrics such as accuracy and optionally F1-score
