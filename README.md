# Alphabet Image Classification Project

This project aims to classify images of alphabets (A-Z) using different machine learning algorithms and determine the most accurate model.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Insights](#insights)


## Introduction
This project involves classifying images of alphabets using machine learning algorithms such as Logistic Regression, Decision Tree, SVM, Random Forest, and K-Nearest Neighbors. The project evaluates the performance of these models and identifies the best-performing one based on accuracy.

## Dataset
The dataset used in this project contains images of alphabets (A-Z). Each image is a 28x28 pixel grayscale image. The dataset is extracted from a ZIP file containing images organized into folders labeled with the corresponding alphabet.

## Installation
To run this project, you need to have the following libraries installed:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- tqdm
- PIL
- zipfile

You can install these libraries using pip:
```sh
pip install numpy pandas matplotlib seaborn scikit-learn tqdm pillow
```

## Usage
1. Mount Google Drive and extract the dataset:
2. Preprocess and visualize the data:
3. Split the data and train models:

## Results
The accuracy of each model is as follows:
- Logistic Regression: 0.8190
- Decision Tree: 0.7198
- SVM: 0.9340
- Random Forest: 0.9076
- KNN: 0.8930

## Insights
The SVM (Support Vector Classifier) shows the highest accuracy score at 0.9340. Therefore, based on the metric of accuracy alone, the SVM is the best-fitted model among those listed.



