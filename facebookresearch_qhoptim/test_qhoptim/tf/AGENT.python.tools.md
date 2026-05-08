# Agent Python Tools

- repo: facebookresearch/qhoptim
- repo_uri: https://github.com/facebookresearch/qhoptim

## File: facebookresearch_qhoptim/test_qhoptim/tf/test_qhadam.py

Prompts

```
['test that QHAdamOptimizer with nu1=1.0 and nu2=1.0 produces identical results to tf.train.AdamOptimizer', 'test constructing QHAdamOptimizer with learning_rate, beta1, beta2, nu1, nu2, and epsilon parameters', 'test that two optimizer constructors produce equal optimization results using assert_optimizers_equal utility', 'review the QHAdamOptimizer class from qhoptim.tf to understand quantized Hessian Adam optimization', 'review the test_adam_equiv function that validates QHAdamOptimizer equivalence to standard Adam', 'test that QHMOptimizer with beta=0.0 produces the same results as plain SGD GradientDescentOptimizer', 'test that QHMOptimizer with nu=1.0 produces the same results as MomentumOptimizer', 'run the test_plain_sgd_equiv function to verify QHMOptimizer equivalence with SGD optimizer', 'run the test_momentum_equiv function to verify QHMOptimizer equivalence with momentum optimizer', 'review the test_qhm module to understand QHMOptimizer equivalence tests against standard TensorFlow optimizers', 'build a TensorFlow variable and optional sparse gather tensor for optimizer testing', 'test two TensorFlow tensors for numerical closeness within absolute and relative tolerance', 'refactor the build_net function to support different sparse indexing strategies for TensorFlow variables', 'review the assert_optimizers_equal function and its linear regression loss setup for optimizer comparison']
```

Usage

```
{'test_QHAdamOptimizer_adam_equiv': 'test that QHAdamOptimizer with nu1=1.0 and nu2=1.0 produces identical results to tf.train.AdamOptimizer', 'test_QHAdamOptimizer_constructor': 'test constructing QHAdamOptimizer with learning_rate, beta1, beta2, nu1, nu2, and epsilon parameters', 'test_assert_optimizers_equal': 'test that two optimizer constructors produce equal optimization results using assert_optimizers_equal utility', 'review_QHAdamOptimizer': 'review the QHAdamOptimizer class from qhoptim.tf to understand quantized Hessian Adam optimization', 'review_test_adam_equiv': 'review the test_adam_equiv function that validates QHAdamOptimizer equivalence to standard Adam'}
```

## File: facebookresearch_qhoptim/test_qhoptim/tf/test_qhm.py

Prompts

```
['test that QHAdamOptimizer with nu1=1.0 and nu2=1.0 produces identical results to tf.train.AdamOptimizer', 'test constructing QHAdamOptimizer with learning_rate, beta1, beta2, nu1, nu2, and epsilon parameters', 'test that two optimizer constructors produce equal optimization results using assert_optimizers_equal utility', 'review the QHAdamOptimizer class from qhoptim.tf to understand quantized Hessian Adam optimization', 'review the test_adam_equiv function that validates QHAdamOptimizer equivalence to standard Adam', 'test that QHMOptimizer with beta=0.0 produces the same results as plain SGD GradientDescentOptimizer', 'test that QHMOptimizer with nu=1.0 produces the same results as MomentumOptimizer', 'run the test_plain_sgd_equiv function to verify QHMOptimizer equivalence with SGD optimizer', 'run the test_momentum_equiv function to verify QHMOptimizer equivalence with momentum optimizer', 'review the test_qhm module to understand QHMOptimizer equivalence tests against standard TensorFlow optimizers', 'build a TensorFlow variable and optional sparse gather tensor for optimizer testing', 'test two TensorFlow tensors for numerical closeness within absolute and relative tolerance', 'refactor the build_net function to support different sparse indexing strategies for TensorFlow variables', 'review the assert_optimizers_equal function and its linear regression loss setup for optimizer comparison']
```

Usage

```
{'test_plain_sgd_equiv': 'test that QHMOptimizer with beta=0.0 produces the same results as plain SGD GradientDescentOptimizer', 'test_momentum_equiv': 'test that QHMOptimizer with nu=1.0 produces the same results as MomentumOptimizer', 'run_test_plain_sgd_equiv': 'run the test_plain_sgd_equiv function to verify QHMOptimizer equivalence with SGD optimizer', 'run_test_momentum_equiv': 'run the test_momentum_equiv function to verify QHMOptimizer equivalence with momentum optimizer', 'review_test_qhm': 'review the test_qhm module to understand QHMOptimizer equivalence tests against standard TensorFlow optimizers'}
```

## File: facebookresearch_qhoptim/test_qhoptim/tf/util.py

Prompts

```
['test that QHAdamOptimizer with nu1=1.0 and nu2=1.0 produces identical results to tf.train.AdamOptimizer', 'test constructing QHAdamOptimizer with learning_rate, beta1, beta2, nu1, nu2, and epsilon parameters', 'test that two optimizer constructors produce equal optimization results using assert_optimizers_equal utility', 'review the QHAdamOptimizer class from qhoptim.tf to understand quantized Hessian Adam optimization', 'review the test_adam_equiv function that validates QHAdamOptimizer equivalence to standard Adam', 'test that QHMOptimizer with beta=0.0 produces the same results as plain SGD GradientDescentOptimizer', 'test that QHMOptimizer with nu=1.0 produces the same results as MomentumOptimizer', 'run the test_plain_sgd_equiv function to verify QHMOptimizer equivalence with SGD optimizer', 'run the test_momentum_equiv function to verify QHMOptimizer equivalence with momentum optimizer', 'review the test_qhm module to understand QHMOptimizer equivalence tests against standard TensorFlow optimizers', 'build a TensorFlow variable and optional sparse gather tensor for optimizer testing', 'test two TensorFlow tensors for numerical closeness within absolute and relative tolerance', 'refactor the build_net function to support different sparse indexing strategies for TensorFlow variables', 'review the assert_optimizers_equal function and its linear regression loss setup for optimizer comparison']
```

Usage

```
{'build_net_tensorflow_variable': 'build a TensorFlow variable and optional sparse gather tensor for optimizer testing', 'test_allclose_tensor_values': 'test two TensorFlow tensors for numerical closeness within absolute and relative tolerance', 'test_assert_optimizers_equal': 'test that two TensorFlow optimizer constructors produce identical variable updates over training iterations', 'refactor_build_net_sparse': 'refactor the build_net function to support different sparse indexing strategies for TensorFlow variables', 'review_assert_optimizers_equal': 'review the assert_optimizers_equal function and its linear regression loss setup for optimizer comparison'}
```

