
# Titanic Survival Prediction - Model Evaluation and Tuning

This project performs machine learning on the Titanic dataset to predict survival outcomes using multiple classifiers. It includes:

- Data preprocessing
- Training Logistic Regression, Random Forest, and SVM models
- Model evaluation using Accuracy, Precision, Recall, and F1-Score
- Hyperparameter tuning using GridSearchCV and RandomizedSearchCV
- Final model comparison and selection

## Dataset
The dataset used is from Seaborn's built-in Titanic dataset.

## Dependencies
- pandas
- numpy
- seaborn
- scikit-learn

## How to Run
```bash
python titanic_model_training.py
```

## Output
The script will print evaluation metrics for all models (before and after tuning) and highlight the best model based on F1 Score.
