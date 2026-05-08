# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/tests/experimental/optim/test_dynamic_loss_scaler.py

Prompts

```
['test the DynamicLossScaler by training a linear regression model over 1000 epochs without gradient overflow', 'train a PyTorch model using DynamicLossScaler to scale loss, step optimizer, and update scaler each epoch', 'create a synthetic linear regression dataset with 100 shuffled samples and convert to PyTorch tensors', 'review the ManualLinearRegression nn.Module class with a single nn.Linear layer for 1D input and output', 'refactor the training loop to use DynamicLossScaler scale, backward, step, and update methods for mixed precision']
```

Usage

```
{'test_dynamic_loss_scaler_without_overflow': 'test the DynamicLossScaler by training a linear regression model over 1000 epochs without gradient overflow', 'train_model_with_dynamic_loss_scaler': 'train a PyTorch model using DynamicLossScaler to scale loss, step optimizer, and update scaler each epoch', 'init_synthetic_linear_regression_dataset': 'create a synthetic linear regression dataset with 100 shuffled samples and convert to PyTorch tensors', 'review_manual_linear_regression_module': 'review the ManualLinearRegression nn.Module class with a single nn.Linear layer for 1D input and output', 'refactor_dynamic_loss_scaler_training_loop': 'refactor the training loop to use DynamicLossScaler scale, backward, step, and update methods for mixed precision'}
```

