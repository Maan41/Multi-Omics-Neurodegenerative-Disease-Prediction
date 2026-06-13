# Integrative Multi-Omics Approaches for Understanding and Predicting Neurodegenerative Diseases

## Project Overview
This project applies machine learning (Logistic Regression, Random Forest, SVM) to predict neurodegenerative diseases using integrated multi-omics data from the ROSMAP dataset. The pipeline includes data preprocessing, feature selection, model tuning, and comprehensive evaluation.

## Key Features
- Multi-omics data integration (3 omics datasets)
- Classification with multiple ML models
- Feature importance analysis using Random Forest
- Hyperparameter tuning with GridSearchCV
- ROC curves and confusion matrices for model evaluation

## Results Summary

| Experiment | Model | Accuracy | ROC-AUC |
|------------|-------|----------|---------|
| Combined (Scaled + Tuned LR) | Tuned Logistic Regression | 0.803 | 0.866 |
| Combined (Scaled) | Logistic Regression | 0.789 | 0.864 |
| Combined (Raw) | Logistic Regression | 0.761 | 0.832 |

## Repository Structure
Multi-Omics-Neurodegenerative-Disease-Prediction/
├── ROSMAP/ # Dataset folder
├── neuro_disease_prediction.ipynb # Main Jupyter notebook
├── final_results.csv # Final model results
├── summary_results.csv # Summary of all experiments
├── top_features.csv # Feature importance rankings
├── roc_curve.jpeg # ROC curve visualization
├── confusion_matrix.jpeg # Confusion matrix visualization
├── requirements.txt # Python dependencies
├── LICENSE # MIT License
└── README.md # Project documentation


## Installation

1. Clone the repository:
```bash
git clone https://github.com/Maan41/Multi-Omics-Neurodegenerative-Disease-Prediction.git
cd Multi-Omics-Neurodegenerative-Disease-Prediction

2. Install dependencies:

Dependencies

Python 3.x
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter


3. License:
This project is licensed under the MIT License - see the LICENSE file for details.

##Author
Jotsaroop singh

Acknowledgments
ROSMAP dataset from IEEE

Thapar Institute of Engineering and Technology 
