# Iris-Flower-Classification

This repository contains a machine learning project that classifies Iris flower species based on their physical attributes using popular algorithms such as Logistic Regression, Decision Trees, and Support Vector Machines (SVM).

---

## 📋 Overview

The **Iris Flower Classification** project is a beginner-friendly dataset and machine learning task. The dataset consists of 150 samples, each described by four features:  
- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

The task is to classify the samples into one of three species:  
1. Setosa  
2. Versicolor  
3. Virginica  

---

## 📂 Project Structure

```plaintext
├── data/
│   └── iris.csv          # Dataset file (optional, or fetched programmatically)
├── notebooks/
│   └── Iris_Classification.ipynb  # Jupyter Notebook with code and visualizations
├── src/
│   └── train_model.py     # Script to train and evaluate models
│   └── utils.py           # Helper functions for preprocessing and evaluation
├── models/
│   └── model.pkl          # Serialized trained model
├── README.md              # Project description
├── requirements.txt       # Required Python libraries
