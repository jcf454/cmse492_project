# cmse492_project

Title: Predicting Stroke Risk From Health Indicators
Author: Jared Frazier
Date: 11/2/2025

Stroke remains one of the most common and catastrophic medical emergencies, with a leading rank among causes of death and disability in the world. Timely identification of high-risk
individuals can enable prevention and thus significantly reduce the long-term burden of both patients and healthcare systems. The aim of this project is to develop and evaluate machine learning models capable of predicting stroke incidents from a wide variety of health indicators that include age, hypertension, heart disease, glucose levels, and BMI.

cmse492_project/
├── README.md # Project overview and documentation
├── .gitignore # Ignore unnecessary files
├── data/
│ ├── raw/ # Original unmodified dataset
│ │ └── healthcare-dataset-stroke-data.csv
│ └── processed/ # Cleaned and encoded data used for modeling
│ └── stroke_processed.csv
├── notebooks/
│ ├── exploratory/ # Jupyter notebooks for EDA and visualization
│ │ └── EDA_stroke.ipynb
│ └── models/ # Baseline and advanced model notebooks
│ └── baseline_models.ipynb
├── src/
│ ├── preprocessing/ # Scripts for cleaning and transforming data
│ ├── models/ # Model training and comparison scripts
│ └── evaluation/ # Performance metrics and validation scripts
├── figures/ # Plots and saved output figures
├── docs/ # Reports and proposal files (LaTeX)
│ └── CMSE492_ProjectProposal.tex
└── requirements.txt # Python dependencies for reproducibility
