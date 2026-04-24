# Semiconductor Wafer Defect Classification: EDA, PCA, and ML

This repository presents an end-to-end exploratory data analysis and machine learning workflow for semiconductor wafer defect classification.

## Project Context

This project is based on the instructional workflow used in **MMIE 7310: Machine Learning and Artificial Intelligence for Engineers** at Texas State University. It is designed as a polished portfolio project demonstrating EDA, PCA, classification modeling, model evaluation, and engineering interpretation for manufacturing-quality analytics.

## Dataset

**Semiconductor Wafer Defect Classification Dataset**  
Kaggle dataset page: [add your Kaggle dataset URL here]

> Note: The dataset file is not included in this repository. Download the dataset from Kaggle and save it in the repository root as `semiconductor_wafer_defect_dataset.csv`.

## Problem Type

Supervised machine learning — classification.

## Skills Demonstrated

- Exploratory data analysis
- Manufacturing process data interpretation
- Data quality assessment
- Class imbalance analysis
- Feature scaling and normalization
- PCA dimensionality reduction
- Classification model development
- Model comparison using accuracy, precision, recall, F1-score, balanced accuracy, ROC-AUC, and PR-AUC
- Confusion matrix interpretation
- Hyperparameter tuning with GridSearchCV
- Feature importance analysis
- Engineering and quality-control interpretation

## Models Included

- Logistic Regression
- k-Nearest Neighbors
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine
- Optional Artificial Neural Network classifier

## Repository Structure

```text
semiconductor-wafer-defect-ml-classification/
│── semiconductor_wafer_defect_classification_eda_ml.ipynb
│── README.md
│── requirements.txt
│── .gitignore
```

## How to Run

1. Clone the repository.
2. Download the dataset from Kaggle.
3. Save the file as `semiconductor_wafer_defect_dataset.csv` in the repository root.
4. Install dependencies:

```bash
pip install -r requirements.txt
```

5. Open the notebook:

```bash
jupyter notebook semiconductor_wafer_defect_classification_eda_ml.ipynb
```

## Professional Relevance

This project demonstrates a practical workflow for manufacturing informatics and process-quality analytics. The same approach can be used for:

- defect detection
- equipment/process monitoring
- anomaly detection
- quality investigation
- supplier and raw-material risk analytics
- manufacturing decision support

## Author

Md Imrul Reza Shishir
