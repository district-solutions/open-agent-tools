# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/sklearn/gaussian_process/_gpc.py

Prompts

```
['create a GaussianProcessClassifier with an RBF kernel and fit it on labeled training data', 'fit a _BinaryGaussianProcessClassifierLaplace on binary labeled data with Laplace approximation', 'predict class labels for test vectors using a fitted GaussianProcessClassifier', 'predict class probability estimates for test vectors using a fitted GaussianProcessClassifier', 'compute the log-marginal likelihood of kernel hyperparameters for a fitted GaussianProcessClassifier', 'fit a Gaussian process regression model on training data X and target values y', 'predict target values using a fitted Gaussian process regression model at query points', 'draw random samples from a Gaussian process and evaluate them at given input points', 'compute the log-marginal likelihood of kernel hyperparameters for training data', 'optimize kernel hyperparameters by maximizing the log-marginal likelihood with L-BFGS-B optimizer', 'create an RBF kernel with configurable length scale and bounds for Gaussian process regression', 'create a Matern kernel with configurable nu smoothness parameter and length scale', 'create an ExpSineSquared periodic kernel with length scale and periodicity parameters', 'combine kernels using addition and multiplication operators to build composite covariance functions', 'build a Gaussian process regression model using composite kernels for hyperparameter optimization']
```

Usage

```
{'create_gpc_classifier': 'create a GaussianProcessClassifier with an RBF kernel and fit it on labeled training data', 'fit_gpc_binary_classification': 'fit a _BinaryGaussianProcessClassifierLaplace on binary labeled data with Laplace approximation', 'predict_gpc_classes': 'predict class labels for test vectors using a fitted GaussianProcessClassifier', 'predict_gpc_probabilities': 'predict class probability estimates for test vectors using a fitted GaussianProcessClassifier', 'compute_gpc_log_marginal_likelihood': 'compute the log-marginal likelihood of kernel hyperparameters for a fitted GaussianProcessClassifier'}
```

## File: scikit-learn_scikit-learn/sklearn/gaussian_process/_gpr.py

Prompts

```
['create a GaussianProcessClassifier with an RBF kernel and fit it on labeled training data', 'fit a _BinaryGaussianProcessClassifierLaplace on binary labeled data with Laplace approximation', 'predict class labels for test vectors using a fitted GaussianProcessClassifier', 'predict class probability estimates for test vectors using a fitted GaussianProcessClassifier', 'compute the log-marginal likelihood of kernel hyperparameters for a fitted GaussianProcessClassifier', 'fit a Gaussian process regression model on training data X and target values y', 'predict target values using a fitted Gaussian process regression model at query points', 'draw random samples from a Gaussian process and evaluate them at given input points', 'compute the log-marginal likelihood of kernel hyperparameters for training data', 'optimize kernel hyperparameters by maximizing the log-marginal likelihood with L-BFGS-B optimizer', 'create an RBF kernel with configurable length scale and bounds for Gaussian process regression', 'create a Matern kernel with configurable nu smoothness parameter and length scale', 'create an ExpSineSquared periodic kernel with length scale and periodicity parameters', 'combine kernels using addition and multiplication operators to build composite covariance functions', 'build a Gaussian process regression model using composite kernels for hyperparameter optimization']
```

Usage

```
{'fit_gaussian_process_regression': 'fit a Gaussian process regression model on training data X and target values y', 'predict_with_gaussian_process': 'predict target values using a fitted Gaussian process regression model at query points', 'sample_from_gaussian_process': 'draw random samples from a Gaussian process and evaluate them at given input points', 'compute_log_marginal_likelihood': 'compute the log-marginal likelihood of kernel hyperparameters for training data', 'optimize_kernel_hyperparameters': 'optimize kernel hyperparameters by maximizing the log-marginal likelihood with L-BFGS-B optimizer'}
```

## File: scikit-learn_scikit-learn/sklearn/gaussian_process/kernels.py

Prompts

```
['create a GaussianProcessClassifier with an RBF kernel and fit it on labeled training data', 'fit a _BinaryGaussianProcessClassifierLaplace on binary labeled data with Laplace approximation', 'predict class labels for test vectors using a fitted GaussianProcessClassifier', 'predict class probability estimates for test vectors using a fitted GaussianProcessClassifier', 'compute the log-marginal likelihood of kernel hyperparameters for a fitted GaussianProcessClassifier', 'fit a Gaussian process regression model on training data X and target values y', 'predict target values using a fitted Gaussian process regression model at query points', 'draw random samples from a Gaussian process and evaluate them at given input points', 'compute the log-marginal likelihood of kernel hyperparameters for training data', 'optimize kernel hyperparameters by maximizing the log-marginal likelihood with L-BFGS-B optimizer', 'create an RBF kernel with configurable length scale and bounds for Gaussian process regression', 'create a Matern kernel with configurable nu smoothness parameter and length scale', 'create an ExpSineSquared periodic kernel with length scale and periodicity parameters', 'combine kernels using addition and multiplication operators to build composite covariance functions', 'build a Gaussian process regression model using composite kernels for hyperparameter optimization']
```

Usage

```
{'create_kernel_rbf': 'create an RBF kernel with configurable length scale and bounds for Gaussian process regression', 'create_kernel_matern': 'create a Matern kernel with configurable nu smoothness parameter and length scale', 'create_kernel_periodic': 'create an ExpSineSquared periodic kernel with length scale and periodicity parameters', 'combine_kernels_add_multiply': 'combine kernels using addition and multiplication operators to build composite covariance functions', 'build_gp_regression_kernel': 'build a Gaussian process regression model using composite kernels for hyperparameter optimization'}
```

