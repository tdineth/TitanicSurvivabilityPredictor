# Titanic Survival Prediction Model

## Overview
This project applies **Linear Regression** to predict the survival probability of Titanic passengers based on historical data. Using a range of passenger attributes such as age, sex, ticket class, and family relationships, the model aims to estimate whether a passenger survived the Titanic disaster.

### Objective
This project demonstrates the application of **Linear Regression** for binary classification by predicting survival probability (scaled between 0 and 1) using structured tabular data.

---

## 📌 Important Note
This is a **followed and recreated project** based on publicly available datasets and concepts for personal learning and educational purposes.  
It is not an original research contribution but rather a hands-on exercise to strengthen practical understanding of machine learning pipelines, data preprocessing, and regression modeling.

---

## Dataset
The dataset used in this project comes from **TensorFlow’s public Titanic dataset**, which is hosted on Google Cloud Storage.

- **Training Dataset:**  
[https://storage.googleapis.com/tf-datasets/titanic/train.csv](https://storage.googleapis.com/tf-datasets/titanic/train.csv)  
Total Records: **627**

- **Testing/Evaluation Dataset:**  
[https://storage.googleapis.com/tf-datasets/titanic/eval.csv](https://storage.googleapis.com/tf-datasets/titanic/eval.csv)  
Total Records: **264**

### Features:
- `sex`: Gender of the passenger (male/female)
- `age`: Age of the passenger
- `n_siblings_spouses`: Number of siblings or spouses aboard
- `parch`: Number of parents or children aboard
- `fare`: Ticket fare paid
- `class`: Ticket class (First, Second, Third)
- `deck`: Deck location (if available, otherwise 'unknown')
- `embark_town`: Town from which the passenger boarded (Southampton, Cherbourg, Queenstown)
- `alone`: Whether the passenger was traveling alone (`y` or `n`)

---
