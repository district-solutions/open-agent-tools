# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/sklearn/neural_network/tests/test_base.py

Prompts

```
['test the binary_log_loss function returns a finite value when y_proba contains 1.0', 'test the log_loss function returns a finite value when y_proba contains 1.0', 'test the poisson_loss function against HalfPoissonLoss with sample weights', 'test MLPClassifier for binary and multi-class classification with various solvers and activation functions', 'test MLPRegressor for regression tasks with lbfgs solver and multiple activation types', 'test MLPClassifier partial_fit for incremental online learning with SGD solver', 'test MLPClassifier predict_proba and predict_log_proba for binary, multi-class, and multi-label classification', 'test MLPClassifier early stopping with validation set splitting and n_iter_no_change convergence', 'test the BernoulliRBM fit method to train on digit data and verify score_samples output', 'test the BernoulliRBM partial_fit method for incremental training on batched data', 'test the BernoulliRBM transform method to verify hidden layer activations match _mean_hiddens', 'test the BernoulliRBM gibbs sampling method to verify reconstruction and numerical stability', 'test the BernoulliRBM score_samples method to verify pseudo-likelihood computation on sparse and dense inputs', 'test the BaseOptimizer class with various learning rates and verify trigger_stopping behavior', 'test the SGDOptimizer class without momentum updates on parameter arrays', 'test the SGDOptimizer class with momentum and verify velocity-based parameter updates', 'test the SGDOptimizer class with Nesterov momentum and verify double-update parameter updates', 'test the AdamOptimizer class with various beta parameters and verify biased-corrected adaptive learning rate updates']
```

Usage

```
{'test_binary_log_loss': 'test the binary_log_loss function returns a finite value when y_proba contains 1.0', 'test_log_loss': 'test the log_loss function returns a finite value when y_proba contains 1.0', 'test_poisson_loss': 'test the poisson_loss function against HalfPoissonLoss with sample weights'}
```

## File: scikit-learn_scikit-learn/sklearn/neural_network/tests/test_mlp.py

Prompts

```
['test the binary_log_loss function returns a finite value when y_proba contains 1.0', 'test the log_loss function returns a finite value when y_proba contains 1.0', 'test the poisson_loss function against HalfPoissonLoss with sample weights', 'test MLPClassifier for binary and multi-class classification with various solvers and activation functions', 'test MLPRegressor for regression tasks with lbfgs solver and multiple activation types', 'test MLPClassifier partial_fit for incremental online learning with SGD solver', 'test MLPClassifier predict_proba and predict_log_proba for binary, multi-class, and multi-label classification', 'test MLPClassifier early stopping with validation set splitting and n_iter_no_change convergence', 'test the BernoulliRBM fit method to train on digit data and verify score_samples output', 'test the BernoulliRBM partial_fit method for incremental training on batched data', 'test the BernoulliRBM transform method to verify hidden layer activations match _mean_hiddens', 'test the BernoulliRBM gibbs sampling method to verify reconstruction and numerical stability', 'test the BernoulliRBM score_samples method to verify pseudo-likelihood computation on sparse and dense inputs', 'test the BaseOptimizer class with various learning rates and verify trigger_stopping behavior', 'test the SGDOptimizer class without momentum updates on parameter arrays', 'test the SGDOptimizer class with momentum and verify velocity-based parameter updates', 'test the SGDOptimizer class with Nesterov momentum and verify double-update parameter updates', 'test the AdamOptimizer class with various beta parameters and verify biased-corrected adaptive learning rate updates']
```

Usage

```
{'test_MLPClassifier_classification': 'test MLPClassifier for binary and multi-class classification with various solvers and activation functions', 'test_MLPRegressor_regression': 'test MLPRegressor for regression tasks with lbfgs solver and multiple activation types', 'test_MLPClassifier_partial_fit': 'test MLPClassifier partial_fit for incremental online learning with SGD solver', 'test_MLPClassifier_predict_proba': 'test MLPClassifier predict_proba and predict_log_proba for binary, multi-class, and multi-label classification', 'test_MLPClassifier_early_stopping': 'test MLPClassifier early stopping with validation set splitting and n_iter_no_change convergence'}
```

## File: scikit-learn_scikit-learn/sklearn/neural_network/tests/test_rbm.py

Prompts

