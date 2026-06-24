# IPL Match Prediction Using Random Forest

## Project Overview
This project uses Machine Learning techniques to predict IPL match outcomes based on match momentum and historical performance data.

The workflow includes:
- Data Cleaning and Preprocessing
- Feature Engineering
- Principal Component Analysis (PCA)
- Data Scaling using MinMaxScaler
- Random Forest Classification
- Hyperparameter Tuning using RandomizedSearchCV
- Model Evaluation

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- PCA
- Random Forest
- Matplotlib

## Dataset
The project uses IPL match momentum datasets containing engineered features related to team performance and match situations.

Files:
- Final train data momentum.csv
- Final test data momentum.csv

## Machine Learning Pipeline

1. Data Preprocessing
2. Missing Value Handling
3. Feature Scaling
4. PCA Dimensionality Reduction
5. Train-Test Split
6. Random Forest Training
7. Hyperparameter Optimization
8. Performance Evaluation

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Model Performance

| Metric | Score |
|----------|---------|
| Accuracy | 65.28% |
| Precision | 81.8% |
| Recall | 60.0% |
| F1 Score | 69.4% |

### Confusion Matrix

```text
[[23, 8],
 [24, 36]]

## Author

Soham Chandwadkar

MSc Data Science
