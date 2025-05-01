# Diabetes Prediction System

This project implements a diabetes prediction system using machine learning techniques on the Pima Indians Diabetes dataset. It compares three algorithms—**Naïve Bayes**, **Logistic Regression**, and **k-Nearest Neighbors**—to classify individuals as diabetic or non-diabetic based on medical attributes.

## Features 
- Supervised classification of diabetes presence using medical data
- Implements and compares:
  - **Naïve Bayes** (probabilistic)
  - **Logistic Regression** (statistical)
  - **k-Nearest Neighbors** (instance-based)
- Visual analysis of feature distributions and correlations
- Performance evaluation using metrics like **precision**, **recall**, **accuracy**, and **F1-score**
- Clean **Jupyter notebook** format for clarity and interactivity
- Detailed documentation with theoretical explanation and rationale

## Algorithm Overview 

- **Naïve Bayes Classifier**:  
  Uses **Bayes' theorem** assuming feature independence for efficient probabilistic classification.

- **Logistic Regression**:  
  Models probability of diabetes using a **sigmoid function** and **maximum likelihood estimation**.

- **k-Nearest Neighbors**:  
  Classifies based on the majority label among the **k closest training examples** using distance metrics.

## Requirements 

Install required Python libraries with:

```bash
pip install -r requirements.txt
