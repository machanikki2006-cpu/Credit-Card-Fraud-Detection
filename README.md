# Credit Card Fraud Detection using Machine Learning

## Overview
This project focuses on detecting fraudulent credit card transactions using **Machine Learning techniques**. Since fraud detection datasets are highly imbalanced, this project applies **SMOTE (Synthetic Minority Oversampling Technique)** to balance the dataset and improve model performance.

The project compares the performance of multiple machine learning models, including:

- Logistic Regression
- Logistic Regression with SMOTE
- Random Forest Classifier

The main objective is to accurately identify fraudulent transactions while minimizing false predictions.

---

## Features
- Data preprocessing and cleaning
- Handling imbalanced dataset using **SMOTE**
- Fraud detection using **Machine Learning**
- Model comparison and evaluation
- Performance analysis using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Confusion Matrix

---

## Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Imbalanced-learn (SMOTE)**
- **Jupyter Notebook**

---

## Dataset
The project uses a **Credit Card Fraud Detection Dataset** containing transaction details.

### Dataset Characteristics
- Contains both **fraudulent** and **non-fraudulent** transactions
- Highly imbalanced dataset
- Includes transaction-related features
- Target variable:
  - **0 → Non-Fraud Transaction**
  - **1 → Fraud Transaction**

---

## Project Workflow

### 1. Data Collection
The dataset is loaded using Pandas and explored for understanding the structure and distribution of data.

### 2. Data Preprocessing
- Removed unnecessary columns (`Time`)
- Checked for missing values
- Removed duplicate entries
- Split dataset into training and testing sets

### 3. Feature Scaling
Applied **StandardScaler** to normalize feature values for better model performance.

### 4. Model Building

#### Logistic Regression
A Logistic Regression model is trained on the original dataset.

#### SMOTE for Class Balancing
Since fraud detection data is imbalanced, **SMOTE** is applied to generate synthetic samples for the minority class and balance the dataset.

#### Random Forest Classifier
A Random Forest model is trained to improve classification performance and reduce overfitting.

### 5. Model Evaluation
The models are evaluated using:

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Confusion Matrix

---

## Results
The project compares different models to determine the best-performing fraud detection system.

### Models Compared
- Logistic Regression
- Logistic Regression with SMOTE
- Random Forest Classifier

Performance is evaluated based on:
- Precision
- Recall
- F1 Score
- Accuracy

Random Forest generally performs better due to its ability to capture complex patterns and reduce overfitting.

---

## Learning Outcomes
Through this project, I gained practical experience in:

- Handling imbalanced datasets
- SMOTE oversampling
- Classification algorithms
- Model evaluation metrics
- Fraud detection using Machine Learning

---

## Installation

Clone the repository:

```bash
git clone https://github.com/machanikki2006-cpu/credit-card-fraud-detection.git
```
