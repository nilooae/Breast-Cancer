# Breast Cancer Classification

A Machine Learning project for breast cancer prediction using Logistic Regression.

## Overview

This project uses the Breast Cancer Wisconsin dataset from Scikit-Learn to classify tumors as malignant or benign.

The workflow includes:

* Data loading and preprocessing
* Exploratory Data Analysis (EDA)
* Model training using Logistic Regression
* Model evaluation with multiple metrics

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Dataset

The dataset is provided by Scikit-Learn:

```python
from sklearn.datasets import load_breast_cancer
```

It contains several features computed from digitized images of breast mass cell nuclei.

## Model

The classification model used in this project is:

* Logistic Regression

## Evaluation Metrics

The model performance was evaluated using:

* Accuracy Score
* Precision Score
* Recall Score
* F1 Score
* Confusion Matrix

## Libraries

```python
import matplotlib.pyplot as plt
import pandas as pd
import numpy as np
import seaborn as sns

from sklearn.linear_model import LogisticRegression
from sklearn.metrics import (
    accuracy_score,
    confusion_matrix,
    precision_score,
    recall_score,
    f1_score,
    ConfusionMatrixDisplay
)
```

## Goals of the Project

* Practice supervised machine learning
* Understand binary classification
* Learn model evaluation techniques
* Improve data analysis and visualization skills

## Results

The Logistic Regression model achieved the following performance:

- Accuracy: 97.37%
- Precision: 97.22%
- Recall: 98.59%
- F1 Score: 97.90%

Confusion Matrix:

[[41, 2],
 [1, 70]]

The model successfully distinguished between malignant and benign tumors and demonstrated strong classification performance on the dataset.



## Future Improvements

* Try different classification models
* Hyperparameter tuning
* Feature selection
* Cross-validation
* Data visualization improvements
                                                                                                                                                                                                                                                                                                                                          
                                                                                                                                                            
                                                                                                                                                                                                                                                                                                                                          
