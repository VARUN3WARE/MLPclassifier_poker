```markdown
# MLP Classifier for Poker Hand Recognition

This project implements a Multi-Layer Perceptron (MLP) classifier to predict poker hands from a dataset. The classifier evaluates various poker hand categories and visualizes the model's performance using ROC-AUC curves for multi-class classification.

## Table of Contents
- [Features](#features)
- [Usage](#usage)
- [Data]
- [Model Evaluation](#model-evaluation)
- [Acknowledgments](#acknowledgments)

## Features
- **Multi-Class Classification**: Classifies poker hands into categories such as:
  - Zilch
  - One Pair
  - Two Pair
  - Three of a Kind
  - Straight
  - Flush or Better
- **Model Performance Visualization**: Utilizes ROC curves and AUC metrics to evaluate model performance.
- **User-Friendly**: Easy to set up and run with clear instructions.

## Usage
1. Load the dataset and preprocess it:
   The dataset `poker_hand_test.data` should be present in the project directory.
   
2. Run the main script:
   ```bash
   python main.py
   ```

   The script will train the MLP model and display the ROC-AUC visualizations.



## Data 
The dataset used in this project consists of poker hand data, where each hand is represented by the suits and ranks of five cards, along with the corresponding hand category.

## Model Evaluation
The performance of the model is evaluated using:
- **Accuracy**: Measures the ratio of correctly predicted instances to the total instances.
- **ROC-AUC**: Visualizes the trade-off between the true positive rate and false positive rate at various thresholds.

## Acknowledgments
- [Yellowbrick](https://www.scikit-yb.org/en/latest/) for providing visualization tools for model evaluation.
- [scikit-learn](https://scikit-learn.org/stable/) for the classification algorithms.

---
