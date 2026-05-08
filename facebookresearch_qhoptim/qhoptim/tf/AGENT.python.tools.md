# Agent Python Tools

- repo: facebookresearch/qhoptim
- repo_uri: https://github.com/facebookresearch/qhoptim

## File: facebookresearch_qhoptim/qhoptim/tf/qhadam.py

Prompts

```
['create a QHAdamOptimizer instance with custom learning rate, nu1, nu2, beta1, and beta2 hyperparameters', 'create a QHAdamOptimizer configured to recover NAdam behavior using the from_nadam classmethod', 'apply dense gradient updates to TensorFlow variables using the QHAdamOptimizer _apply_dense method', 'apply sparse gradient updates to TensorFlow variables using the QHAdamOptimizer _apply_sparse method', 'convert QHAdam parameter object to a dictionary with learning_rate, nu1, nu2, beta1, and beta2 keys', 'create a QHM optimizer with learning rate, momentum, and nu parameters for TensorFlow training', 'create a QHM optimizer from PID controller gains k_p, k_i, and k_d parameters', 'create a QHM optimizer from synthesized Nesterov parameters alpha, beta1, and beta2', 'create a QHM optimizer from robust momentum Lipschitz constant and condition ratio parameters', 'create a QHM optimizer from AccSGD delta, kappa, and xi parameters', ['Evaluate a parameter that may be a callable or a static value', 'Conditionally invoke a function or return its raw value in TensorFlow utility code', 'Simplify lazy evaluation patterns where a config value might be a lambda', 'Handle both direct values and callable factories uniformly in optimization code', 'Reduce boilerplate when a parameter can be either a constant or a function'], {'use_call_if_callable': 'use call_if_callable to evaluate a param that may be a callable or static value', 'test_call_if_callable': 'test call_if_callable with a lambda and a plain integer to verify both branches', 'refactor_call_if_callable': 'refactor call_if_callable to add type hints and docstring for better discoverability', 'review_call_if_callable': 'review call_if_callable to confirm it safely handles None and non-callable types', 'summarize_call_if_callable': 'summarize call_if_callable as a utility that returns param() if callable else param'}]
```

Usage

```
{'create_qhadam_optimizer': 'create a QHAdamOptimizer instance with custom learning rate, nu1, nu2, beta1, and beta2 hyperparameters', 'create_qhadam_from_nadam': 'create a QHAdamOptimizer configured to recover NAdam behavior using the from_nadam classmethod', 'apply_dense_gradients': 'apply dense gradient updates to TensorFlow variables using the QHAdamOptimizer _apply_dense method', 'apply_sparse_gradients': 'apply sparse gradient updates to TensorFlow variables using the QHAdamOptimizer _apply_sparse method', 'convert_params_to_dict': 'convert QHAdam parameter object to a dictionary with learning_rate, nu1, nu2, beta1, and beta2 keys'}
```

## File: facebookresearch_qhoptim/qhoptim/tf/qhm.py

Prompts

```
['create a QHAdamOptimizer instance with custom learning rate, nu1, nu2, beta1, and beta2 hyperparameters', 'create a QHAdamOptimizer configured to recover NAdam behavior using the from_nadam classmethod', 'apply dense gradient updates to TensorFlow variables using the QHAdamOptimizer _apply_dense method', 'apply sparse gradient updates to TensorFlow variables using the QHAdamOptimizer _apply_sparse method', 'convert QHAdam parameter object to a dictionary with learning_rate, nu1, nu2, beta1, and beta2 keys', 'create a QHM optimizer with learning rate, momentum, and nu parameters for TensorFlow training', 'create a QHM optimizer from PID controller gains k_p, k_i, and k_d parameters', 'create a QHM optimizer from synthesized Nesterov parameters alpha, beta1, and beta2', 'create a QHM optimizer from robust momentum Lipschitz constant and condition ratio parameters', 'create a QHM optimizer from AccSGD delta, kappa, and xi parameters', ['Evaluate a parameter that may be a callable or a static value', 'Conditionally invoke a function or return its raw value in TensorFlow utility code', 'Simplify lazy evaluation patterns where a config value might be a lambda', 'Handle both direct values and callable factories uniformly in optimization code', 'Reduce boilerplate when a parameter can be either a constant or a function'], {'use_call_if_callable': 'use call_if_callable to evaluate a param that may be a callable or static value', 'test_call_if_callable': 'test call_if_callable with a lambda and a plain integer to verify both branches', 'refactor_call_if_callable': 'refactor call_if_callable to add type hints and docstring for better discoverability', 'review_call_if_callable': 'review call_if_callable to confirm it safely handles None and non-callable types', 'summarize_call_if_callable': 'summarize call_if_callable as a utility that returns param() if callable else param'}]
```

