# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/data/regressionKaggleHousePrice/baseline.py

Prompts

```
['run the Kaggle house price regression baseline pipeline to train a Ridge model and generate predictions', 'preprocess train validation and test data by imputing missing values encoding categoricals and scaling numerics', 'train a Ridge regression model with alpha 0.1 on preprocessed house price features', 'evaluate a trained model on a dataset and return RMSE and R2 score metrics', 'create a CSV submission file with predicted SalePrice values for the test set', 'run the evaluate_submission function to compare predictions against true labels and print RMSE and R2 metrics', 'run the CLI module with --submission_file to evaluate a house price prediction CSV against answer.csv', 'create a function that loads true labels and predictions from two CSV files and returns SalePrice columns', 'create a function that calculates RMSE and R2 score from true and predicted values using sklearn', 'refactor evaluate_submission to accept a configurable test_labels_file path instead of a hardcoded value']
```

Usage

```
{'run_baseline_pipeline': 'run the Kaggle house price regression baseline pipeline to train a Ridge model and generate predictions', 'preprocess_data': 'preprocess train validation and test data by imputing missing values encoding categoricals and scaling numerics', 'train_model': 'train a Ridge regression model with alpha 0.1 on preprocessed house price features', 'evaluate_model': 'evaluate a trained model on a dataset and return RMSE and R2 score metrics', 'create_submission': 'create a CSV submission file with predicted SalePrice values for the test set'}
```

## File: facebookresearch_mlgym/data/regressionKaggleHousePrice/evaluate.py

Prompts

```
['run the Kaggle house price regression baseline pipeline to train a Ridge model and generate predictions', 'preprocess train validation and test data by imputing missing values encoding categoricals and scaling numerics', 'train a Ridge regression model with alpha 0.1 on preprocessed house price features', 'evaluate a trained model on a dataset and return RMSE and R2 score metrics', 'create a CSV submission file with predicted SalePrice values for the test set', 'run the evaluate_submission function to compare predictions against true labels and print RMSE and R2 metrics', 'run the CLI module with --submission_file to evaluate a house price prediction CSV against answer.csv', 'create a function that loads true labels and predictions from two CSV files and returns SalePrice columns', 'create a function that calculates RMSE and R2 score from true and predicted values using sklearn', 'refactor evaluate_submission to accept a configurable test_labels_file path instead of a hardcoded value']
```

Usage

```
{'run_evaluate_submission': 'run the evaluate_submission function to compare predictions against true labels and print RMSE and R2 metrics', 'run_cli_evaluation': 'run the CLI module with --submission_file to evaluate a house price prediction CSV against answer.csv', 'create_load_data': 'create a function that loads true labels and predictions from two CSV files and returns SalePrice columns', 'create_calculate_metrics': 'create a function that calculates RMSE and R2 score from true and predicted values using sklearn', 'refactor_evaluate_submission': 'refactor evaluate_submission to accept a configurable test_labels_file path instead of a hardcoded value'}
```

