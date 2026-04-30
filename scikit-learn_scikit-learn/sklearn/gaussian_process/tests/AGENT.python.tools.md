# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/sklearn/gaussian_process/tests/_mini_sequence_kernel.py

Prompts

```
['create a MiniSeqKernel convolutional kernel for sequences with a configurable baseline similarity', 'test the MiniSeqKernel __call__ method to compute the kernel matrix between two sequence sets', 'test the MiniSeqKernel diag method to compute the diagonal of the kernel matrix', 'test the MiniSeqKernel clone_with_theta method to clone the kernel with optimized hyperparameters', 'test the MiniSeqKernel hyperparameter_baseline_similarity property to access the kernel hyperparameter definition', 'test the GaussianProcessClassifier to verify binary predict decision matches predicted probability above 0.5', 'test the GaussianProcessClassifier for multi-class classification problems with predict_proba summing to 1', 'test the GaussianProcessClassifier log-marginal-likelihood analytic and numeric gradient comparison', 'test the GaussianProcessClassifier with increasing n_restarts_optimizer to improve log marginal likelihood', 'test the GaussianProcessClassifier with an externally defined optimizer for hyperparameter tuning', 'test the GaussianProcessClassifier latent_mean_and_variance returns correct shape for binary classification', 'test the GaussianProcessClassifier raises ConvergenceWarning when parameters hit bounds', 'test GaussianProcessRegressor interpolates training data exactly with fixed kernel', 'test that hyperparameter optimization improves log-marginal likelihood for non-fixed kernels', 'test that predicted standard deviation is consistent with covariance diagonal', 'test that increasing n_restarts_optimizer only increases log marginal likelihood', 'test output shapes of predict for single-output and multi-output settings', 'test the kernel gradient by comparing analytic and numeric gradient using eval_gradient parameter', 'test the kernel theta parameter vector is set correctly and consistent with hyperparameter values', 'test auto-correlation and cross-correlation produce consistent kernel matrix results', 'test sklearn clone works correctly on kernels preserving parameters and hyperparameters', 'test Matern kernel consistency for special nu values matching RBF and exponential kernels']
```

Usage

```
{'create_MiniSeqKernel': 'create a MiniSeqKernel convolutional kernel for sequences with a configurable baseline similarity', 'test_MiniSeqKernel_call': 'test the MiniSeqKernel __call__ method to compute the kernel matrix between two sequence sets', 'test_MiniSeqKernel_diag': 'test the MiniSeqKernel diag method to compute the diagonal of the kernel matrix', 'test_MiniSeqKernel_clone_with_theta': 'test the MiniSeqKernel clone_with_theta method to clone the kernel with optimized hyperparameters', 'test_MiniSeqKernel_hyperparameter': 'test the MiniSeqKernel hyperparameter_baseline_similarity property to access the kernel hyperparameter definition'}
```

## File: scikit-learn_scikit-learn/sklearn/gaussian_process/tests/test_gpc.py

Prompts

```
['create a MiniSeqKernel convolutional kernel for sequences with a configurable baseline similarity', 'test the MiniSeqKernel __call__ method to compute the kernel matrix between two sequence sets', 'test the MiniSeqKernel diag method to compute the diagonal of the kernel matrix', 'test the MiniSeqKernel clone_with_theta method to clone the kernel with optimized hyperparameters', 'test the MiniSeqKernel hyperparameter_baseline_similarity property to access the kernel hyperparameter definition', 'test the GaussianProcessClassifier to verify binary predict decision matches predicted probability above 0.5', 'test the GaussianProcessClassifier for multi-class classification problems with predict_proba summing to 1', 'test the GaussianProcessClassifier log-marginal-likelihood analytic and numeric gradient comparison', 'test the GaussianProcessClassifier with increasing n_restarts_optimizer to improve log marginal likelihood', 'test the GaussianProcessClassifier with an externally defined optimizer for hyperparameter tuning', 'test the GaussianProcessClassifier latent_mean_and_variance returns correct shape for binary classification', 'test the GaussianProcessClassifier raises ConvergenceWarning when parameters hit bounds', 'test GaussianProcessRegressor interpolates training data exactly with fixed kernel', 'test that hyperparameter optimization improves log-marginal likelihood for non-fixed kernels', 'test that predicted standard deviation is consistent with covariance diagonal', 'test that increasing n_restarts_optimizer only increases log marginal likelihood', 'test output shapes of predict for single-output and multi-output settings', 'test the kernel gradient by comparing analytic and numeric gradient using eval_gradient parameter', 'test the kernel theta parameter vector is set correctly and consistent with hyperparameter values', 'test auto-correlation and cross-correlation produce consistent kernel matrix results', 'test sklearn clone works correctly on kernels preserving parameters and hyperparameters', 'test Matern kernel consistency for special nu values matching RBF and exponential kernels']
```

Usage

```
{'test_GaussianProcessClassifier_predict': 'test the GaussianProcessClassifier to verify binary predict decision matches predicted probability above 0.5', 'test_GaussianProcessClassifier_multi_class': 'test the GaussianProcessClassifier for multi-class classification problems with predict_proba summing to 1', 'test_GaussianProcessClassifier_lml_gradient': 'test the GaussianProcessClassifier log-marginal-likelihood analytic and numeric gradient comparison', 'test_GaussianProcessClassifier_random_starts': 'test the GaussianProcessClassifier with increasing n_restarts_optimizer to improve log marginal likelihood', 'test_GaussianProcessClassifier_custom_optimizer': 'test the GaussianProcessClassifier with an externally defined optimizer for hyperparameter tuning', 'test_GaussianProcessClassifier_latent_mean_and_variance': 'test the GaussianProcessClassifier latent_mean_and_variance returns correct shape for binary classification', 'test_GaussianProcessClassifier_warning_bounds': 'test the GaussianProcessClassifier raises ConvergenceWarning when parameters hit bounds'}
```

