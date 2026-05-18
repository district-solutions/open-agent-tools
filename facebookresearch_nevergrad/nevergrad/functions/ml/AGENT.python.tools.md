# Agent Python Tools

- repo: facebookresearch/nevergrad
- repo_uri: https://github.com/facebookresearch/nevergrad

## File: facebookresearch_nevergrad/nevergrad/functions/ml/mlfunctionlib.py

Prompts

```
['create an MLTuning instance with decision_tree regressor on an artificial dataset with specified data dimension', 'create an MLTuning instance with mlp regressor to optimize neural network hyperparameters on synthetic data', 'create an MLTuning instance with any regressor type to let nevergrad choose between mlp and decision_tree', 'run the evaluation_function on an MLTuning instance to get test set MSE for a recommended parameter set', 'create an MLTuning instance with diabetes or kerasBoston dataset for real-world regression hyperparameter tuning', 'test MLTuning with a decision tree regressor on artificial data with depth 3', 'test MLTuning with an MLP regressor on artificial data using adam solver', 'test MLTuning with regressor set to any to let nevergrad choose the best model', 'test MLTuning with a decision tree regressor on the diabetes dataset', 'test MLTuning with a decision tree regressor on the artificialcos dataset']
```

Usage

```
{'create_MLTuning_decision_tree': 'create an MLTuning instance with decision_tree regressor on an artificial dataset with specified data dimension', 'create_MLTuning_mlp': 'create an MLTuning instance with mlp regressor to optimize neural network hyperparameters on synthetic data', 'create_MLTuning_any': 'create an MLTuning instance with any regressor type to let nevergrad choose between mlp and decision_tree', 'run_MLTuning_evaluation': 'run the evaluation_function on an MLTuning instance to get test set MSE for a recommended parameter set', 'create_MLTuning_real_dataset': 'create an MLTuning instance with diabetes or kerasBoston dataset for real-world regression hyperparameter tuning'}
```

## File: facebookresearch_nevergrad/nevergrad/functions/ml/test_mlfunctionlib.py

Prompts

```
['create an MLTuning instance with decision_tree regressor on an artificial dataset with specified data dimension', 'create an MLTuning instance with mlp regressor to optimize neural network hyperparameters on synthetic data', 'create an MLTuning instance with any regressor type to let nevergrad choose between mlp and decision_tree', 'run the evaluation_function on an MLTuning instance to get test set MSE for a recommended parameter set', 'create an MLTuning instance with diabetes or kerasBoston dataset for real-world regression hyperparameter tuning', 'test MLTuning with a decision tree regressor on artificial data with depth 3', 'test MLTuning with an MLP regressor on artificial data using adam solver', 'test MLTuning with regressor set to any to let nevergrad choose the best model', 'test MLTuning with a decision tree regressor on the diabetes dataset', 'test MLTuning with a decision tree regressor on the artificialcos dataset']
```

Usage

```
{'test_MLTuning_decision_tree': 'test MLTuning with a decision tree regressor on artificial data with depth 3', 'test_MLTuning_mlp': 'test MLTuning with an MLP regressor on artificial data using adam solver', 'test_MLTuning_any_regressor': 'test MLTuning with regressor set to any to let nevergrad choose the best model', 'test_MLTuning_diabetes_dataset': 'test MLTuning with a decision tree regressor on the diabetes dataset', 'test_MLTuning_artificialcos_dataset': 'test MLTuning with a decision tree regressor on the artificialcos dataset'}
```

