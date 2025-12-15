# PCOS Risk Prediction

## Overview
This repository contains the **code and modeling pipeline** used to predict PCOS risk using unsupervised and supervised learning.  
Detailed methodology, interpretation, and clinical discussion are documented separately in the accompanying **Medium post**.

## Tech Stack
- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter / Google Colab

## Data
- Source: Kaggle PCOS Dataset  
- File used: `PCOS_data_without_infertility.xlsx`  
- 541 patient records with clinician-verified PCOS labels

## Methods Implemented
- Data cleaning and feature selection
- Unit-aware feature scaling and encoding
- **K-Means clustering** (Elbow method, PCA visualization)
- **Random Forest classification** with class balancing
- Model evaluation using accuracy, precision, recall
- Feature importance and error analysis


## Notes
- Focus is on **modeling and implementation**, not clinical diagnosis
- Results are exploratory and dataset-specific

## Medium Post
Full explanation, visuals, and interpretation are available in the Medium article.

