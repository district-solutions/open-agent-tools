# Agent Python Tools

- repo: facebookresearch/beanmachine
- repo_uri: https://github.com/facebookresearch/beanmachine

## File: facebookresearch_beanmachine/tests/ppl/world/initialize_fn_test.py

Prompts

```
['test init_from_prior samples valid values from a torch distribution prior', 'test init_to_uniform initializes values within the support of a torch distribution', 'test that initialized values pass the distribution support check constraint', 'test that initialized values produce non-nan log probability values', 'test that initialized values match the expected sample shape of the distribution', 'test get_default_transforms returns identity for Bernoulli and Normal distributions and bijective for Gamma', 'test initialize_value returns zero for Normal distribution and unique samples when sampling from prior', 'run pytest on test_get_default_transforms to verify transform behavior across Bernoulli Normal and Gamma distributions', 'run pytest on test_initialize_value to verify initialization returns zero for Normal and unique samples from prior', 'review utils_test.py to verify test coverage for get_default_transforms and initialize_value functions', 'test the Variable class log_prob property recomputes when value or distribution fields are replaced', 'test the Variable replace method creates a new instance with an updated value tensor', 'test the Variable replace method creates a new instance with an updated distribution', 'test the Variable log_prob property returns a tensor with the correct dtype matching the value', 'test the Variable log_prob property raises RuntimeError when distribution support does not match the value', 'create a World with observations dict mapping random variables to observed tensor values', 'call a random variable on a World to add it and its parents to the graph', 'compute the log probability of all observations in a World given the model', 'replace observations in a World to create a new World with updated values', 'enumerate all possible outcomes of a discrete random variable node in a World']
```

Usage

```
{'test_init_from_prior': 'test init_from_prior samples valid values from a torch distribution prior', 'test_init_to_uniform': 'test init_to_uniform initializes values within the support of a torch distribution', 'test_initialize_validness_support_check': 'test that initialized values pass the distribution support check constraint', 'test_initialize_validness_log_prob': 'test that initialized values produce non-nan log probability values', 'test_initialize_validness_shape': 'test that initialized values match the expected sample shape of the distribution'}
```

## File: facebookresearch_beanmachine/tests/ppl/world/utils_test.py

Prompts

```
['test init_from_prior samples valid values from a torch distribution prior', 'test init_to_uniform initializes values within the support of a torch distribution', 'test that initialized values pass the distribution support check constraint', 'test that initialized values produce non-nan log probability values', 'test that initialized values match the expected sample shape of the distribution', 'test get_default_transforms returns identity for Bernoulli and Normal distributions and bijective for Gamma', 'test initialize_value returns zero for Normal distribution and unique samples when sampling from prior', 'run pytest on test_get_default_transforms to verify transform behavior across Bernoulli Normal and Gamma distributions', 'run pytest on test_initialize_value to verify initialization returns zero for Normal and unique samples from prior', 'review utils_test.py to verify test coverage for get_default_transforms and initialize_value functions', 'test the Variable class log_prob property recomputes when value or distribution fields are replaced', 'test the Variable replace method creates a new instance with an updated value tensor', 'test the Variable replace method creates a new instance with an updated distribution', 'test the Variable log_prob property returns a tensor with the correct dtype matching the value', 'test the Variable log_prob property raises RuntimeError when distribution support does not match the value', 'create a World with observations dict mapping random variables to observed tensor values', 'call a random variable on a World to add it and its parents to the graph', 'compute the log probability of all observations in a World given the model', 'replace observations in a World to create a new World with updated values', 'enumerate all possible outcomes of a discrete random variable node in a World']
```

Usage

```
{'test_get_default_transforms': 'test get_default_transforms returns identity for Bernoulli and Normal distributions and bijective for Gamma', 'test_initialize_value': 'test initialize_value returns zero for Normal distribution and unique samples when sampling from prior', 'run_test_get_default_transforms': 'run pytest on test_get_default_transforms to verify transform behavior across Bernoulli Normal and Gamma distributions', 'run_test_initialize_value': 'run pytest on test_initialize_value to verify initialization returns zero for Normal and unique samples from prior', 'review_utils_test': 'review utils_test.py to verify test coverage for get_default_transforms and initialize_value functions'}
```

