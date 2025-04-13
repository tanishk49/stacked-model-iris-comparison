# Stacked Machine Learning Models for Iris Dataset Classification

This repository demonstrates the implementation of a stacked ensemble model for the classic Iris dataset classification problem, along with performance comparisons against individual machine learning models.

## Project Overview

We compare the performance of several machine learning models including:
- K-Nearest Neighbors (KNN)
- Support Vector Machine with RBF kernel (SVM-RBF)
- Decision Tree (DT)
- Random Forest (RF)
- Multi-layer Perceptron (MLP)
- Stacked Ensemble Model

The project includes:
1. Basic data preparation and feature selection
2. Individual model training and evaluation
3. Stacked model implementation
4. Comprehensive performance comparison

## Key Results

### Model Performance Comparison

| Model    | Train Accuracy | Train MCC | Train F1 | Test Accuracy | Test MCC | Test F1 |
|----------|----------------|-----------|----------|---------------|----------|---------|
| KNN      | 0.958333       | 0.937598  | 0.958327 | 1.000000      | 1.000000 | 1.000000 |
| SVM-RBF  | 0.991667       | 0.987603  | 0.991665 | 0.966667      | 0.951587 | 0.966583 |
| DT       | 1.000000       | 1.000000  | 1.000000 | 0.966667      | 0.951587 | 0.966583 |
| RF       | 1.000000       | 1.000000  | 1.000000 | 0.900000      | 0.851420 | 0.899749 |
| MLP      | 0.983333       | 0.975407  | 0.983323 | 1.000000      | 1.000000 | 1.000000 |
| Stacked  | 0.991667       | 0.987603  | 0.991665 | 1.000000      | 1.000000 | 1.000000 |

### Training Metrics

| Model    | Accuracy  | MCC       | F1        |
|----------|-----------|-----------|-----------|
| KNN      | 0.958333  | 0.937598  | 0.958327  |
| SVM-RBF  | 0.991667  | 0.987603  | 0.991665  |
| DT       | 1.000000  | 1.000000  | 1.000000  |
| RF       | 1.000000  | 1.000000  | 1.000000  |
| MLP      | 0.983333  | 0.975407  | 0.983323  |
| Stacked  | 0.991667  | 0.987603  | 0.991665  |

## Key Findings

1. The stacked model achieved perfect test performance (Accuracy=1.0, MCC=1.0, F1=1.0)
2. Several models (KNN, MLP, Stacked) achieved perfect test accuracy
3. Decision Tree and Random Forest showed signs of overfitting with perfect training scores but lower test performance
4. The stacked model combined the strengths of individual models to achieve robust performance

## Installation

1. Clone this repository
2. Install requirements:


## Requirements

- Python 3.7+
- scikit-learn
- pandas
- numpy
- matplotlib (for visualization)
- jupyter (for notebook)

## Dataset

The Iris dataset from scikit-learn is used, containing 150 samples of iris flowers with 4 features each, classified into 3 species.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
