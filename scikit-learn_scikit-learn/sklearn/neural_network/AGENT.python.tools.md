# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/sklearn/neural_network/_base.py

Prompts

```
['create a module to apply activation functions like relu, tanh, logistic, softmax inplace on numpy arrays', 'create a module to compute derivatives of activation functions for backpropagation', 'create a module to compute loss functions including squared_error, poisson, log_loss, and binary_log_loss', 'test the ACTIVATIONS dictionary maps activation names to their corresponding inplace functions', 'test the DERIVATIVES dictionary maps activation names to their derivative functions for backpropagation', 'test the LOSS_FUNCTIONS dictionary maps loss names to their corresponding loss computation functions', 'summarize the inplace_softmax function that computes K-way softmax with numerical stability', 'create an MLPClassifier with relu activation and adam solver for multi-class classification', 'create an MLPRegressor with squared_error loss for regression on continuous target values', 'fit an MLPClassifier on training data and evaluate with accuracy score', 'fit an MLPRegressor on training data and evaluate with r2 score', 'train an MLPClassifier incrementally using partial_fit with specified classes', 'create a BernoulliRBM transformer with configurable hidden units and learning rate for dimensionality reduction', 'fit a BernoulliRBM model to training data using stochastic maximum likelihood training', 'transform input data into latent representations using a fitted BernoulliRBM model', 'score samples with a fitted BernoulliRBM to compute pseudo-likelihood estimates', 'perform one Gibbs sampling step on a fitted BernoulliRBM to generate reconstructed visible samples', 'create an SGDOptimizer instance with momentum, nesterov, and invscaling learning rate schedule for MLP training', 'create an AdamOptimizer instance with configurable beta_1, beta_2, and epsilon for MLP weight updates', 'build parameter updates using BaseOptimizer.update_params with coefs and intercepts gradients', 'test SGDOptimizer iteration_ends to update learning rate with invscaling schedule at each time step', 'review AdamOptimizer._get_updates to compute bias-corrected moment estimates and weight updates']
```

Usage

```
{'create_activation_functions': 'create a module to apply activation functions like relu, tanh, logistic, softmax inplace on numpy arrays', 'create_derivative_functions': 'create a module to compute derivatives of activation functions for backpropagation', 'create_loss_functions': 'create a module to compute loss functions including squared_error, poisson, log_loss, and binary_log_loss', 'test_ACTIVATIONS': 'test the ACTIVATIONS dictionary maps activation names to their corresponding inplace functions', 'test_DERIVATIVES': 'test the DERIVATIVES dictionary maps activation names to their derivative functions for backpropagation', 'test_LOSS_FUNCTIONS': 'test the LOSS_FUNCTIONS dictionary maps loss names to their corresponding loss computation functions', 'summarize_inplace_softmax': 'summarize the inplace_softmax function that computes K-way softmax with numerical stability'}
```

## File: scikit-learn_scikit-learn/sklearn/neural_network/_multilayer_perceptron.py

Prompts

```
['create a module to apply activation functions like relu, tanh, logistic, softmax inplace on numpy arrays', 'create a module to compute derivatives of activation functions for backpropagation', 'create a module to compute loss functions including squared_error, poisson, log_loss, and binary_log_loss', 'test the ACTIVATIONS dictionary maps activation names to their corresponding inplace functions', 'test the DERIVATIVES dictionary maps activation names to their derivative functions for backpropagation', 'test the LOSS_FUNCTIONS dictionary maps loss names to their corresponding loss computation functions', 'summarize the inplace_softmax function that computes K-way softmax with numerical stability', 'create an MLPClassifier with relu activation and adam solver for multi-class classification', 'create an MLPRegressor with squared_error loss for regression on continuous target values', 'fit an MLPClassifier on training data and evaluate with accuracy score', 'fit an MLPRegressor on training data and evaluate with r2 score', 'train an MLPClassifier incrementally using partial_fit with specified classes', 'create a BernoulliRBM transformer with configurable hidden units and learning rate for dimensionality reduction', 'fit a BernoulliRBM model to training data using stochastic maximum likelihood training', 'transform input data into latent representations using a fitted BernoulliRBM model', 'score samples with a fitted BernoulliRBM to compute pseudo-likelihood estimates', 'perform one Gibbs sampling step on a fitted BernoulliRBM to generate reconstructed visible samples', 'create an SGDOptimizer instance with momentum, nesterov, and invscaling learning rate schedule for MLP training', 'create an AdamOptimizer instance with configurable beta_1, beta_2, and epsilon for MLP weight updates', 'build parameter updates using BaseOptimizer.update_params with coefs and intercepts gradients', 'test SGDOptimizer iteration_ends to update learning rate with invscaling schedule at each time step', 'review AdamOptimizer._get_updates to compute bias-corrected moment estimates and weight updates']
```

Usage

```
{'create_MLPClassifier': 'create an MLPClassifier with relu activation and adam solver for multi-class classification', 'create_MLPRegressor': 'create an MLPRegressor with squared_error loss for regression on continuous target values', 'fit_MLPClassifier': 'fit an MLPClassifier on training data and evaluate with accuracy score', 'fit_MLPRegressor': 'fit an MLPRegressor on training data and evaluate with r2 score', 'train_incremental_MLP': 'train an MLPClassifier incrementally using partial_fit with specified classes'}
```

