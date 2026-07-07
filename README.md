# AdaBoost Classification

This repository demonstrates the implementation of the AdaBoost (Adaptive Boosting) algorithm for a classification problem using Scikit-Learn. The project explores how multiple weak learners (Decision Stumps) can be combined to create a strong classifier and improve predictive performance.

## Project Overview

AdaBoost is one of the most popular ensemble learning algorithms. It works by training multiple weak learners sequentially, where each subsequent model focuses more on the instances misclassified by previous models.

In this project:

- A synthetic classification dataset is generated using Scikit-Learn.
- A Decision Tree Stump is used as the base estimator.
- AdaBoostClassifier is trained on the dataset.
- Model performance is evaluated using classification metrics.

## Algorithms Used

### Decision Stump
- Decision Tree with maximum depth = 1.
- Acts as a weak learner.

### AdaBoost Classifier
- Sequential ensemble learning algorithm.
- Assigns higher weights to previously misclassified samples.
- Combines weak learners into a strong classifier.

## Technologies Used

- Python
- NumPy
- Scikit-Learn
- Jupyter Notebook

## Workflow

1. Generate classification dataset
2. Split dataset into training and testing sets
3. Create Decision Stump
4. Train AdaBoost Classifier
5. Predict test labels
6. Evaluate model performance

## Results

## Results

### Model Performance

| Metric | Value |
|----------|----------|
| Accuracy | 73.33% |
| Precision (Class 0) | 75% |
| Recall (Class 0) | 71% |
| F1-Score (Class 0) | 73% |
| Precision (Class 1) | 71% |
| Recall (Class 1) | 75% |
| F1-Score (Class 1) | 73% |

### Classification Report

| Class | Precision | Recall | F1-Score | Support |
|---------|---------|---------|---------|---------|
| 0 | 0.75 | 0.71 | 0.73 | 77 |
| 1 | 0.71 | 0.75 | 0.73 | 73 |

**Overall Accuracy:** 73.33%

### Key Observations

- AdaBoost successfully improved classification performance by combining multiple weak learners.
- Decision Stumps individually have limited predictive power, but their ensemble significantly improves accuracy.
- The model effectively classified the synthetic dataset and demonstrated the strength of boosting techniques.

## Repository Structure

```text
adaboost-classification/
├── .gitignore
├── README.md
└── AdaBoost_Classification.ipynb
```

## Installation

Clone the repository:

```bash
git clone https://github.com/amaaan01/adaboost-classification.git
```

Navigate to the project directory:

```bash
cd adaboost-classification
```

Install dependencies:

```bash
pip install numpy scikit-learn jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
AdaBoost_Classification.ipynb
```

## Key Learning Outcomes

- Understanding AdaBoost algorithm
- Working with weak learners and Decision Stumps
- Ensemble learning concepts
- Classification model evaluation
- Practical implementation using Scikit-Learn



## Conclusion

This project demonstrates the implementation of AdaBoost for classification tasks. By combining multiple weak Decision Stumps, AdaBoost creates a powerful ensemble model capable of achieving strong predictive performance and reducing classification errors.