Usage

```
{'create_QHMOptimizer': 'create a QHM optimizer with learning rate, momentum, and nu parameters for TensorFlow training', 'create_QHMOptimizer_from_pid': 'create a QHM optimizer from PID controller gains k_p, k_i, and k_d parameters', 'create_QHMOptimizer_from_synthesized_nesterov': 'create a QHM optimizer from synthesized Nesterov parameters alpha, beta1, and beta2', 'create_QHMOptimizer_from_robust_momentum': 'create a QHM optimizer from robust momentum Lipschitz constant and condition ratio parameters', 'create_QHMOptimizer_from_accsgd': 'create a QHM optimizer from AccSGD delta, kappa, and xi parameters'}
```

## File: facebookresearch_qhoptim/qhoptim/tf/util.py

Prompts

```
['create a QHAdamOptimizer instance with custom learning rate, nu1, nu2, beta1, and beta2 hyperparameters', 'create a QHAdamOptimizer configured to recover NAdam behavior using the from_nadam classmethod', 'apply dense gradient updates to TensorFlow variables using the QHAdamOptimizer _apply_dense method', 'apply sparse gradient updates to TensorFlow variables using the QHAdamOptimizer _apply_sparse method', 'convert QHAdam parameter object to a dictionary with learning_rate, nu1, nu2, beta1, and beta2 keys', 'create a QHM optimizer with learning rate, momentum, and nu parameters for TensorFlow training', 'create a QHM optimizer from PID controller gains k_p, k_i, and k_d parameters', 'create a QHM optimizer from synthesized Nesterov parameters alpha, beta1, and beta2', 'create a QHM optimizer from robust momentum Lipschitz constant and condition ratio parameters', 'create a QHM optimizer from AccSGD delta, kappa, and xi parameters', ['Evaluate a parameter that may be a callable or a static value', 'Conditionally invoke a function or return its raw value in TensorFlow utility code', 'Simplify lazy evaluation patterns where a config value might be a lambda', 'Handle both direct values and callable factories uniformly in optimization code', 'Reduce boilerplate when a parameter can be either a constant or a function'], {'use_call_if_callable': 'use call_if_callable to evaluate a param that may be a callable or static value', 'test_call_if_callable': 'test call_if_callable with a lambda and a plain integer to verify both branches', 'refactor_call_if_callable': 'refactor call_if_callable to add type hints and docstring for better discoverability', 'review_call_if_callable': 'review call_if_callable to confirm it safely handles None and non-callable types', 'summarize_call_if_callable': 'summarize call_if_callable as a utility that returns param() if callable else param'}]
```

Usage

```
{'use_cases': ['Evaluate a parameter that may be a callable or a static value', 'Conditionally invoke a function or return its raw value in TensorFlow utility code', 'Simplify lazy evaluation patterns where a config value might be a lambda', 'Handle both direct values and callable factories uniformly in optimization code', 'Reduce boilerplate when a parameter can be either a constant or a function'], 'examples': {'use_call_if_callable': 'use call_if_callable to evaluate a param that may be a callable or static value', 'test_call_if_callable': 'test call_if_callable with a lambda and a plain integer to verify both branches', 'refactor_call_if_callable': 'refactor call_if_callable to add type hints and docstring for better discoverability', 'review_call_if_callable': 'review call_if_callable to confirm it safely handles None and non-callable types', 'summarize_call_if_callable': 'summarize call_if_callable as a utility that returns param() if callable else param'}}
```