## File: scikit-learn_scikit-learn/sklearn/gaussian_process/tests/test_gpr.py

Prompts

```
['create a MiniSeqKernel convolutional kernel for sequences with a configurable baseline similarity', 'test the MiniSeqKernel __call__ method to compute the kernel matrix between two sequence sets', 'test the MiniSeqKernel diag method to compute the diagonal of the kernel matrix', 'test the MiniSeqKernel clone_with_theta method to clone the kernel with optimized hyperparameters', 'test the MiniSeqKernel hyperparameter_baseline_similarity property to access the kernel hyperparameter definition', 'test the GaussianProcessClassifier to verify binary predict decision matches predicted probability above 0.5', 'test the GaussianProcessClassifier for multi-class classification problems with predict_proba summing to 1', 'test the GaussianProcessClassifier log-marginal-likelihood analytic and numeric gradient comparison', 'test the GaussianProcessClassifier with increasing n_restarts_optimizer to improve log marginal likelihood', 'test the GaussianProcessClassifier with an externally defined optimizer for hyperparameter tuning', 'test the GaussianProcessClassifier latent_mean_and_variance returns correct shape for binary classification', 'test the GaussianProcessClassifier raises ConvergenceWarning when parameters hit bounds', 'test GaussianProcessRegressor interpolates training data exactly with fixed kernel', 'test that hyperparameter optimization improves log-marginal likelihood for non-fixed kernels', 'test that predicted standard deviation is consistent with covariance diagonal', 'test that increasing n_restarts_optimizer only increases log marginal likelihood', 'test output shapes of predict for single-output and multi-output settings', 'test the kernel gradient by comparing analytic and numeric gradient using eval_gradient parameter', 'test the kernel theta parameter vector is set correctly and consistent with hyperparameter values', 'test auto-correlation and cross-correlation produce consistent kernel matrix results', 'test sklearn clone works correctly on kernels preserving parameters and hyperparameters', 'test Matern kernel consistency for special nu values matching RBF and exponential kernels']
```

Usage

```
{'test_gpr_interpolation': 'test GaussianProcessRegressor interpolates training data exactly with fixed kernel', 'test_lml_improving': 'test that hyperparameter optimization improves log-marginal likelihood for non-fixed kernels', 'test_gpr_predict_cov_vs_std': 'test that predicted standard deviation is consistent with covariance diagonal', 'test_random_starts': 'test that increasing n_restarts_optimizer only increases log marginal likelihood', 'test_predict_shapes': 'test output shapes of predict for single-output and multi-output settings'}
```

## File: scikit-learn_scikit-learn/sklearn/gaussian_process/tests/test_kernels.py

Prompts

```
['create a MiniSeqKernel convolutional kernel for sequences with a configurable baseline similarity', 'test the MiniSeqKernel __call__ method to compute the kernel matrix between two sequence sets', 'test the MiniSeqKernel diag method to compute the diagonal of the kernel matrix', 'test the MiniSeqKernel clone_with_theta method to clone the kernel with optimized hyperparameters', 'test the MiniSeqKernel hyperparameter_baseline_similarity property to access the kernel hyperparameter definition', 'test the GaussianProcessClassifier to verify binary predict decision matches predicted probability above 0.5', 'test the GaussianProcessClassifier for multi-class classification problems with predict_proba summing to 1', 'test the GaussianProcessClassifier log-marginal-likelihood analytic and numeric gradient comparison', 'test the GaussianProcessClassifier with increasing n_restarts_optimizer to improve log marginal likelihood', 'test the GaussianProcessClassifier with an externally defined optimizer for hyperparameter tuning', 'test the GaussianProcessClassifier latent_mean_and_variance returns correct shape for binary classification', 'test the GaussianProcessClassifier raises ConvergenceWarning when parameters hit bounds', 'test GaussianProcessRegressor interpolates training data exactly with fixed kernel', 'test that hyperparameter optimization improves log-marginal likelihood for non-fixed kernels', 'test that predicted standard deviation is consistent with covariance diagonal', 'test that increasing n_restarts_optimizer only increases log marginal likelihood', 'test output shapes of predict for single-output and multi-output settings', 'test the kernel gradient by comparing analytic and numeric gradient using eval_gradient parameter', 'test the kernel theta parameter vector is set correctly and consistent with hyperparameter values', 'test auto-correlation and cross-correlation produce consistent kernel matrix results', 'test sklearn clone works correctly on kernels preserving parameters and hyperparameters', 'test Matern kernel consistency for special nu values matching RBF and exponential kernels']
```

Usage

```
{'test_kernel_gradient': 'test the kernel gradient by comparing analytic and numeric gradient using eval_gradient parameter', 'test_kernel_theta': 'test the kernel theta parameter vector is set correctly and consistent with hyperparameter values', 'test_auto_vs_cross': 'test auto-correlation and cross-correlation produce consistent kernel matrix results', 'test_kernel_clone': 'test sklearn clone works correctly on kernels preserving parameters and hyperparameters', 'test_matern_kernel': 'test Matern kernel consistency for special nu values matching RBF and exponential kernels'}
```