```
['test the binary_log_loss function returns a finite value when y_proba contains 1.0', 'test the log_loss function returns a finite value when y_proba contains 1.0', 'test the poisson_loss function against HalfPoissonLoss with sample weights', 'test MLPClassifier for binary and multi-class classification with various solvers and activation functions', 'test MLPRegressor for regression tasks with lbfgs solver and multiple activation types', 'test MLPClassifier partial_fit for incremental online learning with SGD solver', 'test MLPClassifier predict_proba and predict_log_proba for binary, multi-class, and multi-label classification', 'test MLPClassifier early stopping with validation set splitting and n_iter_no_change convergence', 'test the BernoulliRBM fit method to train on digit data and verify score_samples output', 'test the BernoulliRBM partial_fit method for incremental training on batched data', 'test the BernoulliRBM transform method to verify hidden layer activations match _mean_hiddens', 'test the BernoulliRBM gibbs sampling method to verify reconstruction and numerical stability', 'test the BernoulliRBM score_samples method to verify pseudo-likelihood computation on sparse and dense inputs', 'test the BaseOptimizer class with various learning rates and verify trigger_stopping behavior', 'test the SGDOptimizer class without momentum updates on parameter arrays', 'test the SGDOptimizer class with momentum and verify velocity-based parameter updates', 'test the SGDOptimizer class with Nesterov momentum and verify double-update parameter updates', 'test the AdamOptimizer class with various beta parameters and verify biased-corrected adaptive learning rate updates']
```

Usage

```
{'test_rbm_fit': 'test the BernoulliRBM fit method to train on digit data and verify score_samples output', 'test_rbm_partial_fit': 'test the BernoulliRBM partial_fit method for incremental training on batched data', 'test_rbm_transform': 'test the BernoulliRBM transform method to verify hidden layer activations match _mean_hiddens', 'test_rbm_gibbs': 'test the BernoulliRBM gibbs sampling method to verify reconstruction and numerical stability', 'test_rbm_score_samples': 'test the BernoulliRBM score_samples method to verify pseudo-likelihood computation on sparse and dense inputs'}
```

## File: scikit-learn_scikit-learn/sklearn/neural_network/tests/test_stochastic_optimizers.py

Prompts

```
['test the binary_log_loss function returns a finite value when y_proba contains 1.0', 'test the log_loss function returns a finite value when y_proba contains 1.0', 'test the poisson_loss function against HalfPoissonLoss with sample weights', 'test MLPClassifier for binary and multi-class classification with various solvers and activation functions', 'test MLPRegressor for regression tasks with lbfgs solver and multiple activation types', 'test MLPClassifier partial_fit for incremental online learning with SGD solver', 'test MLPClassifier predict_proba and predict_log_proba for binary, multi-class, and multi-label classification', 'test MLPClassifier early stopping with validation set splitting and n_iter_no_change convergence', 'test the BernoulliRBM fit method to train on digit data and verify score_samples output', 'test the BernoulliRBM partial_fit method for incremental training on batched data', 'test the BernoulliRBM transform method to verify hidden layer activations match _mean_hiddens', 'test the BernoulliRBM gibbs sampling method to verify reconstruction and numerical stability', 'test the BernoulliRBM score_samples method to verify pseudo-likelihood computation on sparse and dense inputs', 'test the BaseOptimizer class with various learning rates and verify trigger_stopping behavior', 'test the SGDOptimizer class without momentum updates on parameter arrays', 'test the SGDOptimizer class with momentum and verify velocity-based parameter updates', 'test the SGDOptimizer class with Nesterov momentum and verify double-update parameter updates', 'test the AdamOptimizer class with various beta parameters and verify biased-corrected adaptive learning rate updates']
```

Usage

```
{'test_base_optimizer': 'test the BaseOptimizer class with various learning rates and verify trigger_stopping behavior', 'test_sgd_optimizer_no_momentum': 'test the SGDOptimizer class without momentum updates on parameter arrays', 'test_sgd_optimizer_momentum': 'test the SGDOptimizer class with momentum and verify velocity-based parameter updates', 'test_sgd_optimizer_nesterovs_momentum': 'test the SGDOptimizer class with Nesterov momentum and verify double-update parameter updates', 'test_adam_optimizer': 'test the AdamOptimizer class with various beta parameters and verify biased-corrected adaptive learning rate updates'}
```

