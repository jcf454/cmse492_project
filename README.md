# cmse492_project

**Title** Predicting Stroke Risk from Health Indicators  
**Author:** Jared Frazier  
**Course:** CMSE 492 – Machine Learning 
**Date:** Fall 2025  

---

## Project Overview

Stroke is one of the world’s leading causes of death and long-term disability. Early identification of high-risk individuals can prevent severe outcomes, yet traditional clinical scoring systems often fail to capture the nonlinear interactions among demographic, lifestyle, and medical factors.

This project develops a complete end-to-end machine learning pipeline to predict stroke risk from health indicators using a dataset of **5,110 patient records**. The pipeline includes:

- Data cleaning and preprocessing  
- Exploratory data analysis (EDA)  
- Handling missing and imbalanced data  
- Feature encoding and scaling  
- Model development and training  
- Hyperparameter tuning and threshold optimization  
- Evaluation using clinically meaningful metrics  
- Model interpretation 

Three models of increasing complexity were implemented and compared:

1. **Logistic Regression (baseline)**
2. **Random Forest Classifier**
3. **Shallow Neural Network**

The neural network achieved the strongest performance, with a **recall of 0.82** and **ROC-AUC of ~0.83**, demonstrating significant improvements over baseline methods for detecting stroke cases in imbalanced medical data.

---

## Repository Structure
cmse492_project/
├── .gitignore
├── README.md
├── requirements.txt
│
├── data/
│   ├── processed/
│   │   ├── .gitkeep
│   │   └── stroke_processed.csv
│   └── raw/
│       ├── .gitkeep
│       └── healthcare-dataset-stroke-data.csv
│
├── docs/
│   ├── .gitkeep
│   └── Frazier_Jared_CMSE492_ProjectProposal.pdf
│   └── Frazier_Jared_CMSE492_FinalProject.pdf
│
├── figures/
│   ├── .gitkeep
│   ├── age_distribution.png
│   ├── age_vs_glucose_by_stroke.png
│   ├── bmi_distribution.png
│   ├── feature_importance_rf.png
│   ├── missing_values_heatmap.png
│   ├── nn_loss_curve.png
│   ├── nn_precision_curve.png
│   ├── nn_recall_curve.png
│   └── stroke_class_balance.png
│
├── notebooks/
│   └── exploratory/
│       └── .gitkeep
│       └── ExploratoryDataFigures.ipynb
│
└── src/
    ├── evaluation/
    │   ├── .gitkeep
    │   └── ProjEvaluation.ipynb
    │
    ├── models/
    │   ├── .gitkeep
    │   ├── BaseLineModels.ipynb
    │   ├── BaseLineModelsCont.ipynb
    │   ├── RandomForestModel.ipynb
    │   └── ShallowNNModel.ipynb
    │
    └── preprocessing/
        ├── .gitkeep
        └── StrokeAcquisition.ipynb
