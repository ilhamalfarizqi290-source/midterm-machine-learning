# Machine Learning Midterm Project
## Customer Segmentation using K-Means Clustering

### Student Information
Name: Muhammad ilham alfarizqi  
Class: Machine Learning & Deep Learning Class Telyu [TK4601]
NIM: 1103223114

---

## Project Overview
This project implements an end-to-end machine learning pipeline for customer segmentation using clustering techniques.

The objective is to group customers based on their credit card usage behavior.

---

## Dataset
Dataset used:
clusteringmidterm.csv

Total data:
8950 rows

Total features:
17 features after preprocessing

---

## Data Preprocessing
The preprocessing steps include:

- Removing customer ID
- Handling missing values
- Feature scaling using StandardScaler

---

## Model
Algorithm used:

K-Means Clustering

---

## Hyperparameter Tuning
Tuning performed using Optuna.

Best parameter:

n_clusters = 3

Best silhouette score:

0.25099

---

## Experiment Tracking
Experiment tracking performed using MLflow.

---

## Conclusion
The best clustering model was achieved using 3 clusters, which provided the best silhouette score.
