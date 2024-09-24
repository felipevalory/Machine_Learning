# Machine Learning Experiment

## Overview

This project explores **Classification**, **Regression**, and **Clustering** algorithms, analyzing how their performance changes as we tweak key parameters that control **overfitting** and **underfitting**. The goal is to gain a deeper understanding of how to optimize each model, ensuring accurate and consistent results.

## Solution Plan

The final output will include 7 comparative tables showing the performance of the algorithms across three datasets: **training**, **validation**, and **testing**, evaluated using various performance metrics.

## Algorithms Evaluated

### Classification:
- **Algorithms**: KNN, Decision Tree, Random Forest, Logistic Regression
- **Metrics**: Accuracy, Precision, Recall, F1-Score

### Regression:
- **Algorithms**: Linear Regression, Decision Tree Regressor, Random Forest Regressor, Polynomial Regression, Lasso, Ridge, Elastic Net
- **Metrics**: R², MSE, RMSE, MAE, MAPE

### Clustering:
- **Algorithms**: K-Means, Affinity Propagation
- **Metric**: Silhouette Score

## Tools Used

- Python 3.11.4
- Scikit-learn
- Jupyter Notebook

## Development

### Solution Strategy

I used **Python** to train each algorithm and adjust the parameters controlling **overfitting**. The best performance was achieved by optimizing key parameters for each algorithm.

### Step-by-Step Process:

1. Split the data into training, validation, and test sets.
2. Initial training using default parameters.
3. Evaluate performance on training and validation data.
4. Adjust key parameters to improve performance.
5. Retrain using the combined training + validation data.
6. Final evaluation using the test dataset.
7. Identify the top 3 key insights.

## Key Insights

- **Decision Trees** outperformed other models in classification metrics.
- The validation performance closely matched the test performance in classification algorithms.
- **Regression models** showed weaker results, indicating the need for better data preparation and feature selection.

## Results

### Classification Experiments

![Classification results](/img/classification.jpg)

### Regression Experiments

![Regression results - Training](/img/regression_training.jpg)

![Regression results - Validation](/img/regression_validation.jpg)

![Regression results - Test](/img/regression_test.jpg)

### Clustering Experiments

![Clustering results](/img/clusterization.jpg)

## Conclusion

This project gave me valuable insights into the balance between **underfitting** and **overfitting**. I discovered that **decision tree** algorithms are highly sensitive to tree depth and the number of trees, while **regression models** are strongly influenced by the polynomial degree. This experiment was crucial in solidifying my understanding of how to fine-tune key parameters to optimize the performance of **classification**, **regression**, and **clustering** models.