## File: scikit-learn_scikit-learn/sklearn/neural_network/_rbm.py

Prompts

```
['create a module to apply activation functions like relu, tanh, logistic, softmax inplace on numpy arrays', 'create a module to compute derivatives of activation functions for backpropagation', 'create a module to compute loss functions including squared_error, poisson, log_loss, and binary_log_loss', 'test the ACTIVATIONS dictionary maps activation names to their corresponding inplace functions', 'test the DERIVATIVES dictionary maps activation names to their derivative functions for backpropagation', 'test the LOSS_FUNCTIONS dictionary maps loss names to their corresponding loss computation functions', 'summarize the inplace_softmax function that computes K-way softmax with numerical stability', 'create an MLPClassifier with relu activation and adam solver for multi-class classification', 'create an MLPRegressor with squared_error loss for regression on continuous target values', 'fit an MLPClassifier on training data and evaluate with accuracy score', 'fit an MLPRegressor on training data and evaluate with r2 score', 'train an MLPClassifier incrementally using partial_fit with specified classes', 'create a BernoulliRBM transformer with configurable hidden units and learning rate for dimensionality reduction', 'fit a BernoulliRBM model to training data using stochastic maximum likelihood training', 'transform input data into latent representations using a fitted BernoulliRBM model', 'score samples with a fitted BernoulliRBM to compute pseudo-likelihood estimates', 'perform one Gibbs sampling step on a fitted BernoulliRBM to generate reconstructed visible samples', 'create an SGDOptimizer instance with momentum, nesterov, and invscaling learning rate schedule for MLP training', 'create an AdamOptimizer instance with configurable beta_1, beta_2, and epsilon for MLP weight updates', 'build parameter updates using BaseOptimizer.update_params with coefs and intercepts gradients', 'test SGDOptimizer iteration_ends to update learning rate with invscaling schedule at each time step', 'review AdamOptimizer._get_updates to compute bias-corrected moment estimates and weight updates']
```

Usage

```
{'create_bernoulli_rbm_transformer': 'create a BernoulliRBM transformer with configurable hidden units and learning rate for dimensionality reduction', 'fit_rbm_model': 'fit a BernoulliRBM model to training data using stochastic maximum likelihood training', 'transform_data_with_rbm': 'transform input data into latent representations using a fitted BernoulliRBM model', 'score_rbm_samples': 'score samples with a fitted BernoulliRBM to compute pseudo-likelihood estimates', 'gibbs_sample_rbm': 'perform one Gibbs sampling step on a fitted BernoulliRBM to generate reconstructed visible samples'}
```

## File: scikit-learn_scikit-learn/sklearn/neural_network/_stochastic_optimizers.py

Prompts

```
['create a module to apply activation functions like relu, tanh, logistic, softmax inplace on numpy arrays', 'create a module to compute derivatives of activation functions for backpropagation', 'create a module to compute loss functions including squared_error, poisson, log_loss, and binary_log_loss', 'test the ACTIVATIONS dictionary maps activation names to their corresponding inplace functions', 'test the DERIVATIVES dictionary maps activation names to their derivative functions for backpropagation', 'test the LOSS_FUNCTIONS dictionary maps loss names to their corresponding loss computation functions', 'summarize the inplace_softmax function that computes K-way softmax with numerical stability', 'create an MLPClassifier with relu activation and adam solver for multi-class classification', 'create an MLPRegressor with squared_error loss for regression on continuous target values', 'fit an MLPClassifier on training data and evaluate with accuracy score', 'fit an MLPRegressor on training data and evaluate with r2 score', 'train an MLPClassifier incrementally using partial_fit with specified classes', 'create a BernoulliRBM transformer with configurable hidden units and learning rate for dimensionality reduction', 'fit a BernoulliRBM model to training data using stochastic maximum likelihood training', 'transform input data into latent representations using a fitted BernoulliRBM model', 'score samples with a fitted BernoulliRBM to compute pseudo-likelihood estimates', 'perform one Gibbs sampling step on a fitted BernoulliRBM to generate reconstructed visible samples', 'create an SGDOptimizer instance with momentum, nesterov, and invscaling learning rate schedule for MLP training', 'create an AdamOptimizer instance with configurable beta_1, beta_2, and epsilon for MLP weight updates', 'build parameter updates using BaseOptimizer.update_params with coefs and intercepts gradients', 'test SGDOptimizer iteration_ends to update learning rate with invscaling schedule at each time step', 'review AdamOptimizer._get_updates to compute bias-corrected moment estimates and weight updates']
```

Usage

```
{'create_SGDOptimizer': 'create an SGDOptimizer instance with momentum, nesterov, and invscaling learning rate schedule for MLP training', 'create_AdamOptimizer': 'create an AdamOptimizer instance with configurable beta_1, beta_2, and epsilon for MLP weight updates', 'build_BaseOptimizer_update': 'build parameter updates using BaseOptimizer.update_params with coefs and intercepts gradients', 'test_SGDOptimizer_iteration_ends': 'test SGDOptimizer iteration_ends to update learning rate with invscaling schedule at each time step', 'review_AdamOptimizer_get_updates': 'review AdamOptimizer._get_updates to compute bias-corrected moment estimates and weight updates'}
```

