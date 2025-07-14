# 🧠 Alphabet Image Classification Project

This project aims to classify images of alphabets (A–Z) using different machine learning algorithms and determine the most accurate model.

---

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Insights](#insights)

---

## 📝 Introduction

This project involves classifying images of alphabets using machine learning algorithms such as:

- Logistic Regression  
- Decision Tree  
- Support Vector Machine (SVM)  
- Random Forest  
- K-Nearest Neighbors (KNN)

The project evaluates the performance of these models and identifies the best-performing one based on accuracy.

---

## 📁 Dataset

The dataset used in this project contains images of alphabets (A–Z).  
Each image is a **28×28 pixel grayscale image**.

📦 The dataset is extracted from a `.zip` file containing image folders labeled `A/`, `B/`, ..., `Z/`.

---

## 🧰 Installation

To run this project, install the following Python libraries:

- numpy  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  
- tqdm  
- pillow (PIL)


pip install numpy pandas matplotlib seaborn scikit-learn tqdm pillow



## ▶️ Usage

1. Mount Google Drive (if using Colab) and extract the dataset.
2. Preprocess and visualize the data.
3. Split the data and train models using various ML algorithms.

---

## 📊 Results

The accuracy of each model is as follows:

| Model              | Accuracy  |
|--------------------|-----------|
| Logistic Regression| 81.90%    |
| Decision Tree      | 71.98%    |
| SVM                | **93.40%** ✅ |
| Random Forest      | 90.76%    |
| KNN                | 89.30%    |

---

## 🔍 Insights

✅ **SVM (Support Vector Classifier)** achieved the highest accuracy of **93.40%**.  
It is the best-fitted model among all tested based on accuracy.
