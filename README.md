                                                                                                                                                     # PCOS Risk Prediction

## Overview
This repository contains the **code and modeling pipeline** used to predict PCOS risk using unsupervised and supervised learning.  
Detailed methodology, interpretation, and clinical discussion are documented separately in an accompanying **Medium post**. The initial process and steps taken can be viewed in our [presentation](https://www.canva.com/design/DAG69HXDMcw/dy2fDIMcUyN_0bLfdxSy5Q/edit?utm_content=DAG69HXDMcw&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton):

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/0754d437-b850-47ae-96ce-6da430d2c40b" />


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

## Medium Report
Full explanation, visuals, and interpretation are available in this Medium article: 

