# PCOS Risk Prediction

## Overview
This repository contains the **code and modeling pipeline** used to predict PCOS risk using unsupervised and supervised learning.  
Detailed methodology, interpretation, and clinical discussion are documented separately in the accompanying **Medium post**. The initial process and steps taken can be viewed in this presentation: https://www.canva.com/design/DAG69HXDMcw/1z4NZRqqp8CKoRhJ3KGSTQ/view?utm_content=DAG69HXDMcw&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hb48d6a226a

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

