# Agent Python Tools

- repo: facebookresearch/pearl
- repo_uri: https://github.com/facebookresearch/pearl

## File: facebookresearch_pearl/pearl/neural_networks/contextual_bandit/base_cb_model.py

Prompts

```
['build a subclass of MuSigmaCBModel that implements the abstract forward method for contextual bandit predictions', 'create an instance of a MuSigmaCBModel subclass with a specified feature dimension for reward prediction', 'test the forward method of a MuSigmaCBModel subclass by passing a torch tensor and checking output shape', 'review the MuSigmaCBModel base class to understand its abstract forward method and feature dimension initialization', 'refactor a MuSigmaCBModel subclass forward method to return both mu and sigma predictions', 'create a LinearRegression model with feature_dim, l2_reg_lambda, gamma discounting, and optional initial coefficients', 'train the LinearRegression model on a batch of features x, targets y, and optional weights using learn_batch', 'run forward pass on feature tensors to get point predictions using the LinearRegression forward method', 'calculate prediction uncertainty sigma for feature tensors using the calculate_sigma method with quadratic form', 'apply gamma discounting to A and b matrices to forget old data in non-stationary environments', 'create a NeuralLinearRegression model with specified feature dimensions and hidden layer sizes for contextual bandit learning', 'run a forward pass through the NeuralLinearRegression model to get predictions from input feature tensors', 'calculate the sigma uncertainty estimates for input features using the NeuralLinearRegression linear regression layer', 'run a forward pass that returns predictions along with intermediate NN output values for debugging', 'compare two NeuralLinearRegression model instances to identify differences in their attributes and layer state dicts']
```

Usage

```
{'build_MuSigmaCBModel_subclass': 'build a subclass of MuSigmaCBModel that implements the abstract forward method for contextual bandit predictions', 'create_MuSigmaCBModel_instance': 'create an instance of a MuSigmaCBModel subclass with a specified feature dimension for reward prediction', 'test_MuSigmaCBModel_forward': 'test the forward method of a MuSigmaCBModel subclass by passing a torch tensor and checking output shape', 'review_MuSigmaCBModel': 'review the MuSigmaCBModel base class to understand its abstract forward method and feature dimension initialization', 'refactor_MuSigmaCBModel_forward': 'refactor a MuSigmaCBModel subclass forward method to return both mu and sigma predictions'}
```

## File: facebookresearch_pearl/pearl/neural_networks/contextual_bandit/linear_regression.py

Prompts

```
['build a subclass of MuSigmaCBModel that implements the abstract forward method for contextual bandit predictions', 'create an instance of a MuSigmaCBModel subclass with a specified feature dimension for reward prediction', 'test the forward method of a MuSigmaCBModel subclass by passing a torch tensor and checking output shape', 'review the MuSigmaCBModel base class to understand its abstract forward method and feature dimension initialization', 'refactor a MuSigmaCBModel subclass forward method to return both mu and sigma predictions', 'create a LinearRegression model with feature_dim, l2_reg_lambda, gamma discounting, and optional initial coefficients', 'train the LinearRegression model on a batch of features x, targets y, and optional weights using learn_batch', 'run forward pass on feature tensors to get point predictions using the LinearRegression forward method', 'calculate prediction uncertainty sigma for feature tensors using the calculate_sigma method with quadratic form', 'apply gamma discounting to A and b matrices to forget old data in non-stationary environments', 'create a NeuralLinearRegression model with specified feature dimensions and hidden layer sizes for contextual bandit learning', 'run a forward pass through the NeuralLinearRegression model to get predictions from input feature tensors', 'calculate the sigma uncertainty estimates for input features using the NeuralLinearRegression linear regression layer', 'run a forward pass that returns predictions along with intermediate NN output values for debugging', 'compare two NeuralLinearRegression model instances to identify differences in their attributes and layer state dicts']
```

Usage

```
{'create_linear_regression_model': 'create a LinearRegression model with feature_dim, l2_reg_lambda, gamma discounting, and optional initial coefficients', 'train_linear_regression_batch': 'train the LinearRegression model on a batch of features x, targets y, and optional weights using learn_batch', 'predict_with_linear_regression': 'run forward pass on feature tensors to get point predictions using the LinearRegression forward method', 'calculate_uncertainty_sigma': 'calculate prediction uncertainty sigma for feature tensors using the calculate_sigma method with quadratic form', 'apply_discounting_forget_old_data': 'apply gamma discounting to A and b matrices to forget old data in non-stationary environments'}
```

## File: facebookresearch_pearl/pearl/neural_networks/contextual_bandit/neural_linear_regression.py

Prompts

```
['build a subclass of MuSigmaCBModel that implements the abstract forward method for contextual bandit predictions', 'create an instance of a MuSigmaCBModel subclass with a specified feature dimension for reward prediction', 'test the forward method of a MuSigmaCBModel subclass by passing a torch tensor and checking output shape', 'review the MuSigmaCBModel base class to understand its abstract forward method and feature dimension initialization', 'refactor a MuSigmaCBModel subclass forward method to return both mu and sigma predictions', 'create a LinearRegression model with feature_dim, l2_reg_lambda, gamma discounting, and optional initial coefficients', 'train the LinearRegression model on a batch of features x, targets y, and optional weights using learn_batch', 'run forward pass on feature tensors to get point predictions using the LinearRegression forward method', 'calculate prediction uncertainty sigma for feature tensors using the calculate_sigma method with quadratic form', 'apply gamma discounting to A and b matrices to forget old data in non-stationary environments', 'create a NeuralLinearRegression model with specified feature dimensions and hidden layer sizes for contextual bandit learning', 'run a forward pass through the NeuralLinearRegression model to get predictions from input feature tensors', 'calculate the sigma uncertainty estimates for input features using the NeuralLinearRegression linear regression layer', 'run a forward pass that returns predictions along with intermediate NN output values for debugging', 'compare two NeuralLinearRegression model instances to identify differences in their attributes and layer state dicts']
```

Usage

```
{'create_NeuralLinearRegression_model': 'create a NeuralLinearRegression model with specified feature dimensions and hidden layer sizes for contextual bandit learning', 'run_forward_NeuralLinearRegression': 'run a forward pass through the NeuralLinearRegression model to get predictions from input feature tensors', 'calculate_sigma_NeuralLinearRegression': 'calculate the sigma uncertainty estimates for input features using the NeuralLinearRegression linear regression layer', 'forward_with_intermediate_NeuralLinearRegression': 'run a forward pass that returns predictions along with intermediate NN output values for debugging', 'compare_NeuralLinearRegression_models': 'compare two NeuralLinearRegression model instances to identify differences in their attributes and layer state dicts'}
```