## File: facebookresearch_beanmachine/tests/ppl/world/variable_test.py

Prompts

```
['test init_from_prior samples valid values from a torch distribution prior', 'test init_to_uniform initializes values within the support of a torch distribution', 'test that initialized values pass the distribution support check constraint', 'test that initialized values produce non-nan log probability values', 'test that initialized values match the expected sample shape of the distribution', 'test get_default_transforms returns identity for Bernoulli and Normal distributions and bijective for Gamma', 'test initialize_value returns zero for Normal distribution and unique samples when sampling from prior', 'run pytest on test_get_default_transforms to verify transform behavior across Bernoulli Normal and Gamma distributions', 'run pytest on test_initialize_value to verify initialization returns zero for Normal and unique samples from prior', 'review utils_test.py to verify test coverage for get_default_transforms and initialize_value functions', 'test the Variable class log_prob property recomputes when value or distribution fields are replaced', 'test the Variable replace method creates a new instance with an updated value tensor', 'test the Variable replace method creates a new instance with an updated distribution', 'test the Variable log_prob property returns a tensor with the correct dtype matching the value', 'test the Variable log_prob property raises RuntimeError when distribution support does not match the value', 'create a World with observations dict mapping random variables to observed tensor values', 'call a random variable on a World to add it and its parents to the graph', 'compute the log probability of all observations in a World given the model', 'replace observations in a World to create a new World with updated values', 'enumerate all possible outcomes of a discrete random variable node in a World']
```

Usage

```
{'test_Variable_log_prob': 'test the Variable class log_prob property recomputes when value or distribution fields are replaced', 'test_Variable_replace_value': 'test the Variable replace method creates a new instance with an updated value tensor', 'test_Variable_replace_distribution': 'test the Variable replace method creates a new instance with an updated distribution', 'test_Variable_log_prob_dtype': 'test the Variable log_prob property returns a tensor with the correct dtype matching the value', 'test_Variable_log_prob_runtime_error': 'test the Variable log_prob property raises RuntimeError when distribution support does not match the value'}
```

## File: facebookresearch_beanmachine/tests/ppl/world/world_test.py

Prompts

```
['test init_from_prior samples valid values from a torch distribution prior', 'test init_to_uniform initializes values within the support of a torch distribution', 'test that initialized values pass the distribution support check constraint', 'test that initialized values produce non-nan log probability values', 'test that initialized values match the expected sample shape of the distribution', 'test get_default_transforms returns identity for Bernoulli and Normal distributions and bijective for Gamma', 'test initialize_value returns zero for Normal distribution and unique samples when sampling from prior', 'run pytest on test_get_default_transforms to verify transform behavior across Bernoulli Normal and Gamma distributions', 'run pytest on test_initialize_value to verify initialization returns zero for Normal and unique samples from prior', 'review utils_test.py to verify test coverage for get_default_transforms and initialize_value functions', 'test the Variable class log_prob property recomputes when value or distribution fields are replaced', 'test the Variable replace method creates a new instance with an updated value tensor', 'test the Variable replace method creates a new instance with an updated distribution', 'test the Variable log_prob property returns a tensor with the correct dtype matching the value', 'test the Variable log_prob property raises RuntimeError when distribution support does not match the value', 'create a World with observations dict mapping random variables to observed tensor values', 'call a random variable on a World to add it and its parents to the graph', 'compute the log probability of all observations in a World given the model', 'replace observations in a World to create a new World with updated values', 'enumerate all possible outcomes of a discrete random variable node in a World']
```

Usage

```
{'create_world_with_observations': 'create a World with observations dict mapping random variables to observed tensor values', 'call_random_variable': 'call a random variable on a World to add it and its parents to the graph', 'compute_log_prob': 'compute the log probability of all observations in a World given the model', 'replace_world_observations': 'replace observations in a World to create a new World with updated values', 'enumerate_discrete_node': 'enumerate all possible outcomes of a discrete random variable node in a World'}
```

